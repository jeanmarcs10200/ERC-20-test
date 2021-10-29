# ERC20 
## Code
This is a test to deploy an ERC20 token.

The name of the token is CoinFiance
The simbol is BCS

```sh
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.2;

import "@openzeppelin/contracts@4.3.2/token/ERC20/ERC20.sol";

contract CoinFiance is ERC20 {
    constructor() ERC20("CoinFiance", "BCS") {
        _mint(msg.sender, 500000 * 10 ** decimals());
    }
}
```

## Compilation and Deployment
TO DO: Deploy on test net
