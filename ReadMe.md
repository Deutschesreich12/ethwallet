# DAI Token Transfer DApp

This is a decentralized application (DApp) built using React that allows users to transfer DAI tokens. It interacts with the Ethereum blockchain using the Web3 library and the DaiTokenMock contract.

## Prerequisites

Make sure you have the following installed:

- Node.js
- MetaMask (or any other Ethereum wallet)

## Getting Started

To get started, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/dai-token-transfer-dapp.git`
2. Navigate to the project directory: `cd dai-token-transfer-dapp`
3. Install the dependencies: `npm install`
4. Start the development server: `npm start`
5. Open your web browser and go to `http://localhost:3000`

## How It Works

1. Connect your Ethereum wallet (e.g., MetaMask) to the DApp.
2. You should see your account address and the balance of DAI tokens associated with it.
3. To transfer tokens, enter the recipient's address and the amount you want to send.
4. Click the "Send" button to initiate the transfer.
5. Confirm the transaction in your wallet.
6. The table below will display a list of previous transfers, including the recipient's address and the transferred amount.

## Notes

- If you are using a non-Ethereum browser, you will be prompted to install MetaMask or use an Ethereum-compatible browser.
- The DAI token address is currently set to a mock address (`0x7b729B07EcBDEd8879Acf997aAF6546926982830`). Replace it with the actual DAI token address in the `loadBlockchainData()` function if you are using a different network.

## Resources

- [Dapp University](http://www.dappuniversity.com/bootcamp) - Learn more about blockchain development.

## License

This project is licensed under the [MIT License](LICENSE).
