# Assembly-Project-Tasm-8086

This assembly code is designed to calculate the frequency of each character in a given string. Here’s a detailed breakdown of how it works:

Data Segment: This is where the data used in the program is declared. It includes messages to be displayed to the user, an array to store the input string, and variables to hold the character count and the character being checked.

Code Segment: This is where the main logic of the program resides.

START: The program starts here. It sets up the data segment and displays the first message to the user asking for a string input.

STRING_INPUT: This is a loop where the program reads the input character by character until it encounters a carriage return (ASCII value 13), which signifies the end of the input.

GET_TOTAL_CHAR: This section stores the address of the last character of the string.

CHECK_NEXT_CHAR: This section increments the pointer to the next character to be checked.

ACCEPT_CHAR: This section loads the character to be checked into the BL register.

DISPLAY_2ND_MSG: This section displays the character being checked.

COUNT_CHAR: This is a loop where the program checks each character of the string against the character in the BL register. If it finds a match, it increments the character count.

COUNT_OCC: This section increments the character count if a match is found.

REFRESH_REG: This section resets the registers and prepares for the next character check.

BREAKING_NUM: This section breaks the character count into individual digits.

DISPLAY_COUNT: This section displays the count of the character.

LOOP_ALL_CHAR: This section checks if all characters have been processed. If not, it loops back to CHECK_NEXT_CHAR.

EXIT: This section ends the program.
