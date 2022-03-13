1. npm install - To install all the dependences

Now make an account on Alchemy : https://www.alchemy.com

Alchemy is the service that we are  using to connect to test ethereum network ropster



2.  npx hardhat - inside the project folder to create hardhat project

select create an empty config.js in hardhat pop-up.


Then, create a .env file in the root directory of our project, and add your MetaMask private key and HTTP Alchemy API URL to it.

3. npx hardhat compile - To compile the contract 

4. Change scripts/deploy.js file - just add the contract name that you want to deploy

5. npx hardhat --network ropsten run scripts/deploy.js  - To deploy your contract