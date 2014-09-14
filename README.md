Serial Read
==============
The purpose with this program is to enable stable and complex communication with computers.

The program read_word_serial.ino is a small arduino program to document the function receive_string(). When called, the function waits for a string to be sent over serial and store the string in an array. The function is stopped when the word is ended by a new line (‘\n’) or if the recived word is longer than the buffer array inData.
