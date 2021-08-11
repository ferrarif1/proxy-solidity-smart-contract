# Upgradeable smart contrat with proxy - Solidity

Even though smart contracts cannot be changed once deployed to the blockchain, there is a method to develop upgradeable contracts. Ethereum provides a function named DelegateCall, which allows a contract to use code in other contracts, and all storage changes are made in the caller’s value. In this case, developers can develop two contracts, A and B. A is the proxy contract, which controls all the storage values, contract states, and Ethers. All the logic code is stored in contract B

