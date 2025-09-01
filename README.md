# BLOCKCHAIN-ASSIGNMENT
🪙 Simple Blockchain in Python

This project is a basic implementation of a blockchain written in Python. It demonstrates the fundamental concepts of blockchain technology such as:

✅ Blocks containing data, timestamp, and hash

✅ Chaining through previous block hashes

✅ Proof of Work (mining) with adjustable difficulty

✅ Genesis Block creation

✅ Chain validation to ensure integrity

🚀 Features

Block Structure – Each block stores index, timestamp, data, nonce, previous hash, and its own hash.

Proof of Work – Mining requires finding a hash with a certain number of leading zeros (difficulty).

Validation – Ensures that the blockchain is consistent and untampered.

Custom Data – You can store any data (e.g., transactions) inside blocks.

📂 Project Structure
blockchain.py    # Main blockchain implementation

🛠️ Usage

Clone this repository:

git clone https://github.com/your-username/simple-blockchain-python.git
cd simple-blockchain-python


Run the blockchain:

python blockchain.py


Example Output:

Mining block 1...
Block mined: 000a93f2c67d5...
Mining block 2...
Block mined: 000fcd4123b...
{'index': 0, 'previous_hash': '0', 'timestamp': 1693605642.123, 'data': 'Genesis Block', 'nonce': 238, 'hash': '000e7a...'}
{'index': 1, 'previous_hash': '000e7a...', 'timestamp': 1693605643.456, 'data': {'amount': 100}, 'nonce': 129, 'hash': '000d4f...'}
{'index': 2, 'previous_hash': '000d4f...', 'timestamp': 1693605645.789, 'data': {'amount': 50}, 'nonce': 382, 'hash': '000c91...'}
Blockchain valid? True

📖 Concepts Covered

Hashing with SHA-256

Proof of Work (PoW) consensus mechanism

Blockchain immutability through cryptographic linking

Data integrity verification

🧩 Future Improvements

Add transaction support with multiple fields

Implement peer-to-peer network for distributed blockchain

Add Merkle Trees for transaction verification

Explore Proof of Stake (PoS)

📜 License

This project is open-source and available under the MIT License.
