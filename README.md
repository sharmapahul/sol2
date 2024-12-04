
### Solarium Wallet App  
The **Solarium Wallet App** is a simple and user-friendly Solana wallet interface built with React and the Solana Web3.js library. It empowers users to set up a sender account, connect their wallet via the Phantom browser extension, disconnect seamlessly, and execute SOL transfers efficiently.

---

### **Prerequisites**  

Before you start using the app, ensure you have the following:  

1. **Node.js**: Install Node.js and npm (Node Package Manager) from [Node.js official site](https://nodejs.org/).  
2. **Phantom Wallet**: Install and configure the Phantom browser extension for wallet integration.  

---

### **Getting Started**  

Follow these steps to set up and run the application:

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```  

2. **Navigate to the project folder**:  
   ```bash
   cd your-repo-name
   ```  

3. **Install dependencies**:  
   ```bash
   npm install
   ```  

4. **Launch the application**:  
   ```bash
   npm start
   ```  
   Access the app at [http://localhost:3000](http://localhost:3000) in your browser.  

---

### **Features**  

#### 1. **Initialize Sender Account**  
   - Generate a fresh sender account using the "Initialize Sender" button.  
   - Automatically airdrops 1 SOL to the sender account for use in transactions.  

#### 2. **Wallet Connection**  
   - Utilize the "Connect Wallet" option to link your Phantom wallet.  
   - Displays the wallet's public address upon connection.  

#### 3. **Wallet Disconnection**  
   - Use the "Disconnect Wallet" button to unlink your wallet instantly.  

#### 4. **SOL Transfers**  
   - Transfer 2 SOL from the sender account to the connected wallet.  
   - Requires both sender initialization and wallet connection before executing.  

---

### **Key Considerations**  

- Ensure that the Phantom wallet is installed and unlocked in your browser before attempting to connect.  
- The app runs on the Solana **Devnet** cluster by default. Update the `clusterApiUrl` setting in the source code to switch clusters if needed.  

---

### **Contributions**  

We welcome contributions! If you’d like to improve this project, feel free to:  

- Submit pull requests with enhancements or fixes.  
- Report issues or share feedback.  

---

### **License**  

This project is distributed under the MIT License. For more details, refer to the `LICENSE` file in the repository.  
