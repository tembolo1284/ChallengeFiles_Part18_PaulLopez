# Project Title

This is the RoboAdvisor Application using Amazon Lex for Challenge 15! The project starts with me creating a new bot
named RoboAdvisor.  I create five sample utterances that all are along the lines of the user wanting to invest for their
retirement.  I create four slots to store my four variables: age, investment amount, first name, and risk level.
In a separate lambda function py file I put in business logic that doesn't allow the user to enter an age of 0 or less, or
older than 65. I also have logic that requires the user to put in an investment amount greater than or equal to 5000.
After that based on his risk level I output for him what his optimally portfolio breakdown would be. I use the following
mapping between risk level and portfolio breakdown for the user:

Risk Level     Portfolio Breakdown
* **none:** "100% bonds (AGG), 0% equities (SPY)"
* **low:** "60% bonds (AGG), 40% equities (SPY)"
* **medium:** "40% bonds (AGG), 60% equities (SPY)"
* **high:** "20% bonds (AGG), 80% equities (SPY)"



## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:

from datetime import datetime
from dateutil.relativedelta import relativedelta

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

I launch Amazon Lex and initiate a chat with the RoboAdvisor bot. That's it!

---

## Usage

Launch the RoboAdvisor bot and begin chatting.


---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
