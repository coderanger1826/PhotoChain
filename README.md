PhotoChain

Overview:
PhotoChain is a decentralized platform for uploading and sharing images on the blockchain. It uses Solidity for smart contract development and React for the front-end interface. Users can securely upload images to IPFS and manage access through smart contracts.

Features:
1. Decentralized Storage: Secure and immutable image storage on IPFS.
2. Smart Contract: Solidity-based contracts on Ethereum for ownership and access control.
3. Access Control: Manage image access via smart contracts.

Technologies Used:
1. Solidity: For smart contract development.
2. React: For the front-end interface.
3. IPFS: For decentralized image storage.

Installation:
1. Clone the repository: git clone https://github.com/coderanger1826/PhotoChain.git
2. Navigate to the root directory: cd PhotoChain
3. Install hardhat dependencies: npm install
4. Compile the smart contract: npx hardhat compile
5. Deploy the smart contract: npx hardhat run scripts/deploy.js --network <network-name>
6. Navigate to the React client directory: cd client
7. Install React dependencies: npm install
8. Start the React application: npm start

Configuration:
1. Set up environment variables:
    1. Obtain API keys for Pinata to interact with IPFS.
    2. Update the React component (FileUpload.js) with your Pinata API keys.
2. Install Metamask and configure it for Ethereum interactions.
3. Update the contract address in App.js after deploying the smart contract.

Usage Instructions:
1. Upload an image before clicking "Get Data" to avoid access errors.
2. Use the "Get Data" button with the user's address to access their images, granted they've given permission through the smart contract.