# SoliditySimpleContract
This is the code written in Solidity I used to deploy my own smart-contract to Base blockchain testnet and create STRYCOINs

If you want to create your own ERC-20 crypto tokens just follow these steps:

1. Import this code into Solidity compiler as a strycoin.sol file (remix.ethereum.org)
2. When creating new workspace in a Solidity compiler choose OpenZeppelin ERC-20 standart
3. Click OK, change Token ticker from STRC to your own (10th string), it can be literally anything, like YEOF or FELKM. Whatever you choose
4. Also change Name of a contract (9th string) and decimals (amount of symbols after comma from 18 to anything of your choice
5. Click Ctrl+S to compile. Or Choose Solidity compiler on the left tab and click Compile strycoin.sol
6. Click on "Deploy and run transactions" tab, change your environment to "Injected Provider". As an injected provider you would use Metamask and approve this transaction.
If you want to deploy your crypto tokens completely for free you would choose any Testnet in Metamask and add Testnet tokens (For example, Goerli ETH or Base Goerli or Sepolia ETH) to your Metamask account.
In order to do that you have to choose any crypto FAUCET that sends testnet tokens to anyone in your testnet and aquire some testnet tokens. Otherwise you won't be able to pay gas for transactions, approve, deploy your new tokens to the blockchain testnet.
7. Once you have enough testnet ETH in your chosen testnet you can select this testnet in your metamask (Base Goerli Testnet in my example), connect it to RemixEthereum.org and RUN DEPLOY
8. Approve your contract deployment and check if the transaction is done in your testnet scanner, for example in https://goerli.basescan.org/
Done!
If you want to see your newly created tokens: Copy address of a new smart contract from base scanner (or etherscan), go to metamask, click import tokens, paste address of your smart contract and you'll see your tokens in metamask.

Now you can send it to friends, flex with it, just have fun!

P.S. Also, you can change contract settings in deploy section of Solidity compiler.
