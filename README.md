# crypto-herdcoin
Here is my code for the Ethereum Remix IDE.  This project is coded in Solidity and is essentially copy paste if you are trying to replicate my coin.  I set a coin cap of 100,000  but you can change that as you like,  As well as the default decimal value for my code is 0.  The "standard" decimal value for most modern cryptos is 18.  Since this is a ERC-20 token any number 0-18 will be plenty sufficient but make sure you match the total circulation along with your decimal value.

This is a ERC-20 "token" on the eth network.  I programmed mine on the Ropsten test network since i do nto have to pay real money for it to exist but this should work for the main ETH network.  

I used metamask as my wallet.  simply create metamask accoiunt and test your ropsten wallet using a faucet.  [https://faucet.ropsten.be/](url) is the only faucet i found to work.  
Once you know your wallet adderess works you can paste my ERC-20 token code into the Ethereum Remix IDE.  Make sure you change the symbol, name, decimals, and total supply accordingly.  respectfully lines 62, 63, 64, 65.

Compile the smart contract and deploy using injected web3 on the Ropsten test network.  This should cause a popup from metamask extension and simply pay the gas fee with the ETH from the faucet.  

Deploy the token contract by selecting the name of the contract in the contracts section.  

Finally, copy the deployed contracts address and go into metamask to add a token.  Once here add the token button and since your wallet should be linked to the smart contract you will be the only owner.

Feel free to send to friends just make sure they import the token.  Will be adding more to this token in the future.  Maybe binance coin next or solana coin.
