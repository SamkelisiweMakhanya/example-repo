# award
award.py is a python program that determines the award a participant receives after completeting a triathlon.
The program prompts the user to enter the number of minutes taken to complete the swimming, cycling, and running events. It then calculates the participant's total race time and determines the appropriate award based on the triathlon award criteria.

# Features
- Accepts swimming, cycling and running times as user input.
- Calculates the total time taken to complete the triathlon.
- Determines the participant's award catergory.
- Displays the final result to the user.

# Requirements
- Python 3.x

# Installation
1. Clone or download the repository.
2. Navigate to the project directory.
git clone <repository-url> cd <repository-name>

# Usage
Run the program using Python:

python award.py

# Example
Enter swimming time (minutes): 40
Enter cycling time(minutes): 60
Enter running time(minutes): 30

Total time: 130 minutes
Award: Provincial colors

# How it works
1. The user enters the time taken for:
   - swimming
   - cycling
   - running
2. The program calculates the total race time:
   Total time = Swimming time + Cycling time + Running time
3. The total time is compared against the triathlon award criteria to determine the award earned.

# Award Criteria
The participant's award is determined according to the official triathlon rules implemented in the program.

# File Structure
.
|___ award.py
|___ README.md

# Author
Created as part of Hyperiondev programming exercise

# License
This program is available for educational purposes

