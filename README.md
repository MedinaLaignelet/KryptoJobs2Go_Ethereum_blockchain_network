# KryptoJobs2Go_Ethereum_blockchain_network

# Objective:#

Integrating and Ethereum blockchain network into the KryptoJobs2Go application using python coding and Streamlit library for its web interface.  The application would allow customers to pay for fictitious fintech professionals with Ethereum.

The python coding needed for this project can be found in the following files: krypto_jobs.py and crypto_wallet.py
The code Imports  the generate_account, get_balance, and send_transaction functions from the crypto_wallet.py file into the krypto_jobs.py file to automate the process of access them into the into the KryptoJobs2Go application At the same time, the personal mnemonic seed phrase from Ganache was added to the .env file to be used for validating the transactions created.

The code than creates a Streamlit sidebar calling the generate_account function to display the prospective client’s Ethereum account balance form the Ethereum account address.  The code also calculates the wages that will be paid to the Fintech professionals based on their hourly Ethereum rate and the number of hours that the individual is hired for. The code then allows a customer (me) to send an Ethereum blockchain transaction that pays the hired Fintech professional.

The application was tested by creating transactions where after selecting a Fintech professional and the hours needed, the application would display the total wages due. Once the transaction is submitted, a transaction_hash function will display in the web interface and the client’s new Ethereum account balance will display.

##Inspect the transaction in Ganache##

Finally, assuming the role of a customer using the application, please find the  screenshots to confirm the code successfully created an Ethereum transaction, with the gas estimate and paid a KryptoJobs2Go candidate for their work. 

The following screeshots show the Streamlit Application, creating a transaction and the transaction validation. From Ganache, you may see also the account balance before and after the transaction, the transactions details and the ganache blocks screen. 

<img src="/Images/streamlitapp.png">
<img src="/Images/transaction.png">
<img src="/Images/transactionvalidation.png">

<img src="/Images/ganacheacctbalance.png">
<img src="/Images/ganachebalaftertransaction .png">
<img src="/Images/ganachetransactionsdetails.png">
<img src="/Images/ganacheblocks.png">

###Resources###
UC Berkely Fintech Bootcamp class materials
UC Berkely Fintech Bootcamp Tutoring session 5/1/24

