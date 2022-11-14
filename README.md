# Finanical Tech Finder. 
You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

## Instructions:

You’ll make the following updates to the provided Python file for this Challenge, which already contains the basic PyChain ledger structure that you created throughout the module:


* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

* Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Ganache blockchain.

* Review the transaction hash code associated with the validated blockchain transaction.





## Technologies

The project leverages python 3.7 with the following packages:

* [streamlit](https://streamlit.io/) - Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps. So let's get started.

* [Pandas](https://github.com/pandas-dev/pandas) - pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way towards this goal.

* [Web3](https://www.npmjs.com/package/web3) - This is the Ethereum JavaScript API which connects to the Generic JSON-RPC spec.

You need to run a local or remote Ethereum node to use this library.






---

## Installation Guide

Clone GitHub Respoitories to yoour local machine

```sh
   git clone https://github.com/jpqt/Challenge-18.git
 ```

Before running the application first install the following dependencies.

```python
pip install web3==5.17
```

```python
pip install eth-tester==0.5.0b3
```

```python
pip install mnemonic
```

```python
pip install bip44
```

---

## Fintech Professional
![Alt text](https://github.com/jpqt/Challenge-18/blob/main/photo/1.png?raw=true "Testing the bot")
* Enter values for the sender, receiver, and amount, and then click the Add Block button. Do this several times to store several blocks in the ledger.



![Alt text](https://github.com/jpqt/Challenge-18/blob/main/photo/2.png "Testing the bot")

* Verify the block contents and hashes in the Streamlit drop-down menu. Take a screenshot of the Streamlit application page, which should detail a blockchain that consists of multiple blocks. 

![Alt text](https://github.com/jpqt/Challenge-18/blob/main/photo/3.png "Testing the bot")

* Test the blockchain validation process by using the web interface. Take a screenshot of the Streamlit application page, which should indicate the validity of the blockchain.

---

## Contributors


Joshua Pak, taehanpak9@gmail.com

## License

Denver University 2022.
MIT License
