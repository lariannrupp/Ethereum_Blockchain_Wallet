# Ethereum_Blockchain_Wallet

---

The purpose of this project is to create a streamlit application called "Fintech Finder" which demonstrates the framework for a cryptocurrency payroll system. The user can select an employee, input their hours, and pay them instantly in Ethereum.

---

## Technologies

![python-logo-master-v3-TM-flattened](https://user-images.githubusercontent.com/95719899/172075328-3d283af5-369f-4dd6-aa2d-51842e496428.png)
![streamlit_logo](https://user-images.githubusercontent.com/95719899/172075334-918934ce-691a-4e98-b2ac-aa06fe4377de.png)
![1_6Cbo1WZ499BM4b8Q7Ziyug](https://user-images.githubusercontent.com/95719899/172075389-35909bb3-aeba-45f6-89af-48a798b18894.png)

A Python 3 (ipykernal) in Visual Studio was used to write this application. Additional Python libraries are imported into the start of the app:

fintech_finder.py:

![Screenshot 2022-06-05 174311](https://user-images.githubusercontent.com/95719899/172075470-a16da648-3649-4a72-9d6c-dc9164d62dbe.jpg)

crypto_wallet.py:

![Screenshot 2022-06-05 174448](https://user-images.githubusercontent.com/95719899/172075533-9b6b5d66-ecaf-48ed-ad4c-97b131b54603.jpg)

---

## Installation Guide:
If you do not already have the required technologies installed, install them now through your terminal or Gitbash. 
For example:

> pip install streamlit
> pip install web3==5.17
> pip install bip44
> pip install dataclasses

If you do not already have Ganache, download and install the lastest version of Ganache. To create a workspace, click on "Quickstart Ethereum".

To run it from local computer, clone repo. From the Terminal, activate conda envirnoment; change directory to repo folder, and type streamlit run pychain.py. This will launch a web browser with a local URL such as http://localhost:8501. Note that you will need to install some libraries/dependencies if you do not already have them.

---

## Usage
To use this application,

1. From your terminal, navigate to the project folder that contains your `.env` file and the `fintech_finder.py` and `crypto_wallet.py` files.

2. To launch the Streamlit application, type `streamlit run fintech_finder.py` in terminal or Gitbash. 

3. On the resulting webpage, select a candidate that you would like to hire from the appropriate drop-down menu. Then, enter the number of hours that you would like to hire them for.

4 Click the Send Transaction button to sign and send the transaction with your Ethereum account information. If the transaction is successfully communicated to Ganache, validated, and added to a block, a resulting transaction hash code will be written to the Streamlit application sidebar.

5. Navigate to the Ganache accounts tab and locate your account (index 0).

6. Navigate to the Ganache transactions tab and locate the transaction.

---

## Streamlit App Overview

Launch page:

![Screenshot 2022-06-05 172911](https://user-images.githubusercontent.com/95719899/172075806-46ac891f-3cbd-4cf6-b4ab-10c29728000b.jpg)


Ganache Account:

![Screenshot 2022-06-05 175321](https://user-images.githubusercontent.com/95719899/172075829-34f427fd-ff2d-4809-835c-b3bcd3e31ba2.jpg)

Ganache Transaction:

![Screenshot 2022-06-05 172953](https://user-images.githubusercontent.com/95719899/172075834-9bd5c2f9-fb3f-4529-a4a8-3f80591d175e.jpg)

---

## Contributors

## Contributors

Thank you to UC Berekely and Trilogy Education 2022 for the data and reference code.

For any questions, please reach out to me on [LinkedIn](https://www.linkedin.com/in/lari-rupp-5baa49153/)

---

## License

Creative Commons Zero


