# decentralized-leading.sol
# Decentralized Lending Platform

## Project Description

The **Decentralized Lending Platform** is a smart contract designed to facilitate peer-to-peer lending on the Ethereum blockchain. This platform allows users to lend and borrow funds in a decentralized manner. Lenders can create loans for borrowers, and borrowers can repay their loans within a specified duration, including an interest fee.

The contract ensures that all transactions, including the creation and repayment of loans, are handled transparently and securely. By utilizing the Ethereum blockchain, the platform removes intermediaries and provides trustless financial services.

---

## Table of Contents

1. [Features](#features)
2. [Contract Address](#contract-address)
3. [How to Use](#how-to-use)
4. [Installation & Deployment](#installation--deployment)
5. [License](#license)
6. [Contributing](#contributing)

---

## Features

1. **Create a Loan:**
   - Lenders can create loans by specifying the borrower’s address, loan amount, interest rate, and the loan duration in days.
   - The contract calculates the repayment date based on the loan duration.

2. **Repay a Loan:**
   - Borrowers can repay their loans with the required interest before the repayment deadline.
   - The total repayment amount includes the principal and interest (calculated as a percentage of the loan amount).
   
3. **Loan Details:**
   - Anyone can view the loan details by loan ID, including lender, borrower, loan amount, interest rate, duration, repayment date, and whether the loan has been repaid.

4. **Loan Events:**
   - **LoanCreated**: Notifies when a new loan is created, with relevant details.
   - **LoanRepaid**: Notifies when a loan has been successfully repaid.

5. **Security:**
   - Only the borrower can repay the loan.
   - Repayments are restricted by the loan’s repayment date to ensure timely payments.

6. **Transparency:**
   - Loan data is accessible to everyone, promoting transparency in the borrowing and lending process.

---

## Contract Address

The contract address is the Ethereum address where the **Decentralized Lending Platform** smart contract is deployed. The contract address will be provided once the contract is deployed on an Ethereum network (e.g., Rinkeby, Ethereum mainnet).

- **Contract Address**: `0xYourContractAddressHere`

(Note: Replace with the actual contract address once deployed.)

---

## How to Use

1. **Deploy the Contract**: 
   - Deploy the smart contract to the Ethereum network using Remix, Hardhat, or Truffle.

2. **Interact with the Contract**:
   - **Creating a Loan**: Lenders can call the `createLoan` function, specifying the borrower, loan amount, interest rate, and loan duration.
   - **Repaying a Loan**: Borrowers can call the `repayLoan` function and send the correct amount of Ether (principal + interest) to repay the loan.
   - **Getting Loan Details**: Anyone can call the `getLoanDetails` function to view the loan status and terms.

---

## Installation & Deployment

1. Install **MetaMask** or any Ethereum-compatible wallet.
2. Connect to a **test network** (e.g., Rinkeby) or the **Ethereum mainnet**.
3. Deploy the smart contract using Remix, Truffle, or Hardhat.
4. After deployment, you can interact with the contract via the deployed contract address using your wallet.

---

## License

This project is licensed under the **MIT License**. You can freely use, modify, and distribute it.

---

## Contributing

Feel free to fork, improve, and submit pull requests. Contributions are welcome! Please follow standard practices for pull requests, including providing a description of the changes and any related issues.

---

For more details on deploying and interacting with this contract, please refer to the [Ethereum documentation](https://ethereum.org/en/developers/docs/) and [Remix IDE](https://remix.ethereum.org/).
