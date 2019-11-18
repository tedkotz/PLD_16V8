# PLD_16V8
A collection of notes and utilities to aid in open development for the 16v8 Generic Array Logic device

Playing around with the open source minipro software for the TL866CS revealed that the programmer claimed to support the ATF16V8B. Which were available for less than $1 each online. The programmer required being upgraded to version 0.4 and the latest firmware. 

    minipro -p ATF16V8B -P -w myfile.jed

Looking for tools to create files for loading onto the 16v8 didn't find anything open source, but how it works could pieced together from the datasheets, some youtube videos and dumping the blank chips.

This project collects all that information and gives some jed files that are organized to help better understand what the data in the file means. It also contains some examples to help with understanding or that may be useful on their own.

Good Luck
