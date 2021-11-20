# Test Plan

## High Level Test Plan

| ID | Description | Expected I/P | Expected O/P | Actual O/P | Type of Test |
| ---- | --------------------- | ------------ | ---------- | ------------- | -------------|
| H_01 | User needs to enter the password | Enter Password | Succesfully Loged | Succesfully Logged | Requirement Based |
| H_02 | User can create ANY bank account to whom collaborate with this application. like Union,SBI,Indian Bank,BOI etc,.  | Select the Account which is user wants and enter their details like name,DOB, age,address, citizenship, phone number, amount to deposite and type of account through this application | Created Successfully | Created Successfully | Senario based |
| H_03 | User can do the transaction to any bank or UPI | Enter account no and amount to deposit or withdraw | Deposite/Withdraw Succesfully | Deposite/Withdraw Succesfully | Boundary Based |

## Low Level Test Plan

| ID | Description | Expected IN | Expected OUT | Actual Out | Type of Test |
| ---- | --------------------- | ------------ | ---------- | ------------- | -------------|
| L-01 | User can update existing account information based phone number, address, account no | Enter phone number | Changes saved succesfully | Changes saved successfully | Requirement based |
| L_02 | User can check the details of existing account by account no | Enter Account number |  Displayed details succesfully | Displayed details succesfully | Senario based |
| L_03 | User can remove existing account by entering their pin and password | Enter account no, passwor, Pin number | Account deleted succesfully | Account deleted succesfully | Boundary based |
