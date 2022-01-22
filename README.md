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

# NOTE: The standard token has all basic functions of the standard token protocol.

## Accessible Functions of the BUY Back

### 1. getBuyBackBalance

This function returns the balance in the buyback wallet

### 2. getHoldersBalance

This functin returns the holders balance

### 3. getDevelopersBalance

This function returns the developers balance

4.
