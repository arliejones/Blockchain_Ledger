# Blockchain Ledger

This program is a blockchain-based ledger system that allows money transfers between senders and receivers. The program also is built to verify the integrity of the data in the ledger.

----

## Technologies
This application is in the Python programming language and was edited in Visual Studio Code. The Python libraries, tools, and modules used in this application are Pandas, Streamlit, dataclasses, typing, datetime, and hashlib.

[Pandas](https://pandas.pydata.org/docs/index.html), [Streamlit](https://docs.streamlit.io/), [dataclasses](https://docs.python.org/3/library/dataclasses.html), [typing](https://docs.python.org/3/library/typing.html), [datetime](https://docs.python.org/3/library/datetime.html), [hashlib](https://docs.python.org/3/library/hashlib.html)


----

## Installation Guide
This program uses the Pandas library. If the user is not already running an environment that includes Pandas, then they will need to intall the library. Instructions shown in the installation guide --> [Pandas Installation Guide](https://pandas.pydata.org/docs/getting_started/install.html)

For the program to run correctly, the user must make sure that all libraries and modules are correctly imported in the beginning of the code. This looks like:

    import streamlit as st
    from dataclasses import dataclass
    from typing import Any, List
    import datetime as datetime
    import pandas as pd
    import hashlib


----

## Usage

**The program is comprised of 4 parts:**

1. Create a Record Data Class

2. Modify the Existing Block Data Class to Store Record Data

3. Add Relevant User Inputs to the Streamlit Interface

4. Test the PyChain Ledger by Storing Records


![]("Resources/pychain.png")
