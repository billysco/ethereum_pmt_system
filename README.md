# ethereum_pmt_system
This project aims to create a fully functional system that customers can use to hire and pay (using Ethereum) temporary employees from a list of candidates. A screenshot of the finished product is attached below:
![Main_page](https://github.com/billysco/ethereum_pmt_system/blob/main/Screenshots/main_page.PNG)

## Usage
To utilize this application, the user needs to provide their mnemonic seed phrase in a .env file. Once the program is run, the user is shown their account address and current balance (in Ether) in the top left. Then, they are given the option to select a canditate from the list displayed on the right side. Once a candidate is selected and number of hours are entered, the total wage in Ethereum is displayed and the user has the opportunity to send the funds. A test transaction (on the Kovan test network) is displayed below:
![transaction_history](https://github.com/billysco/ethereum_pmt_system/blob/main/Screenshots/transaction_details.PNG)
![transaction_confirmation](https://github.com/billysco/ethereum_pmt_system/blob/main/Screenshots/tansaction_verification.PNG)
![recipient_account](https://github.com/billysco/ethereum_pmt_system/blob/main/Screenshots/recipient_history.PNG)

## Technologies
The program is written in Python and uses the following libraries: web3, bip44, dataclasses, typing, streamlit, os, requests, and dotenv. 

## Contributor
William Scolinos | billyscolinos1@gmail.com
