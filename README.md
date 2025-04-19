# BlockBase DApp Submission 🚀

## 👤 Developer
**Name:** Jainil  
**Wallet Address:** 0xd2721d640aAaFeE4FDd6BD41e642A0FD2Bbc5C2d

## ✅ Features Implemented

### Solidity Feature:
- **Get your own name** – Added a function `getMyName()` in the smart contract to fetch the name associated with the wallet.

### JavaScript Feature:
- **Display connected wallet address** – Shows the wallet address of the currently connected MetaMask user.

## 🛠️ Code Changes


### Solidity Code:
```solidity
function getMyName() public view returns (string memory) {
    return people[msg.sender].name;
}
