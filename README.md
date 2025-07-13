# 🧱 MiniChain: A Simple Blockchain Simulation

MiniChain is a lightweight educational blockchain prototype built with Python. It simulates fundamental blockchain concepts including hash-linked blocks, proof-of-work mining, wallet balances, transaction validation, and ledger immutability.

---

## 🚀 Features

- 🔐 **Secure Hashing** with SHA-256
- 🧾 **Simulated Transactions** between users (`Vinny` and `Kinny`)
- 🔗 **Block Chaining** using hash pointers
- ⛏️ **Proof-of-Work Mining** with adjustable difficulty
- 💼 **Wallet Balance Tracking** with overdraft protection
- 💾 **Blockchain Export** to JSON file

---

## 🛠️ Technologies Used

- Python 3.x
- Built-in libraries: `hashlib`, `json`, `random`, `sys`, `time`

---


---

## 📋 How It Works

1. **Transaction Generation**  
   Random token transfers between Vinny and Kinny are created and validated (no overdrafts).

2. **Block Mining**  
   Valid transactions are grouped into blocks. Each block is mined using proof-of-work (leading zeros in the hash).

3. **Reward System**  
   Each successfully mined block includes a reward transaction for the `Miner`.

4. **Chain Construction**  
   Blocks are linked using SHA-256 hashes to ensure immutability.

5. **Final Output**  
   The full blockchain and wallet balances are printed and saved to `blockchain_data.json`.

---

## ▶️ Run the Project

```bash
python3 blockchain_simulation.py
