# Swirl 

Swirl is a platform for derivative contracts, which allows the creation of assets
synthetics such as bonds, stablecoins, stocks, bitcoin-backend.

## How to create a new asset?
Synthetics are created when an amount of bitcoins is added to a contract for a synthetic such as the US Dollar, the amount of the
tokens is defined using this formula: $$p * (r / m)$$

(p) is the price of the asset at the current moment (r) is the amount of bitcoins (m) is the guarantee reserved to keep the peg, 
in our case we use (2.5) or (150%) as collateral.

## How to redeem my bitcoins?
The guarantees can be redeemed when the borrower or the current owner of the tokens burns them, the borrower has the right to redeem 150% of the guarantees, while the non-borrower can only redeem 100% of the value in bitcoin referring to the token.

## Is this safe what are the tradeoffs?
To be honest, synthetic assets have several weaknesses, such as price oracle, collateral custody, collateral asset volatility, which can result in forced liquidation of the asset. On the other hand, these instruments can serve well, in several specific scenarios, collateralized loans without interest payments, international remittances with stable currency, exposure to shares and other assets, the creation of a service that does not depend on banks to function, interoperability since the escrow token is bitcoin.
