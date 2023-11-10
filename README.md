# Collateral and Insurance Protocol Contract


## Table of Content

- [Collateral and Insurance Protocol Contract](#collateral-and-insurance-protocol-contract)
  - [Table of Content](#table-of-content)
  - [Introduction](#introduction)
  - [Description](#description)
  - [Deployment and Verification of the Contracts on Sepolia testnet](#deployment-and-verification-of-the-contracts-on-sepolia-testnet)
  

## Introduction
This is Solidity-based smart contracts in this project. The contracts enable users to purchase insurance and collateral for crypto-backed loans.

## Description

The project includes a factory contract model, which allows users to create either insurance contracts or collateral protection contracts. The factory contract can deploy instances of either a child contract based on user preference.

The insurance contract allows users to pay their premiums either monthly or annually. The collateral management contract, on the other hand, monitors the value of the user's collateral. If the collateral value drops below 20, the contract liquidates the collateral. Users can also repay their loans to retrieve their collateral.

## Deployment and Verification of the Contracts on Sepolia testnet

![Alt text](images/02.png)

![Alt text](images/11.png)

![Alt text](images/03.png)

![Alt text](images/last.png)