# blockchain_ledger_app
This is an blockchain [web application](https://derickdecesare-blockchain-ledger-app-pychain-oco6ek.streamlitapp.com/) built using python and deployed using streamlit that allows users to conduct transactions and verify the integrity of the data. The information of the block is customized by the user and is hashed by the SHA256 hashing algorithm. This hash is then added to the next block to ensure the validity of the chain. If one block is altered then that block and all following blocks will be invalid.

## Before any transactions are added:
![empty](Images/empty.png)

---

## <center> After adding a few transactions: </center>
![3_tran](Images/3_tran.png)

---

## Verifying a block:
![verify](Images/verify.png)

---

## Technologies

This analysis uses Python and the following libraries:
* [Pandas](https://pandas.pydata.org/) - Provides data manipulation and visualization.
* [dataclass](https://docs.python.org/3/library/dataclasses.html) - Provides a decorator and functions for automatically adding generated special methods.
* [Typing](https://docs.python.org/3/library/typing.html) - Provides runtime support for type hitns
* [datetime](https://docs.python.org/3/library/datetime.html) - Provides classes for manipulating dates and times
* [hashlib](https://docs.python.org/3/library/hashlib.html) - Implements a common interface to many different secure hash and message digest algorithms.
---

## Installation Guide

You can use the streamlit web app at [this link](https://derickdecesare-blockchain-ledger-app-pychain-oco6ek.streamlitapp.com/). 

OR

You can run it locally, if you'd like to repurpose it for your own use. To do so please follow these steps:

1. Download and install [Anaconda](https://www.anaconda.com/products/distribution). 

2. Clone the the blockchain_ledger_app repository to your local machine.

3. Navigate to the directory of the cloned repo in your terminal/gitbash.

4. Run the following command in your terminal or gitbash:
```python
pip install -r requirements.txt
```

5. Run the following command in your terminal or gitbash:
```python
streamlit run pychain.py
```

---

## Usage

After lauching the application through the [streamlit app](https://derickdecesare-blockchain-ledger-app-pychain-oco6ek.streamlitapp.com/) or by running it locally on your computer you can add transactions and verify those transactions. You can also change the difficulty of the block calculation needed to add a block by adjusting the difficulty score from 1-5.

---

## Contributors

Derick Decesare | [LinkedIn](https://www.linkedin.com/in/derickdecesare/) | derick.decesare@gmail.com

---

