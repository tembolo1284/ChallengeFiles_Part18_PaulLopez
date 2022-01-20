# Project Title

This is the Blockchain ledger system application for Challenge 18! I create a Record data class that stores
3 attributes: sender, receiver, and amount. I specify a variable type for each.  I modify the Block data class
so it can receive my Record data as one block of the 3 attributes I gave it. I then go to the streamlit part of the code
and change the input method by deleting the original method and adding three that allows the user to enter a sender, receiver,
and amount. When the web application runs through streamlit one can see that there are now three input boxes for the user.
Once the user enters values in each, I populate the ledger by putting the 3 attributes in the first column called record. The other columns are populated as before.  From there one is able to validate the chain by clicking the button.  This was such a fun challenge!

## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

---


## Usage

Go to the directory where pychain.py is located and run the file by typing streamlit run pychain.py in the command
line and that's it!


---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
