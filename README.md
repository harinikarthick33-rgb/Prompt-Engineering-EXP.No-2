EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

PARAGRAPH BEFORE APPLYING PROMPTING TECHNIQUES:

Blockchain technology is a decentralized digital system designed to securely record, store, and verify transactions across a distributed network of computers. Unlike traditional databases that are controlled by a central authority, blockchain operates through a peer-to-peer network where every participant, known as a node, has access to a shared ledger. This ledger records all transactions in a transparent and secure manner, making it difficult for any single party to manipulate the data.

The core structure of blockchain consists of a chain of blocks. Each block contains a list of transactions, a timestamp, and a cryptographic hash that links it to the previous block. This connection forms a continuous chain, ensuring that once a block is added to the blockchain, the information within it cannot easily be altered. If someone tries to change the data in a block, the hash would also change, breaking the chain and immediately alerting the network. This design makes blockchain highly secure and resistant to tampering.

One of the key characteristics of blockchain technology is decentralization. Instead of relying on a central authority such as a bank or government institution, blockchain networks distribute control among multiple participants. Each node in the network maintains a copy of the blockchain, ensuring that the system remains operational even if some nodes fail or are compromised. This decentralization increases reliability and reduces the risk of data loss or corruption.

Another important feature is transparency. In most blockchain systems, all transactions are visible to participants in the network. This openness helps build trust among users because every transaction can be verified. At the same time, blockchain maintains privacy through cryptographic techniques that protect the identities of users while still allowing transactions to be validated.

Blockchain technology gained global attention through cryptocurrencies like **Bitcoin**, but its applications extend far beyond digital currencies. Today, blockchain is being explored in industries such as supply chain management, healthcare, finance, voting systems, and digital identity management. By providing a secure, transparent, and decentralized way to record and share data, blockchain has the potential to transform many sectors and improve the efficiency and trustworthiness of digital transactions.

USING CHATGPT:
Zero-shot summary:

Blockchain technology is a decentralized digital ledger used to record transactions securely and transparently across a network of computers. Instead of relying on a central authority, blockchain allows multiple participants to maintain and verify the data collectively. This decentralized structure increases trust and reduces the risk of data manipulation.

A blockchain is made up of blocks that store transaction data. Each block contains a timestamp, transaction details, and a cryptographic hash that connects it to the previous block, forming a chain. This structure ensures that once data is recorded, it cannot easily be changed, making the system highly secure and reliable.

Blockchain networks use consensus mechanisms to validate transactions before they are added to the chain. These mechanisms ensure that all participants agree on the accuracy of the data, preventing fraud and double spending.

Blockchain technology became widely known through cryptocurrencies such as **Bitcoin**, but its use is expanding to other areas like supply chain management, healthcare, finance, and digital identity verification. Overall, blockchain provides a transparent, secure, and efficient way to store and share digital information.

Few-short summary:

Blockchain technology is a decentralized digital ledger that records transactions securely across a network of computers. Instead of relying on a central authority, multiple participants in the network verify and store the information. Transactions are grouped into blocks, and each block is linked to the previous one using cryptographic hashes, forming a continuous chain. This structure makes the data difficult to alter and ensures transparency and security.

Blockchain networks use consensus mechanisms to validate transactions before adding them to the chain, preventing fraud and double spending. The technology became widely known through cryptocurrencies such as **Bitcoin**, but it is also used in many other areas like supply chain management, healthcare, finance, and digital identity systems. Overall, blockchain provides a reliable, transparent, and decentralized way to record and share digital information.

Chain-of-Thought Summary: 

Blockchain technology is a decentralized system used to record and manage digital transactions securely. Instead of storing data in a central database controlled by one organization, blockchain distributes the data across a network of computers called nodes. This decentralized structure improves transparency and reduces the risk of manipulation.

The technology works by grouping transactions into blocks. Each block contains transaction data, a timestamp, and a cryptographic hash that links it to the previous block. These blocks are connected in chronological order, forming a chain known as a blockchain. Because each block is connected to the previous one, altering the information in a single block would require changing all the following blocks, which makes the system highly secure and resistant to tampering.

Before a new block is added to the chain, the network must verify the transactions using a consensus mechanism. This process ensures that all participants agree that the transaction is valid. Common consensus methods include Proof of Work and Proof of Stake. These mechanisms help maintain trust and prevent issues like fraud or double spending.

Blockchain technology gained global recognition through cryptocurrencies such as **Bitcoin**. However, its potential applications extend far beyond digital currencies. Many industries are exploring blockchain for uses such as supply chain tracking, secure healthcare data management, financial services, voting systems, and digital identity verification.

In conclusion, blockchain technology provides a secure, transparent, and decentralized way of recording and sharing information. Its ability to protect data integrity and remove the need for intermediaries makes it a promising technology for many modern digital systems.

Role-Based Summary (Researcher):

From a researcher’s perspective, blockchain technology represents a decentralized and distributed ledger system designed to securely record and verify digital transactions. Unlike traditional centralized databases, blockchain operates through a peer-to-peer network in which multiple nodes maintain and validate a shared record of transactions. This decentralized structure enhances transparency, security, and reliability while reducing dependence on a central authority.

Blockchain stores data in units called blocks. Each block contains transaction information, a timestamp, and a cryptographic hash that connects it to the previous block, forming a continuous chain. This design ensures immutability, meaning that once data is recorded, it is extremely difficult to modify without altering the entire chain. As a result, blockchain provides strong data integrity and protection against tampering.

Another key component of blockchain systems is the consensus mechanism, which is used to validate transactions before they are added to the ledger. Consensus protocols such as Proof of Work and Proof of Stake allow network participants to collectively agree on the accuracy of transactions, preventing fraudulent activities like double spending. These mechanisms maintain the reliability and trustworthiness of the distributed network.

Blockchain technology first gained widespread attention through cryptocurrencies such as **Bitcoin**. However, researchers are now exploring its broader applications across multiple domains. Potential use cases include supply chain management, healthcare data management, financial services, digital identity verification, and secure voting systems.

From an academic and research standpoint, blockchain is considered a transformative technology due to its potential to improve transparency, reduce intermediaries, and enhance data security in digital systems. Ongoing research focuses on improving scalability, energy efficiency, interoperability, and regulatory frameworks to support wider adoption. Overall, blockchain continues to evolve as a significant innovation with the potential to reshape various sectors of the digital economy.

USING COPILOT:

Zero-shot summary:

Blockchain is a decentralized digital ledger that records transactions across a network of computers. Each transaction is stored in a block, linked cryptographically to the previous one, making the chain secure and tamper-resistant. It operates without a central authority, relying instead on consensus mechanisms like Proof of Work or Proof of Stake. Transparency ensures all participants can verify transactions, while cryptography protects user identities. Though first popularized by Bitcoin, blockchain now supports diverse applications in finance, healthcare, supply chains, and digital identity.
Blockchain is like a digital notebook shared among many people. 

few-shot summary:

Banking: Instead of one bank keeping records, everyone in the network has the same ledger.

Supply Chains: A company can track goods from factory to store, with each step recorded transparently.

Voting: Votes can be securely stored so no one can tamper with them.

Across these examples, the core idea is the same: a decentralized, secure, and transparent system that builds trust without needing a central authority.

Chain-of-Thought summary:

Identify the structure: Blockchain is made of blocks linked together by cryptographic hashes.

Assess security: Any change in a block alters its hash, breaking the chain — ensuring tamper resistance.

Consider decentralization: No single authority controls the ledger; nodes share responsibility.

Evaluate transparency vs. privacy: Transactions are visible, but identities remain protected.

Consensus mechanisms: Proof of Work and Proof of Stake validate transactions.

Applications: Beyond cryptocurrency, blockchain impacts industries like supply chain, healthcare, and voting.

Role-Based (Researcher):

As a researcher, I view blockchain as a paradigm shift in digital trust systems. Its decentralized architecture challenges traditional centralized models by distributing control across nodes. The immutability of blocks, enforced through cryptographic hashing, ensures data integrity. Transparency fosters accountability, while consensus mechanisms safeguard against fraud. Current research explores scalability, energy efficiency, and interoperability across networks. While cryptocurrencies remain the most visible application, ongoing studies highlight blockchain’s potential in critical areas such as secure medical records, resilient supply chains, and democratic voting systems. The technology represents not just a tool, but a foundational infrastructure for the next generation of digital ecosystems.

USING GEMINI

Zero shot summmary:

Blockchain technology is a decentralized, distributed ledger system that records and verifies transactions across a global network of nodes. By utilizing a linked chain of blocks secured by cryptographic hashes, it ensures data integrity and prevents tampering. Its core strengths lie in decentralization, which removes the need for central authorities, and transparency, which fosters trust through public verifiability. Regulated by consensus mechanisms like Proof of Work, blockchain has evolved beyond cryptocurrency to provide secure, efficient solutions for industries like healthcare, finance, and supply chain management.

Few-shot summary:

Example 1 (AI): Artificial Intelligence mimics human intelligence to perform complex tasks and learn from data.

Example 2 (Cloud Computing): Cloud computing provides on-demand access to computing resources over the internet without local management.

chain-of-Summary:

Blockchain is a peer-to-peer digital ledger that uses decentralization and cryptography to ensure secure, transparent, and immutable data records across various industries.

Step 1: Identify the Core Definition. Blockchain is a decentralized digital system for recording/storing transactions across a distributed network (no central authority).

Step 2: Explain the Technical Structure. It uses a "chain of blocks" where each block contains data, a timestamp, and a cryptographic hash linking it to the previous one, making it tamper-proof.

Step 3: Highlight Key Features. The pillars are decentralization (no single point of failure), transparency (publicly verifiable), and consensus mechanisms (agreements like Proof of Work to prevent fraud).

Step 4: Note Evolution and Application. Originally for Bitcoin, it is now applied to supply chains, healthcare, and voting for its security and efficiency.

Final Synthesis: Blockchain is a tamper-resistant, decentralized ledger system. By linking data blocks via cryptography and validating them through network consensus, it eliminates the need for central intermediaries. While famous for powering cryptocurrency, its inherent transparency and reliability are currently transforming data management across diverse global sectors.

Role-based summary (researcher):

"From a systems-architecture perspective, blockchain represents a paradigm shift from centralized silos to distributed trust. Our analysis reveals that the technology’s primary value proposition is its immutability, achieved through the sequential hashing of data blocks. By distributing the ledger across a peer-to-peer network, we eliminate 'single points of failure' common in traditional database management. Furthermore, the integration of consensus protocols ensures Byzantine Fault Tolerance, allowing the network to maintain integrity even in the presence of malicious actors. While initially a financial tool, the research suggests that blockchain’s true potential lies in its ability to provide a 'single source of truth' for complex, multi-stakeholder environments like global supply chains and digital identity frameworks."

| Prompt Technique | Platform      | Accuracy | Coherence | Simplicity | Speed | UX |
| ---------------- | ------------- | -------- | --------- | ---------- | ----- | -- |
| Zero-Shot        | ChatGPT       | 4        | 4         | 4          | 5     | 4  |
| Zero-Shot        | Copilot      | 4        | 4         | 4          | 4     | 4  |
| Zero-Shot        | Google Gemini | 4        | 5         | 4          | 4     | 4  |
| Few-Shot         | ChatGPT       | 4        | 4         | 4          | 5     | 4  |
| Few-Shot         | Copilot        | 5        | 5         | 4          | 4     | 4  |
| Few-Shot         | Google Gemini | 5        | 5         | 4          | 3     | 5  |
| Chain-of-Thought | ChatGPT       | 5        | 5         | 4          | 4     | 4  |
| Chain-of-Thought | Copilot        | 5        | 5         | 4          | 4     | 4  |
| Chain-of-Thought | Google Gemini | 5        | 5         | 4          | 3     | 5  |
| Role-Based       | ChatGPT       | 4        | 5         | 4          | 5     | 4  |
| Role-Based       | Copilot       | 5        | 5         | 4          | 4     | 4  |
| Role-Based       | Google Gemini | 5        | 5         | 4          | 3     | 5  |


RESULT:
 Thus, the summarized Result section based on the experiment using the three prompt types (zeroshot, few-shot, chain-of-thought, role-based) and two AI platforms (ChatGPT,Gemini and Claude).


