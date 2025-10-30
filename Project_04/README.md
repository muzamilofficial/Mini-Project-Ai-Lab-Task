## Overview
This project consists of **four independent Python programs**.  
Each part demonstrates a different concept related to string manipulation, input validation, and number processing.

---

## Part 1 – Debit Card Number Validation

### Description
This program checks whether a given debit card number is **valid or invalid** using a simplified form of the **Luhn Algorithm**.

### How It Works
1. Takes a debit card number as input (spaces allowed).  
2. Removes spaces and isolates the last digit.  
3. Reverses the remaining digits.  
4. Doubles every second digit and subtracts 9 if the result exceeds 9.  
5. Sums all digits including the last one.  
6. If the total is divisible by 10 → **Valid**, otherwise **Invalid**.



---



## Part 2 – Remove Non-Alphanumeric Characters

### Description
This program takes a string and removes all characters except letters and numbers.



---



## Part 3 – Sort Characters in a String

### Description
This program sorts all characters in an input string in **ascending order** using the **bubble sort algorithm**.




---



## Part 4 – Sort Words in a Sentence

### Description
This program takes a sentence and sorts all words in **alphabetical order** using bubble sort logic.


## Structure
│
├── part1_card_validation.py

├── part2_remove_special.py

├── part3_sort_characters.py

├── part4_sort_words.py

└── README.md



