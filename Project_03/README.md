## Overview
This project simulates an **intelligent temperature control system** using a simple **agent-based model** in Python.  
The agent monitors the temperature of different rooms and decides whether to turn a device **on** or **off** based on a threshold temperature.

All temperature readings and actions are stored in a text file (`task3.txt`) for reference.

---

## Features
- Takes temperature input for multiple rooms  
- Compares current room temperature with a fixed threshold  
- Decides whether to **turn on** or **turn off** based on the condition  
- Saves temperature logs and actions in a text file  
- Displays temperature history at the end  

---

## How It Works
1. The `modelagent` class initializes with a threshold temperature and a log file.
2. The `sensor()` method:
   - Compares the user’s temperature input with the threshold.
   - Returns “turn on” if it’s greater or equal, otherwise “turn off”.
   - Logs each reading to `task3.txt`.
3. The `actuator()` method prints the current temperature and the corresponding action.
4. The `call_history()` method displays the dictionary of stored readings and the contents of the log file.

---

## Requirements
- Python 3.x


