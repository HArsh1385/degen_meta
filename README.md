# DegenToken

**DegenToken** is an ERC20 token deployed on the Avalanche network, designed specifically for Degen Gaming. This smart contract enables the owner to mint new tokens, while players can transfer, redeem, and burn tokens, as well as check their token balances at any time.

## Features

- **Minting New Tokens:** The contract owner can mint new tokens and distribute them as rewards to players.
- **Transferring Tokens:** Players can transfer tokens to other players.
- **Redeeming Tokens:** Players can redeem tokens for in-game items through the platform's store.
- **Checking Token Balance:** Players can check their token balances at any time using the contract.
- **Burning Tokens:** Players can burn unwanted tokens to remove them from circulation.

## Deployment

To deploy the DegenToken contract on the Avalanche network using Remix IDE and MetaMask, follow these steps:

1. **Open Remix IDE:** Visit [Remix IDE](https://remix.ethereum.org/).
2. **Load Contract Code:** Copy the DegenToken smart contract code and paste it into a new file named `DegenToken.sol` in Remix IDE.
3. **Compile the Contract:**
   - Navigate to the "Solidity Compiler" tab.
   - Select the Solidity version `0.8.20`.
   - Click "Compile DegenToken.sol".
4. **Deploy the Contract:**
   - Go to the "Deploy & Run Transactions" tab.
   - Select "Injected Web3" as the environment to connect to MetaMask.
   - Ensure MetaMask is connected to the Avalanche network.
   - Select the `DegenToken` contract from the dropdown menu.
   - Click "Deploy" and confirm the transaction in MetaMask.
5. **Verify Contract on Snowtrace:**
   - Copy the deployed contract address from Remix IDE.
   - Visit [Snowtrace Testnet](https://testnet.snowtrace.io/).
   - Paste the contract address into the search bar to view transaction details.

## Usage

Once deployed, the following functions are available for interacting with the DegenToken contract:

- **Mint Tokens:** Only the owner can mint new tokens using the `mint` function.
- **Transfer Tokens:** Use the `transfer` function to send tokens to another player’s address.
- **Redeem Tokens:** Call the `redeem` function to exchange tokens for items in the in-game store.
- **Check Balance:** Use the `balanceOf` function to view your current token balance.
- **Burn Tokens:** Call the `burn` function to permanently destroy tokens you no longer need.

## Events

- **ItemRedeemed:** Emitted whenever a player successfully redeems tokens for an item in the game.
