# Introduction to Smart Contract 
#### The short description about ERC721, ERC721A and ERC1155 Contracts
#### *More details about contracts can be found in folders with contract names*
*Compiler Version* - *v0.8.1*
*ERC Version* - *1155*,
*ERC Version* - *721*,
*ERC Version* - *721A*


## About The Standard ERC721

The ERC-721 introduces a standard for NFT, in other words, this type of Token is unique and can have different value than another Token from the same Smart Contract, maybe due to its age, rarity or even something else like its visual. Wait, visual?

Yes! All NFTs have a uint256 variable called tokenId, so for any ERC-721 Contract, the pair contract address, uint256 tokenId must be globally unique. That said, a dApp can have a "converter" that uses the tokenId as input and outputs an image of something cool, like zombies, weapons, skills or amazing kitties!



## About The Standard ERC721A

The goal of ERC721A is to provide a fully compliant implementation of IERC721 with significant gas savings for minting multiple NFTs in a single transaction. This project and implementation will be updated regularly and will continue to stay up to date with best practices.

![Gas Savings](https://pbs.twimg.com/media/FIdILKpVQAEQ_5U?format=jpg&name=medium)

## About The Standard ERC1155

A standard interface for contracts that manage multiple token types. A single deployed contract may include any combination of fungible tokens, non-fungible tokens or other configurations (e.g. semi-fungible tokens).

What is meant by Multi-Token Standard?

The idea is simple and seeks to create a smart contract interface that can represent and control any number of fungible and non-fungible token types. In this way, the ERC-1155 token can do the same functions as an ERC-20 and ERC-721 token, and even both at the same time. And best of all, improving the functionality of both standards, making it more efficient, and correcting obvious implementation errors on the ERC-20 and ERC-721 standards.