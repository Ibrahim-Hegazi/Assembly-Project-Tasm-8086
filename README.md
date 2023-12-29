# Character Occurrence Frequency Sorting

## Introduction
This assembly code takes a string as input and calculates the occurrence frequency of each character in the string. It then sorts and displays the frequencies in descending order along with the corresponding characters.

## Instructions
1. Run the program.
2. Enter a string when prompted.
3. The program will calculate and display the occurrence frequency of each character in the entered string, sorted in descending order.

## Code Overview
- `DATA_SEG` segment: Declares data variables and messages.
- `CODE_SEG` segment: Contains the main code.
  - `START`: Entry point of the program.
  - `STRING_INPUT`: Takes user input and stores it in an array.
  - `GET_TOTAL_CHAR`: Computes the length of the entered string.
  - `CHECK_NEXT_CHAR`, `ACCEPT_CHAR`, `DISPLAY_2ND_MSG`, `COUNT_CHAR`, `COUNT_OCC`, `REFRESH_REG`: Handle character counting and frequency calculation.
  - `BREAKING_NUM`, `DISPLAY_COUNT`, `LOOP_ALL_CHAR`: Handle frequency display.
  - `SORT_AND_EXIT`: Sorts the frequency array and displays the result.
  - `BUBBLE_SORT`: Sorting subroutine (needs modification for lexicographical sorting).
  - `DISPLAY_SORTED`: Displays the sorted frequencies and characters.
  - `DISPLAY_PAIR`: Displays frequency and character pairs.
  - `EXIT`: Exits the program.

## Known Issue
- There is an error in the sorting part that needs to be modified for lexicographical sorting.

## Modification
- To enable lexicographical sorting, modify the `BUBBLE_SORT` subroutine according to the provided instructions in the code comments.

