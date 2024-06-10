[MyToken]{.underline}

MyToken is a simple token contract written in Solidity. It provides a
basic implementation ,with the ability to mint and burn tokens.

Features

Token Name: COIN

Token Abbreviation: CIN

Total Supply: 0 initially

I declared a public mapping named balances, which maps addresses to
their token balances. Each address is associated with a uint value
representing the balance.

Mint Function

Increases the total supply and the balance of the specified address.

The mint function takes two parameters: an address add and a value val
increases the total supply by val and increases the balance of the add
address by val.

Burn Function

Decreases the total supply and the balance of the specified address.

The burn function takes two parameters: an address add and a value val.

It checks if the balance of the add address is greater than or equal to
val, and if so, it decreases the total supply by val and decreases the
balance of the add address by val.

How to Run

Deploy the contract using Remix or any other Solidity IDE.

Authors

Sujal Sachan sachansujal773@gmail.com
