# Unit 21: You sure can attract a crowd!
# Background 

Your company has decided to crowdsale their PupperCoin token in order to help fund the network development. This network will be used to track dog breeding activity across the globe in a decentralized way, and allow humans to track the genetic trail of their pets. You have already worked with the necessary legal bodies and obtained the green light on creating a crowdsale open to the public. However, you are required to enable refunds if the crowdsale is successful and the goal is met, and you are only allowed to raise a maximum of 300 ether. The crowdsale will run for 24 weeks.

You will need to create an ERC20 token that will be minted through a Crowdsale contract that you can leverage from the OpenZeppelin Solidity library.

This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin). This contract will mint the tokens automatically and distribute them to buyers in one transaction.

It will need to inherit Crowdsale, CappedCrowdsale, TimedCrowdsale, RefundableCrowdsale, and MintedCrowdsale.

You will conduct the crowdsale on the Kovan or Ropsten testnet in order to get a real-world pre-production test in.
## ![headline_photo](Images/Crowd.jpg)

Run PupperCoin.sol

## ![headline_photo](Images/Pic1.jpg)
Transaction - block success
## ![headline_photo](Images/Pic2.jpg)

Process 1: Bootstrap the contract, providing a parameters for all features of crowdsale, and compile.

## ![headline_photo](Images/Pic3.jpg)

Process 2: Launch crowdsale
## ![headline_photo](Images/Pic3.jpg)