FINITE AUTOMATA – Task 2

About the Project
This repository contains three validation applications implemented using Deterministic Finite Automata (DFA) as part of the Formal Languages and Automata Theory (FLA) course. Each program processes an input string through defined states and transitions, then reports whether the input satisfies the rules.
Applications Implemented
     1. OTP Verification System
•	Accepts an OTP containing exactly six digits.
•	Rejects inputs with fewer or more than six digits.
•	Rejects non-numeric characters.
     2. Username Validation System
•	Allows usernames with a length of 3 to 8 characters.
•	Requires the first character to be a lowercase letter.
•	Allows lowercase letters, digits, and underscores in the remaining positions.
•	Rejects spaces and other special characters.
     3. Time Format Validation System
•	Checks time in 24-hour HH:MM format.
•	Allows hours from 00 to 23 and minutes from 00 to 59.
•	Rejects incorrect formats and values outside these ranges.
     Tools Used
•	Python
•	Google Colab
•	Matplotlib for DFA diagrams

The repository includes the following files:

- `OTP_Verification.ipynb` – Python implementation of the OTP verification DFA.
- `Username_Validation.ipynb` – Python implementation of the username validation DFA.
- `Time_Validation.ipynb` – Python implementation of the time format validation DFA.
- `FLA_OUTPUT_SCREENSHOTS.pdf` – Screenshots showing the code, DFA diagrams, and test results.

    How to Run
1.	Open the required .ipynb notebook in Google Colab.
2.	Run the cells from top to bottom.
3.	View the DFA diagram and the test results.
4.	Enter a value when prompted to check whether it is accepted or rejected.

Conclusion
These implementations demonstrate how DFA can be used for simple input-validation tasks. Working through the applications provided practice with defining states, transitions, accepting states, and testing strings against a language.
     

