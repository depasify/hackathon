# Tech Unpacked #2: Fintech Goes Web3

Join us on May 9th for the second edition of Tech Unpacked, a series of events hosted by GoHub Ventures to explore cutting-edge technologies.

​This time, Web3 takes center stage! The session will be a hands-on exploration of how Web3 is changing the fintech sector, where we will discover the meaning of wallets, nodes, and how to make transfers.

​Attendees will explore integrating blockchain with Depasify APIs for real-world financial applications, like sending a payment from Spain to Colombia in 10 seconds 💸 or treating a friend to a beer straight from your wallet 🍺

​We'll wrap up the event with some casual networking, beers, and pizza on us!

## AGENDA

1. ​​6:00pm | Fintech Goes Web3 💸
2. ​​6:30pm | Hackathon: Blockchain for real-world financial applications 🔗
3. ​​8:30pm | Networking, Beers & Pizza 🍕

## Hackathon: Blockchain for real-world financial applications

Welcome to the Blockchain Hackathon!

Here are the key objectives for all participants:

**Prerequisite: Ready-to-Use Wallet:**
Ensure you have a prepared and ready-to-use wallet before starting.

### Register at Depasify platform (stage):
Sign up on our dedicated hackathon portal to receive tokens for the event.

[https://sandbox.depasify.com/hackathon/sign-in](https://sandbox.depasify.com/hackathon/sign-in)

After registering, you will be redirected to a page where you will see some details that you will need to do the hackathon.

The token is **Gohub Hack (GHH)**, it's in Ethereum Sepolia network, you can find all the information about the token and the contract in [sepolia.etherscan.io](https://sepolia.etherscan.io/token/0x8efa809bc27a9d25772b1c1ab69b87462d0312d8#code). Probably for next steps, you will need the contract address and the abi code.

### Send some Tokens to Depasify Wallet:
Using your desired coding language, send some of the tokens you received to the next Depasify wallet using native transfer technology. We recommend using Python or JavaScript, and web3 packages, but there are more available.

The depasify wallet is: **0x64bc5be8db527c53fdbfbb2a7f928f5dbeff4721**.

### Send the Transaction to Depasify Platform:
After completing the transaction to the Depasify wallet, send it to our platform using the API Link Blockchain Payment Depa. This way you can operate your digital assets with our platform.

You can find the documentation here: [https://depasify.readme.io/reference/post_accounts-account-id-link-blockchain-payment](https://depasify.readme.io/reference/post_accounts-account-id-link-blockchain-payment).

**Important**: Please, include a "currency" field in the payload with the value "GHH".

### Exchange Tokens for Fiat (Depa Trade API):
Explore exchanging your tokens for fiat currency using the Depa Trade API.

You can find the documentation here: [https://depasify.readme.io/reference/post_accounts-account-id-trades](https://depasify.readme.io/reference/post_accounts-account-id-trades)

The currency pair you must trade is **GHHEUR**.

### Pay for Beer (Fiat Payment to Gohub Account):
Finally, try the fiat payment process to buy a beer. Use fiat payment to the Gohub account and experience blockchain transactions in everyday scenarios.

You can find the documentation here: [https://depasify.readme.io/reference/post_accounts-account-id-bank-accounts-bank-account-id-fiat-payments](https://depasify.readme.io/reference/post_accounts-account-id-bank-accounts-bank-account-id-fiat-payments)

The Gohub IBAN is: **ES7767130002000000000302**, please include your name as the description.

-----

We're excited to have you on board and hope this hackathon will be a rewarding and enjoyable experience for all!

Good luck and happy coding!
