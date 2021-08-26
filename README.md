# Kasei Coin Contract & Crowdsale

In this project, we endeavor to develop a monetary system for the first human colony on Mars.  This monetary system will be developed on a blockchain, and we will mint tokens called Kasei coins.  This token will be a **fungible token** and **ERC-20** compliant.  We will also use the **crowdsale** method for users to purchase these tokens.

## Installation & Use

In order to run these contract, please do the following:

1. Open up **Remix IDE** and open up the files **KaseiCoin.sol** and **KaseiCrowdsale.sol**.
2. Go to the left-hand menu in Remix, look for the **Solidity compiler** icon.
3. Once there, make sure on the first field under **Compiler**, you set it to **0.5.0** for the **KaseiCoin.sol** contract, and **0.5.5** for the **KaseiCrowdsale.sol** contract.
5. Hit the **Compile (Solidity File)** button.
6. If the compilation is successful, you will then be able to deploy the contract.  However if it is unsuccessful, read the error messages for debugging.

## Deploying Contracts on the Blockchain

In order for the contracts to be deployed on the blockchain, you should have **Ganache** and **Metamask** installed.

In Ganache, you will pull test accounts to use with the contracts as you see here:

![ganache](https://user-images.githubusercontent.com/80929342/131048459-708a4e06-679e-4999-ac14-1b3b57bdb21c.JPG)

You will use the **private keys** from Ganache's test accounts to import accounts into **Metamask**, as you can see here:

![metamask](https://user-images.githubusercontent.com/80929342/131048517-e7a634e0-3fee-43bc-882d-976ee8c53466.JPG)

Back in **Remix**, go to the **Deploy & run transactions** icon on the left hand menu, and set the environment to **Injected Web3**.
This should automatically open up Metamask and you can choose which account in Metamask you want to use for deploying the contract.

## Evaluation Evidence

The following screenshot shows the successful compliation of the **Kasei Coin** contract:

![evaluation_evidence_1](https://user-images.githubusercontent.com/80929342/131043467-85be02ff-3a6c-4387-aaa8-6db08ce27272.JPG)

The next screenshot shows the successful compilation of the **Kasei Crowdsale** and **Kasei Crowdsale Deployer** contract:

![evaluation_evidence_2](https://user-images.githubusercontent.com/80929342/131043477-3eaee977-cd93-4034-888f-694dad35b0ba.JPG)

