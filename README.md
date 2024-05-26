# Eth-Avax-frontend-integration

## The FUNCTIONALITIES added to the starter Project

1. Styling the whole content is centered on the page. Before, it was just horizontally now it is both vertically and horizontally centered.
2. Added the functionality of Depositing and Withdrawing the ETHs according to your desire i.e. you can change the amount of ETH you can transfer.
3. Previously, If you Withdrew more than the balance the page crashes and the error was shown from blockchain. Now, if you Withdraw more (handled on  the frontend) the transaction doesn't go through and an alert message is shown.

## To start the PROJECT
After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.
6. This will launch the frontoend at localhost:3000
