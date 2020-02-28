## Sūrya's Description Report

### Files Description Table


|  File Name  |  SHA-1 Hash  |
|-------------|--------------|
| BTCCToken.sol | 54e714c34ca96b6675e5d7ebeca89e112e68a22f |


### Contracts Description Table


|  Contract  |         Type        |       Bases      |                  |                 |
|:----------:|:-------------------:|:----------------:|:----------------:|:---------------:|
|     └      |  **Function Name**  |  **Visibility**  |  **Mutability**  |  **Modifiers**  |
||||||
| **SafeMath** | Implementation |  |||
| └ | safeAdd | Internal 🔒 |   | |
| └ | safeSub | Internal 🔒 |   | |
||||||
| **ERC20Interface** | Implementation |  |||
| └ | totalSupply | Public ❗️ |   |NO❗️ |
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | allowance | Public ❗️ |   |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
| └ | approve | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
||||||
| **ApproveAndCallFallBack** | Implementation |  |||
| └ | receiveApproval | Public ❗️ | 🛑  |NO❗️ |
||||||
| **Owned** | Implementation |  |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | transferOwnership | Public ❗️ | 🛑  | onlyOwner |
| └ | acceptOwnership | Public ❗️ | 🛑  |NO❗️ |
||||||
| **BTCCToken** | Implementation | ERC20Interface, Owned, SafeMath |||
| └ | \<Constructor\> | Public ❗️ | 🛑  | |
| └ | distributeTokens | Public ❗️ | 🛑  | onlyOwner |
| └ | distributedTokenCount | Public ❗️ |   | onlyOwner |
| └ | totalSupply | Public ❗️ |   |NO❗️ |
| └ | balanceOf | Public ❗️ |   |NO❗️ |
| └ | transfer | Public ❗️ | 🛑  |NO❗️ |
| └ | approve | Public ❗️ | 🛑  |NO❗️ |
| └ | transferFrom | Public ❗️ | 🛑  |NO❗️ |
| └ | mintToken | Public ❗️ | 🛑  | onlyOwner |
| └ | freezeAccount | Public ❗️ | 🛑  | onlyOwner |
| └ | burn | Public ❗️ | 🛑  |NO❗️ |
| └ | burnFrom | Public ❗️ | 🛑  |NO❗️ |
| └ | allowance | Public ❗️ |   |NO❗️ |
| └ | \<Fallback\> | Public ❗️ |  💵 |NO❗️ |
| └ | transferAnyERC20Token | Public ❗️ | 🛑  | onlyOwner |
| └ | destroyContract | Public ❗️ | 🛑  | onlyOwner |


### Legend

|  Symbol  |  Meaning  |
|:--------:|-----------|
|    🛑    | Function can modify state |
|    💵    | Function is payable |
