JusticeChain
JusticeChain is a full-stack web application built to revolutionize how First Information Reports (FIRs) are submitted, prioritized, and verified. It empowers citizens to file FIRs digitally, uses AI/NLP to assess the seriousness of each case, and stores tamper-proof hashes of FIR details on the blockchain to ensure transparency and data integrity.

🚀 Features
🌐 Digital FIR Submission: Citizens can file FIRs through an intuitive web interface.

🧠 AI-Based Prioritization: Uses Groq's LLaMA3 model to classify FIRs as High, Medium, or Low priority.

🔐 Blockchain Verification: Hashes of FIRs are stored on the Ethereum Sepolia Testnet for tamper-proof records.

🗂 File Storage with IPFS: FIR-related media and documents are uploaded to IPFS via Pinata and linked to the blockchain.

👤 User Portal:

File new FIRs
View or download existing FIRs
🛡️ Admin Portal:

View all FIRs
Sort and filter by Title, Date, Priority, etc.
Update FIR status (e.g. Registered -> Under Investigation)
🛠️ Tech Stack
Frontend: React.js
Backend: Node.js, Express.js, MongoDB
AI Service: Groq API with LLaMA3
Blockchain: Ethereum (Sepolia Testnet), Smart Contracts
File Storage: Pinata + IPFS
🧑‍💻 Project Structure & Ports
Component	Technology Used	Port
Frontend	React	3000
Backend (MongoDB)	Node.js + Express + MongoDB	5000
Blockchain Service	Node.js (Ethereum)	4000
AI Classifier	Flask + Groq (LLaMA3)	5050
🔧 Getting Started
Prerequisites
Node.js
npm / yarn
MongoDB
Python (for AI server)



