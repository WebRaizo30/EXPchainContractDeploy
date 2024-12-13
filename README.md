# EXPchainContractDeploy

# Aşağıdaki siteye girelim 👇
https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.26+commit.8a97fa7a.js

# Adım 1:
![remix1](https://github.com/user-attachments/assets/40f9f55b-430b-49ab-a2a0-3c30ba7afe65)

Aşağıdaki kodu yapıştıracaksınız👇

```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(uint256 initialSupply) ERC20("MyToken", "MTK") {
        _mint(msg.sender, initialSupply * (10 ** decimals()));
    }
}
```

# Adım 2: 
![remix2](https://github.com/user-attachments/assets/9b4fb46f-e654-4b2e-8cbb-b22762f63802)


# Adım 3: 
![remix4](https://github.com/user-attachments/assets/a7e50253-4ed7-4932-8309-458e279c81ac)


