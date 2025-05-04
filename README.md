Recurring Payment DApp on Algorand
==================================

This is a basic decentralized application (DApp) that enables recurring payments on the Algorand blockchain using PyTeal smart contracts.

Project Structure
-----------------
recurring-payment-dapp/
├── contract.py              # PyTeal smart contract code
├── frontend/
│   ├── index.html           # Basic HTML UI
│   ├── style.css            # Simple CSS styling
│   └── app.js               # Placeholder JS logic

How It Works
------------
- The smart contract makes a payment to a specific address at defined time intervals.
- You can trigger payments through the frontend (simulation only in this example).
- Customize the contract with your desired recipient, amount, and interval.

Requirements
------------
- Python 3.7+
- PyTeal

Setup Instructions
------------------
1. Install PyTeal:
    pip install pyteal

2. Compile the Smart Contract:
    python contract.py > approval.teal

3. Open the Frontend:
    - Navigate to the `frontend/` directory.
    - Open `index.html` in your browser.

Notes
-----
- This project is a simulation and does not integrate with the Algorand blockchain or wallets.
- Use tools like Reach or Algorand SDKs (Python, JS) to enable full deployment and interaction.

License
-------
This project is open-source and free to use for educational purposes.
