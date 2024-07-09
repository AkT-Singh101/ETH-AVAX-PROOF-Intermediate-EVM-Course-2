GOJO ERC20 Contract
=====================

This is a basic ERC20 token contract implemented in Solidity. It allows the contract owner to mint new tokens, and any user to burn and transfer tokens.

**Functions**

* `mint(address to, uint256 amount)`: Mints new tokens to a specified address. Only callable by the contract owner.
* `burn(uint256 amount)`: Burns a specified amount of tokens from the caller's balance.
* `transfer(address to, uint256 amount)`: Transfers a specified amount of tokens to another address.
* `balanceOf(address account)`: Returns the token balance of a specified address.

**Deployment**

To deploy this contract, compile and deploy it using Remix or your preferred Ethereum development environment.

**Interacting with the Contract**

Once deployed, you can interact with the contract using Remix or other Ethereum wallets. Make sure to replace `msg.sender` with the actual address of the contract owner when calling the `mint` function.

## Author 
ANKIT SINGH

