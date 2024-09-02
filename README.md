# Money Bank App

## Overview

This Money Bank App is a simple web application built using JavaScript. It allows users to log in, transfer money between accounts, request loans, and close their accounts. The app also features an automatic logout system that activates after 5 minutes of inactivity.

## Live Demo

Check out the [Live Demo](https://money-bank-rs.netlify.app/) of the app to see it in action!

## Features

- **Login System**: Users need a valid username and password to access their account.
- **Money Transfer**: Users can transfer money to other accounts.
- **Loan Request**: Users can request a loan, subject to specific conditions.
- **Account Closure**: Users can close their accounts, removing all associated data.
- **Automatic Logout**: The app automatically logs the user out after 5 minutes of inactivity.

## Accounts

The following accounts are available in the app:

- **Account 1**
  - Owner: Vasantha Kumar
  - Username: `vk`
  - Password: `1111`

- **Account 2**
  - Owner: Tony Stark
  - Username: `ts`
  - Password: `2222`

- **Account 3**
  - Owner: Peter Parker
  - Username: `pp`
  - Password: `3333`

- **Account 4**
  - Owner: Steve Rogers
  - Username: `sr`
  - Password: `4444`

## Usage

### Login
To log in, users must enter their valid username and password. Without these credentials, access to the account is not possible.

### Money Transfer
Once logged in, users can transfer money to other accounts by specifying the recipient's account and the amount. After transferring the amount, users can log into the recipient's account to see the effect of the transfer.

### Loan Request
Users can request a loan. The loan will be approved if the user has a deposit greater than or equal to 10% of the loan request.

### Account Closure
If needed, users can close their account, which will delete all data associated with it. This action is irreversible.

### Automatic Logout
A 5-minute inactivity timer is implemented. If the user doesn't interact with the app within this time, they will be automatically logged out.

## Flowchart

Refer to the flowchart below for a visual representation of the application's logic:

![Bankist-flowchart](https://github.com/user-attachments/assets/edab64bc-4d95-4833-9cee-f5255aa98286)


## Screenshots

![1](https://github.com/user-attachments/assets/5f1b3310-18c9-46f4-b364-3214fd8bc819)
![2](https://github.com/user-attachments/assets/bbd69022-12ca-49b9-b43a-961518294d7d)
![3](https://github.com/user-attachments/assets/74a04395-6b1d-40f2-bb96-1b127b86d413)


