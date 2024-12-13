# EXPchainContractDeploy

Aşağıdaki siteye girelim 👇
https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.26+commit.8a97fa7a.js

Adım 1:
![remix1](https://github.com/user-attachments/assets/40f9f55b-430b-49ab-a2a0-3c30ba7afe65)

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

Adım 2: 
![remix2](https://github.com/user-attachments/assets/9b4fb46f-e654-4b2e-8cbb-b22762f63802)
Adım 3: 
![remix4](https://github.com/user-attachments/assets/0425d45c-66aa-47b7-aa95-a374e50e11b5)

