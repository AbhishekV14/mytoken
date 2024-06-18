Hi there, I'm Abhishek Chaudhary 
I am a student at Chandigarh University doing computer sciencety
This is a code of solidity in which we can burn and mint token in this i have created my own token which is known as "Abhishek" and it's abbreviation is "Abhi".
Mapping variable : 'balance' is a public mapping that associated address with unsigned integers.This mapping is used to keep track of the balance of tokens for each address.
Mint function : Mint is a public function that allow new tokens to be created and assigned to a specified address.
It takes two parameters-
1. "address"- the address to which the new token will be assigned.
2. "value"- the number of token to be created.
Burn function - It allow tokens to be destroyed from a specified address.
It also takes two parameters-
1. "address"- the address from which the tokens will be removed.
2. "value"- the number of token to be destroyed .
The function ensures that the address has enough tokens to burn.If not it throws an error with the message in sufficient balance to burn.The total supply is decreased by value.
In this code i can mint any amount of token a per my requirement and can also burn token according to my requirements its a very basic code which can easily  give  you understanding of how we can burn and mint token on solidity.
The balance of address in the balance mapping is decreased by value.
The code mantains a record of token balances for each address.It keeps track of the total supply of token in circulation.
