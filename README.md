MyToken
This Solidity contract implements a basic token system with minting and burning functionality. It allows the creation and destruction of tokens, while keeping track of the total supply and individual balances.

Requirements
The contract has public variables to store information about the token, including its name, abbreviation, and total supply.
There is a mapping that associates addresses with their corresponding token balances.
The contract includes a mint function that increases the total supply by a specified value and adds that value to the balance of the "sender" address.
The contract includes a burn function that deducts tokens from the total supply and the balance of the "sender" address. This function should only execute if the balance of the "sender" is greater than or equal to the amount being burned.
Getting Started
To run this contract, you can use Remix, an online Solidity IDE. Follow the steps below to compile and deploy the contract:

Go to the Remix website at https://remix.ethereum.org/.
Create a new file in Remix by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., MyToken.sol).
Copy and paste the provided code into the file.
In the "Solidity Compiler" tab, ensure the "Compiler" option is set to version 0.8.18 or a compatible version.
Click on the "Compile MyToken.sol" button to compile the code.
Switch to the "Deploy & Run Transactions" tab.
Select the "MyToken" contract from the dropdown menu.
Click on the "Deploy" button to deploy the contract.
Once the contract is deployed, you can interact with it using the following functions:

mint: Allows the creation of new tokens by specifying the address and value to be minted.
burn: Enables the destruction of tokens by specifying the address and value to be burned.

Author
Metacrafter Febrare

License
This project is licensed under the MIT License - see the LICENSE.md file for details.
