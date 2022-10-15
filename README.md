# PyChain Ledger

## Package Requirements

`pip install x` where x is the below listed packages

* `Python == 3.7.13`
* `pandas == 1.3.5`
* `streamlit == 1.13.0`

## Purpose of Use

Build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions and to verify the integrity of the data in the ledger.

## Files Navigation

* `Images`: Directory containing screenshots of the Streamlit application page
* `pychain.py`: Python file that contains the basic `PyChain` ledger structure

## Solution/Summary

1. Create a new data class named `Record`. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.

2. Modify the existing `Block` data class to store `Record` data.

3. Add Relevant User Inputs to the Streamlit interface.

![Relevant User Inputs](https://github.com/lrb924/PyChain_Ledger/blob/main/Images/Screen%20Shot%202022-10-15%20at%202.10.04%20PM.png)

4. Test the PyChain Ledger by Storing Records.

![Storing Records](https://github.com/lrb924/PyChain_Ledger/blob/main/Images/Screen%20Shot%202022-10-15%20at%202.10.45%20PM.png)