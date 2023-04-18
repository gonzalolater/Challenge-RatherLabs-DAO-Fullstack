# DAO-FullStack - Challenge RatherLabs - Senior BlockChain Backend Engineer
The DAO

A DAO is a type of organization that is governed by smart contracts, which are self-executing computer programs that automatically enforce the rules of the organization. 
Members of the DAO can vote on proposals and decisions using their DAO tokens, and the smart contracts automatically execute the decisions based on the results of the vote. Essentially, a DAO is a decentralized organization that operates on a blockchain using smart contracts to facilitate decision-making and enforce rules.

Bare Minimum Requirements

In this case, you are tasked with developing a full-stack solution for a DAO that seeks to allow its token holders (ERC20) to vote on proposals generated 
by an admin on how to operate the organization 
- A single, or a set of smart-contracts to support the DAO.
- A command-line script that allows the admin create a new proposal on-chain with the following fields: Title, description, proposal deadline, minimum votes, option A and option B, and any other you deemed necessary.
- A backend module that when spun up, syncs up with all proposals to date, and serves all necessary information about such proposals through a REST API
- A frontend application
- Lists all proposals and their status (pending, closed, finished, option A won, option B won, etc)
- Allows to vote option A or option B

Bonus / Improvements

To stand out, feel free to add as much functionalities and capabilities as you like. Here are just some examples of functionalities you could add to stimulate your creativity.
- Implement quadratic voting
- Mint an NFT for each participation

Evaluation
- 100% bare minimum requirements completion
- Deploy your solution to a testnet of choice
- Aesthetic code, clean code (use linter)
- Elegant and simpler solution
- Senseful folder structure
- Care for security & production practices: Treat this code as if it were going to be deployed in mainnet

---------------------------------------------------------------------------------------------------------------------
[DAO - Fullstack + Web3.pdf](https://github.com/gonzalolater/DAO-FullStack/files/11261829/DAO.-.Fullstack.%2B.Web3.pdf)
---------------------------------------------------------------------------------------------------------------------

- Moralis Escrow Dao
Escrow contract governed by DAO using moralis on the frontend

-Technology Stack & Dependencies

-Solidity (Writing Smart Contract)

-Javascript (Game interaction)

-Infura As a node provider https://infura.io/

-NodeJS To create hardhat project and install dependencis using npm

1. Clone/Download the Repository
2. Install Dependencies: npm install
3. Deploy to hardhat network (local development blockchain) npx hardhat run src/backend/scripts/deploy.js
4. Run app
npm start
Flow of Execution
Join the DAO
Create a Proposal
Delegate
Vote
Move 5 Blocks - node src/backend/scripts/moveBlock5.js 
Queue
Move Time - node src/backend/scripts/moveTime.js 
Execute
Finally Claim the accrued interest.
---------------------------------------------------------------------------------------------
Smart Contract are deployed on mainnet, use some MATIC to interact with the front, or some USDC.
