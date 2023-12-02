# AoC23-2
Solution in "Airline food" for Advent-of-code 2023 day 2 - part 2 https://adventofcode.com/2023/day/2

Link to interpreter: https://github.com/jamie-large/Airline-Food/blob/main/Airline-food.py
Default interpreter prints ascii characters, so I changed line 203 to output raw number from stack.

Input must be given sequentially one number at a time:

`ID0 num0 type0 num1 type1 ... 0 ID1 num0 type0 num1 type1 ... 0 ID2 num0 type0 num1 type1 ... 0 ... 0`

Number 0 is to detect the end of the line (numX == 0) and also the end of the input (if ID == 0)
