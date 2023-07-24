# EntangleProtocol
TESTNET V2 GUIDE: WRITTEN

In the Entangle Testnet V2.1 the following functionalities are added:
Buy & Sell Liquid Vaults
Stake LP Tokens to obtain Liquid Vaults
Transfer Liquid Vaults across 7 EVM Chains
To setup yourself to test each functionality please follow this guide: A TL;DR Version is given first by a thorough guide explaining each single step.

TL;DR
Go to https://test.entangle.fi/ and register for Testnet
Obtain “Entangler Role” in Discord
Send wallet address to Entangle Bot to obtain Faucet Tokens
Add relevant Test-networks (see step 15.8)
Participate!
Requirements:
A Computer (PC, Laptop, Tablet, Mobile)
A Browser (for example Chrome, Brave or Opera).
A Web3 Wallet such as Metamask installed
Discord Account
Phone Number
Have one of the following Entangle Testnet-works added to your Metamask Wallet
Polygon
Fantom
Avalanche
BNB Smart Chain
Optimism
Arbitrum
Ethereum
To connect to any of these networks, please refer to the end of this guide for relevant details
Walkthrough:
Go to https://test.entangle.fi/

Click "Connect Wallet" and choose your preferred Web3 Wallet. This guide will be done with a Metamask wallet.

Click on "Metamask" if using a Metamask Web3 Wallet
If prompted, login to your Metamask Account
Click “Next”

Click "Connect”

If you do not have one of the networks stated in the requirements list, you will be shown this screen:

Select any of these networks and click “Switch Network” You will be prompted to switch to it inside the Metamask Wallet Extension

After successfully connecting your wallet. Go to https://test.entangle.fi/testnet-info Tap on “Get faucet tokens” then go to Discord and verify your account to obtain the Entangle Role. Follow steps in the discord testnet channel

This will open a new tab in your Browser and re-direct you to an invite link



*Note: If you do not already have a phone-number attached to your discord account, you will be prompted to verify your phone-number: Ignore 10.1-10.5 if you already have a phone number attached to your Discord Account. Entangle does not store your phone number and verification happens purely on the side of Discord in order to combat botting.
10.1. Click "Complete", read the rules and click "I have read and agree to the rules", and then click "Verify”

10.2. Input your phone-number and click "Send"

10.3. Proceed with completing the captcha

10.4. You will now receive a 6 digit code from Discord. Paste it, which will trigger Discord to request you to confirm your password

10.5. Click "Submit”

10.6 Click "Become Entangled!" You will now get a notification in the sub-channel by the "Entangle Bot" of "Added Role" of @Entangler 

10.7 Now proceed to #faucet-tokens sub-channel

10.8 Click "Verify", which will notify you to check the DM from Entangle Verification Bot. If current private settings prohibit you from receiving DMs, please disable these momentarily or look for the DM under "Message Requests”

10.9 You should see the DM pop up in the top left corner, as such:

10.10 Click on the DM and proceed to pasting your wallet address and send message.

Now you will need to connect to Entangle Test Networks. Entangle has created their own custom Test Networks, which will need a little bit of work to set-up.
11.1. Open the Metamask User Wallet Interface and click on the top right corner, displaying your personal wallet icon

11.2. Click on “Settings”

11.3. Now click on “Networks”

11.4. Now click “Add network”

11.5. You will now be redirected to your wallet interface in a new tab

11.6. Click “Add a network manually”

11.7. Fill in the details of the Entangle Testnets and click save.

11.8. You will now be able to access the Entangle V2 Testnet: To test the functionality on each of the integrated networks, please add them by filling out all relevant details below:
Network Name: ENT Ethereum Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/eth Chain ID: 1 Currency Symbol: ETH
Network Name: ENT BSC Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/bsc Chain ID: 56 Currency Symbol: BNB
Network Name: ENT Optimism Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/optimism Chain ID: 10 Currency Symbol: ETH
Network Name: ENT Avalanche Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/avalanche Chain ID: 43114 Currency Symbol: AVAX
Network Name: ENT Arbitrum Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/arbitrum Chain ID: 42161 Currency Symbol: ETH
Network Name: ENT Fantom Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/fantom Chain ID: 250 Currency Symbol: FTM
Network Name: ENT Polygon Testnet New RPC URL: https://nodes.test.entangle.fi/rpc/polygon Chain ID: 137 Currency Symbol: MATIC
***For further guide-lines in case of confusion, check out this article from MetaMask about adding networks manually: https://support.metamask.io/hc/en-us/articles/360043227612-How-to-add-a-custom-network-RPC***
11.9 If you are not already connected to a test-network, then select one:

Pending you have completed all forms and discord verification, you will have received test network tokens (in this example gas-token BNB) and USDC and LP Tokens.
If you do not see USDC in your wallet, go to settings inside your Metamask Wallet:
11.10. Click the “Security & Privacy” section, scroll down and turn on “Autodetect tokens”


Now go back to your wallet, and you should be able to see USDC!

11.11. If that does not work, click "Import tokens" under each chain and input the relevant contract adresses and click "add custom token". After you see the USDC Balance, click "Import tokens"


The contract addresses for USDC tokens are:
Ethereum: 0xA0b86991c6218b36c1d19D4a2e9Eb0cE3606eB48 
BSC: 0x8AC76a51cc950d9822D68b83fE1Ad97B32Cd580d 
Optimism: 0x7F5c764cBc14f9669B88837ca1490cCa17c31607 
Avalanche: 0xB97EF9Ef8734C71904D8002F8b6Bc66Dd9c48a6E 
Arbitrum: 0xFF970A61A04b1cA14834A43f5dE4533eBDDB5CC8 
Fantom: 0x04068DA6C83AFCFA0e13ba15A6696662335D5B75 
Polygon: 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174

The contract addresses for LP Tokens are:

Ethereum: 
Curve: FRAX/USDC LP Token: 0x845838DF265Dcd2c412A1Dc9e959c7d08537f8a2 
Curve: DAI/USDC LP Token: 0x3175Df0976dFA876431C2E9eE6Bc45b65d3473CC

BSC:
PancakeSwap: TUSD/BUSD LP Token: 0x7EFaEf62fDdCCa950418312c6C91Aef321375A00 
PancakeSwap: DAI/BUSD LP Token: 0x66FDB2eCCfB58cF098eaa419e5EfDe841368e489 
PancakeSwap: USDT/BUSD LP Token: 0x2E28b9B74D6d99D4697e913b82B41ef1CAC51c6C

Optimism:
Velodrome: USDC/sUSD LP Token: 0xd16232ad60188B68076a235c65d692090caba155

AVAX:
TraderJoe: USDC/USDC.e LP Token: 0x2A8A315e82F85D1f0658C5D66A452Bbdd9356783 
TraderJoe: USDT/USDT.e LP Token: 0x74B651Eff97871eA99fcc14423E611d85Eb0EA93

Arbitrum: 
Stargate: USDC LP Token: 0x892785f33CdeE22A30AEF750F285E18c18040c3e 
Stargate: USDT LP Token: 0xB6CfcF89a7B22988bfC96632aC2A9D6daB60d641

Fantom:
Stargate: USDC LP Token: 0x12edeA9cd262006cC3C4E77c90d2CD2DD4b1eb97 
Spookyswap; USDC/TUSD LP Token: 0x12692B3bf8dd9Aa1d2E721d1a79efD0C244d7d96 Spookyswap: USDC/MAI LP Token: 0x4dE9f0ED95de2461B6dB1660f908348c42893b1A

Matic(Polygon):
Stargate: USDC LP Token:0x1205f31718499dBf1fCa446663B532Ef87481fe1 
Stargate: USDT LP Token: 0x29e38769f23701A2e4A8Ef0492e19dA4604Be62c




The contract addresses for Liquid Vaults are:

Ethereum
Ticker: sCVFU
Underlying LP Token: FRAX/USDC on Curve  
Liquid Vault Token Address: 0x5946d354392782744bC8d679ad4002FBE62C181E


BSC:
Ticker: sPSDB
Underlying LP Token: DAI-BUSD on PancakeSwap
Liquid Vault Token Address: 0xdD6D08E3c1Cb741d71b2c3d3AfD893887bDb5B9C

Ticker: sPSTB
Underlying LP Token: TUSD-BUSD on PancakeSwap
Liquid Vault Token Address: 0x9921449ebCe265FF076C5da470e7aF367F720e7C

Ticker: sPSUB
Underlying LP Token: USDT-BUSD on PancakeSwap
Liquid Vault Token Address: 0xb8E3D62a3d80426620315f128cEA16a00B437852


Optimism: 

Ticker: sVDUC
Underlying LP Token: USDC-sUSDC on Velodrome
Liquid Vault Token Address: 0x1E5233c5822699F6E920F0ec2128EE62222cAa3b


AVAX:

Ticker: sTJUC
Underlying LP Token: USDC-USDC.e on TraderJoe
Liquid Vault Token Address: 0xEe6c744De56DcEc26d12484727FF9E5F3eCb680C

Ticker: sTJUT
Underlying LP Token: USDT-USDT.e on TraderJoe
Liquid Vault Token Address: 0x77230CfBaD940F74402D3268C4185e6F9b62B314


Arbitrum:

Ticker: sSGUC
Underlying LP Token: USDC on Stargate
Liquid Vault Token Address: 0xD08dE86f934a774bC6771AADB764E801fC8518ec

Ticker: sSGUT
Underlying LP Token: USDT on Stargate
Liquid Vault Token Address: 0x5D6617411f3E0e0E50bFfc2cF2F38ED1345463a0


Fantom:

Ticker: sSSUT
Underlying LP Token:  USDC/TUSD on SpookySwap
Liquid Vault Token Address: 0x2A68e9BF51E0FED5e62eB050D8fcf32B6a298279


Ticker: sSGUC
Underlying LP Token: USDC on Stargate
Liquid Vault Token Address: 0x95833C35bCEF414EB210185826ce56F6C5C2A914


Matic(Polygon):


Ticker: sSGUC
Underlying LP Token: USDC on Stargate
Liquid Vault Token Address: 0xDD83216467EFb674DC47d8C411462dABcA554c30

Ticker: sSGUT
Underlying LP Token: USDT on Stargate
Liquid Vault Token Address: 0xa83438fd9C5c00104993C3B97883fD63E906a9e3
