# MedicalBlockchain

This project implements a Medical Blockchain using Python and Flask. It is designed to securely store and share medical permissions between patients and doctors. The blockchain ensures the integrity and transparency of the data, which includes patient access permissions for doctors.

Key Features:
Blockchain Creation: A blockchain is created where each block contains proof of work, a timestamp, and medical transactions.
Mining: Nodes can mine blocks by solving proof-of-work problems, ensuring network consensus.
Transactions: Patients can add permissions for doctors, and these permissions are added as transactions in the blockchain.
Decentralization: Nodes can join the network, and the blockchain can be updated with the longest valid chain.
Validation: The blockchain can be validated to ensure it remains secure and untampered with.
API Endpoints:
/mine_block: Mines a new block and adds a medical transaction.
/get_chain: Retrieves the full blockchain.
/is_valid: Checks if the blockchain is valid.
/add_transactions: Adds a medical transaction (patient permission).
/connect_node: Connects additional nodes to the blockchain network.
/replace_chain: Replaces the current chain with the longest valid chain.
This implementation is designed for educational and experimental purposes in managing patient-doctor permissions using blockchain technology.
