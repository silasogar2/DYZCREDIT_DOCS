# DYZCREDIT_DOCS

## Project requirement

Each transaction = 13%

6% buy back wallet(BNB)
5% developer / Marketing( Busd)
2% to holders ( in Dyzcredits)

Here is how the buyback wallet must operate.

The buyback wallet will be a part of the smart contract, so the bnb can only be used to buy dyzcredit tokens.

The buyback function is automated and dynamic, meaning when it’s activated it will buy back tokens when someone is selling. So basically sells will pump the price or sustain it to keep the price floor, the settings can be set to different levels.

Example
if someone sells 0,2 bnb the buyback wallet will automatically buyback 0,3 bnb of dyzcredit tokens and will burn them immediately, which make this token very hyper deflationary and gives more value to the tokens you hold due to the burn.

The setting can also be higher and buying back 1 bnb eg, if someone sells 0,2 bnb, it will pump the price and burn the amount it bought back. Sellers will be punished in other words.

The buy back wallet only activates at a setting holder level. In this case we will set it to 3000 holders. Once we hit 3k holders it will start to function.

## Smart contracts

There are two smart contracts here:

1. he standard BEP20 TOken
2. The Buy back smart contract

## Token Addresses

1. Token: 0xB23460393532899E929913e0c6Cbe3BD6a6d6f41

2. Buy Back: 0xE545208F65CE78d5Ae876b52c5f1D2f9251A3847

## Repositories

https://github.com/silasogar2/dyzrupt_contracts

## NOTE: The token has all basic functions of the standard token protocol.

## Accessible Functions of the BUY Back

### 1. getBuyBackBalance

This function returns the balance in the buyback wallet

### 2. getHoldersBalance

This functin returns the holders balance

### 3. getDevelopersBalance

This function returns the developers balance

### 4. setAccountPercentages

This function is used to adjust account settings, accessible by only the contract owner/admin

It requires the followiing parameters:

1. BuyBack percentage (Overall i.e 13% reflected above)
2. holders Percentage,
3. developers Percentage,
4. BuyBack Wallet Percent

### 5. getPercentages

This function returns the data above from accounts settings:

1. BuyBack percentage (Overall i.e 13% reflected above)
2. holders Percentage,
3. developers Percentage,
4. BuyBack Wallet Percent

### 6. buyDyzcredit

A non Reentrant function that allows the procurement of the DyzeCredit token in BNB

### 7. sellDyzCredit

A non Reentrant function that allows the sales of the DyzeCredit token

### 8. getNumberOfholders

This function returns the number of dyzcredit tokens

### 9. getWalletStatus

This function returns the status of the buy back wallet
