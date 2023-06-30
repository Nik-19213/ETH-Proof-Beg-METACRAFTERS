# Crypto Token Smart Contract

In this project i have created a Smart Contract to generate a Crypto token whose supply will be given by the user.
It has three public variables that stores the details about our coin (Token Name, Token Abbrv., Total Supply).
It has a mapping of addresses to balances (address => uint).
It has a mint function that takes two parameters: an address and a value, 
the function then increases the total supply by that number and increases the balance of the “sender” address by that amount.
It has a burn function, which works the opposite of the mint function, It will deduct the value from the total supply and from the balance of the “sender”.
Burn function also have condition to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.
