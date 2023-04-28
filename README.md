# Dictionary
* a dictionary written in C 
* take home project of digitize LLC

# Features
* Implemented Insert/Delete operation on word, and case sensitive/insensitive word search
* Used linked list data structure to implement the dictionary.

# Log of time:
2/2/2023 - 2/3/2023: Research on c struct, c string, string library, stdinput, stdoutput methods, build dictionary with alphetically insert.

2/3/2023: case sensititve search functionality completed.
2/4/2023: case insensitive search completed. Add entry into dictionary task completed. Delete dunctionary completed.

Usage:
1.The program first will ask the user to enter a sentence in the console follow by enter key. (This sentence should not be over 200 characters, and each word within should not be over 20 characters.)

2. After step1, user can enter $exit, $add, $delete, $case sensitive, $case insensitive or $instruction in the console to interact with the program.

Enter $exit to exit the program.
Enter $add to add a word into the dictionary.
Enter $case sensitive to turn on case sensitive search mode.
Enter $case insensitive to turn on case insensitive search mode.
Enter $instruction to view instruction in the console again.
Enter first four letters of the word to search in the dictionary(This should be at length 1 - 4).

Thoughts about this project:

The easy part of this program is the pointer manipulation of node because this is very similar to how c++ handle pointer. So I don't need additionary research on that, and make it work.

The challenging part is the language c itself. Since I don't know alot about c, I have to do some research on c string, c struct, string library, and stdio library to convert my thoughts into c program. In additon to that, unfamiliar with the language also gave my a hard time on debugging.
