# PuppyRaffle Audit Report

## Overview

The PuppyRaffle Audit Report provides a comprehensive security review of the PuppyRaffle smart contract, highlighting the protocol's purpose, identified vulnerabilities, and their respective risk classifications. The audit aims to ensure the security, reliability, and overall integrity of the PuppyRaffle protocol. Conducted by Viktor Yordanov on August 21, 2024, this report offers insights into the findings, their potential impacts, and recommended mitigations to secure the contract.

## Protocol Summary

The PuppyRaffle protocol enables users to enter a raffle to win a unique dog-themed NFT. The protocol incorporates essential functionalities, such as:

- Allowing participants to enter the raffle by providing their addresses.
- Ensuring that duplicate entries are not allowed.
- Enabling participants to receive a refund of their ticket value if required.
- Drawing a random winner and minting a random puppy NFT every defined interval.
- Charging a fee, which is sent to a specified fee address, while the remaining funds are allocated to the winner.

## Disclaimer

The security audit was time-boxed and focused solely on the Solidity implementation of the contracts. While every effort was made to identify vulnerabilities, the audit does not serve as an endorsement of the underlying business model or product.

## Risk Classification

The audit leverages the CodeHawks severity matrix to categorize the identified issues based on their **Impact** and **Likelihood**, with classifications ranging from **High** to **Low** severity.

## Audit Details

- **Commit Hash**: e30d199697bbc822b646d76533b66b7d529b8ef5
- **Scope**: The scope of the audit included the **PuppyRaffle.sol** contract located in the project's source directory.
- **Roles**:
  - **Owner**: The deployer of the protocol with the authority to change the fee address.
  - **Player**: A participant who can enter the raffle and request refunds.

## Executive Summary

The audit identified **15 issues** classified as **High**, **Medium**, **Low**, and **Informational/Non-Critical** based on their severity. The key findings are summarized in the report, highlighting critical vulnerabilities and areas for gas optimizations.

- **High**: 3 issues
- **Medium**: 2 issues
- **Low**: 1 issue
- **Informational/Non-Critical**: 7 issues
- **Gas Optimizations**: 2 issues

## Conclusion

The PuppyRaffle Audit Report serves as a crucial reference for enhancing the security and efficiency of the PuppyRaffle protocol. By addressing the identified issues, the development team can significantly improve the reliability and trustworthiness of their decentralized raffle platform.
