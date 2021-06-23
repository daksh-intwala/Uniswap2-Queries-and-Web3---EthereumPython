***Instructions for Manipulating_Data_Uniswap.ipynb File***
------------------------------------------------------------
#Libraries Needed for Manipulating_Data_Uniswap.ipynb file:
1. requests
2. json
3. pprint 

# For flexibiliy: create environment
    open cmd
       > cd <my_vebev_path>
       > python -m venv newenv
       > .\newenv\Scripts\activate

#Installation Procedure (only if you don't have these libraries already installed)
--> Install through bash terminal
    1. pip install requests
    2. pip install json
    3. pip install pprint

# Run the code now in your jupyter terminal, and you are good to go.
** Advice: Use Jupyter in VScode for easy editing, github communications.

-------------x----------------------x--------------------x-----------------------------

***Instructions for Reading_Info_Contract_Ethereum.ipynb File***
------------------------------------------------------------------
#Libraries Needed for Reading_Info_Contract_Ethereum.ipynb file:
1. json
2. web3

#Installation Procedure (only if you don't have these libraries already installed)
1. pip install json
2. pip install web3
    ( In case of error: failed Iru-dict, failed setup.py, etc, Follow this:
        Install Visual C++ build tools 2019 package from the link in the error and restart the system.)

# Infura_url:
  the url is taken from my acc and should not work when I delete it.
  It is advisable to singup at Infura > create new proj > settings > EndPoint > *copy http:// url from here * and replace it with Infura_url

# address of contract is taken from :
    https://etherscan.io/address/0xd26114cd6EE289AccF82350c8d8487fedB8A0C07#tokentxns

    You can take any contract address suitable to you.

# ABI:
    Scroll down the page you visited to get contract address and you should find "Contracts" TAB > a text box down named "ABI"> Copy full codes




