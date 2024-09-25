# Token Inscription Tool on Fractal Network

This project is for inscribing of text, image and any types of files on fractal network

---

A powerful **Token Inscription Tool** built for the **Fractal Network** that allows users to easily create, inscribe, and manage their tokens on the decentralized blockchain.

## Features
-  **Secure Token Creation**: Inscribe tokens directly onto the Fractal Network with robust security mechanisms.
-  **Fast and Efficient**: Optimized for speed and performance, making inscriptions quick and cost-effective.
-  **Flexible Token Standards**: Support for multiple token standards within the Fractal ecosystem.
-  **Easy Metadata Management**: Customize token metadata such as name, supply, and properties.
-  **Decentralized & Trustless**: Fully decentralized, ensuring a trustless environment for token creation and transactions.

## Prerequisites
To use the tool, ensure you have the following:
- Node.js >= v14
- Fractal Network Wallet
- Fractal Network RPC URL

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ptc-bink/fractal-inscription-tool.git
   cd fractal-inscription-tool
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file:
   ```bash
   cp .env.example .env
   ```

4. Update the `.env` file with your Fractal wallet's private key and RPC URL:
   ```bash
   PRIVATE_KEY=your_fractal_private_key
   FRACTAL_RPC_URL=https://rpc.fractalnetwork.io
   ```

## Usage

To inscribe a new token, run the following command:

```bash
npm run inscribe --tokenName="MyToken" --totalSupply=1000000 --decimals=18
```

This will inscribe a new token on the Fractal Network with the name **MyToken**, a total supply of **1,000,000**, and **18 decimals**.

### Parameters
- `--tokenName`: The name of the token you wish to create.
- `--totalSupply`: The maximum supply of the token.
- `--decimals`: Number of decimal places for the token.

Example command:
```bash
npm run inscribe --tokenName="FractalCoin" --totalSupply=100000 --decimals=8
```

### Additional Commands
- **Check Token Balance**:  
   You can check your token balance using:
   ```bash
   npm run balance --tokenAddress=<TokenAddress>
   ```

- **Transfer Token**:  
   To transfer tokens to another address:
   ```bash
   npm run transfer --tokenAddress=<TokenAddress> --recipientAddress=<RecipientAddress> --amount=100
   ```

## Contribution
Contributions are welcome! Feel free to open issues or pull requests.

### Steps to Contribute:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries or support, please reach out on our Discord or open an issue.

---

Feel free to customize this further to fit your specific project’s needs!
