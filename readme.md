## Step - 1 : Set Up MetaMask:
**1. Install MetaMask :**
- Follow the [Link](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn) to install the Google Chrome Extension. 
   
**2. Create or Import a Metamask Wallet**
   
- To create a Metamask Wallet: Follow the [Link](https://myterablock.medium.com/how-to-create-or-import-a-metamask-wallet-a551fc2f5a6b)
```
Note : 
- While creation of the Metamask Wallet, you will be asked to select 12 pass phrase
- Keep the passphrase safley
- It becomes handy to recover your password
```
  
- To import an existing Metamask Wallet : Watch the [video](https://www.youtube.com/watch?v=GS1asrK0glI)

**3. Fund Your Wallet from any Testnet:**
  
* [Sepolia Testnet](https://github.com/LifnaJos/Getting-funds-from-Testnets-to-Metamask-Wallet#steps-to-get-funds-from-sepolia-testnet) (0.5 ETH per day)
  
* [RSK Testnet](https://github.com/LifnaJos/Getting-funds-from-Testnets-to-Metamask-Wallet#steps-to-get-funds-from-rsk-testnet)  (0.05 RBTC per day)

## Step - 2 : Connect the Sepolia Testnet  / RSK Testnet to Remix IDE
**1. In the Remix IDE, select the Environment as Injected Web3.**

*Note : Injected Web3 connects Remix with the active account in Metamask.*

![select_env](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/Screenshot%20from%202023-09-12%2023-07-49.png)

**2. Once the Injected Web3 Provider is selected as Metamask, the following popup appears.**

![metamask](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask.jpg)

**3. Select the account to be linked with and Click ```Next``` Button.**

![metamask_connect](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_connect.jpg)

**4. Click on ```Connect``` button. Once the Account is linked to Remix IDE, the Metamask Account details appears in the Deployment Environment as follows:**

![metamask acc](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_acc.jpg)   

## Step - 3 : Create a Simple Solidity Smart Contract
- As per Experiment 4
  
## Step - 4 : Compile and Deploy the Smart Contract.

**1. Once the Contract is deployed on Remix IDE, the popup appears to confirm the Contract Deployment.**

![metamask_1](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_1.jpg)
 
**2. As the Deployment is in progress the following popup appears, stating that the deployment is in progress**

![metamask_2](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_2.jpg)

**3. Once the transaction is confirmed the status of the transaction is displayed**

![metamask_3](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_3.jpg)

**4. Transaction Deployment details are displayed, w.r.t the Gas Limit, Used, Gas Used, Gas Price and Total Amount**

![metamask_4](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_4.jpg)

**5. In Remix IDE terminal, the transaction details are displayed**

![metamask_5](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/metamask_5.jpg)

## Step - 5 : Check the transaction details on the RSK Explorer
**1. Open** ```https://explorer.testnet.rsk.co/```

**2. Enter the Block Hash / Transaction Hash on the Search. The details of the transactions are displayed as follows**

![RSK_explorer_1](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/rsk_explorer_1.jpg)

**3. Scroll down to see the Transaction in the respective block**

![rsk_explorer_2](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/rsk_explorer_2.jpg)

**4. Further, we can check the Account which was associated with the Deployemnt of Contract**

![rsk_explorer_3](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/blob/main/images/rsk_explorer_3.jpg)

## Step - 6 : Interact with the smart contract 
- As per Experiment 6

## Acknowledgement
* [Metamask](https://support.metamask.io/hc/en-us/articles/360015489531-Getting-started-with-MetaMask) to understand how to install Metamask Wallet

* [Hackernoon](https://hackernoon.com/how-to-use-remix-and-metamask-to-deploy-smart-contracts-on-the-rsk-testnet-zt393xfz) for the article on "How to use Remix IDE and Metamask to deploy smart contracts on the RSK Testnet

* [Basic Writing & Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
