# tokenLaunchBot
This is a bot that snipes a token once liquidity has been provided


This code is for BSC testnet and uses

#Pancakeswap Factory & Router contracts from pcs testnet 

https://pancake.kiemtienonline360.com/

factoryTestnet = web3.toChecksumAddress('0xb7926c0430afb07aa7defde6da862ae0bde767bc')        

routerTestnet = web3.toChecksumAddress('0xD99D1c33F9fC3444f8101754aBC46c52416550D1')


1) Bot listens for a new pair that has been created
2) only when liquidity has been added it will purchase token


This bot works for all Dexes, nomatter if mainnet or testnet change addresses accordingly
