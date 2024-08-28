
## DegenToken Smart Contract

### Overview

This is a Solidity smart contract named `DegenToken` that implements an ERC20 token called "Degen". It provides functionalities for minting, burning, ordering ChickenJoy, ordering JollyHotdog, checking user orders, and transferring tokens. The contract defines constant prices for ChickenJoy and JollyHotdog.


### Contract Details

- **Name:** DegenToken
- **Version:** 1.0.0
- **Solidity Version:** ^0.8.18
- **License:** MIT

### Constants

- `CHICKENJOY_PRICE`: The price of ordering ChickenJoy.
- `JOLLYHOTDOG_PRICE`: The price of ordering JollyHotdog.

### Functions

- `mint(address to, uint256 amount)`: Allows the owner to mint tokens.
- `burn(uint256 amount)`: Allows token holders to burn their tokens.
- `orderChickenJoy()`: Allows users to order ChickenJoy.
- `orderJollyHotdog()`: Allows users to order JollyHotdog.
- `getUserOrder(address user)`: Retrieves the total order amount for the specified user.
- `transfer(address to, uint256 amount)`: Allows token holders to transfer tokens.

