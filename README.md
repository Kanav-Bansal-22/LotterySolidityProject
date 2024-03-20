GSDC LOTTERY SYSTEM PROJECT

Steps to Run Project:


Download voting.sol from GitHub folder and then import it into your Ethereum Development Environment such as Remix IDE.

In the code there are some Addresses like that of manager and participants. Replace the address of manager from which address you are going to deploy.

First, the manager deploys the contract. Then, participants join, and the ticket price for the lottery is set at 1 ether. Each participant can purchase more than one ticket individually to increase their chances of winning. A random number will be generated, and this random number will determine the index of the array of participants from which the winner will be selected. 90 percent of the total lottery amount will go to the winner, while the remaining 10 percent will go to the manager.

--> If you want to deploy contract on a test network like the Sepolia testnet, add your metamask wallet extension through your web browser and in Remix IDE change environment to "Injected Provider MetaMask" and in code change Manager Address to your MetaMask wallet address then select testnetwork and deploy.

Features of Lottery Project :

1.Secure: Utilizes the security and transparency of blockchain technology to ensure the integrity of the process.

2.Decentralized: No central authority.

3.User-Friendly: Easy interface for participants.

Tech Stacks Used :

Remix IDE
Metamask
Solidity
