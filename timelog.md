# Timelog

* Parsing the QUIC Packet Description Language
* Ryan Murphy
* 2385677M
* Stephen McQuistin

## Week 1

### 20 Sept 2021
* *4 hours* Learning parsley grammar file syntax and writing a parser for QUIC packet descriptions

### 23 Sept 2021
* *2 hours* Adding all QUIC packet descriptions as text files and ensuring the grammar file can parse them all correctly

## Week 2

### 27 Sept 2021
* *2 hours* More research into how QUIC works and how to represent packet structures in Python

### 28 Sept 2021
* *0.5 hours* Meeting with supervisor to discuss start of project, minutes found in [meetings/2020-09-28](meetings/2021-09-28.md)
* *1 hour* Understanding the [parser](ips-protodesc-code/npt/parser_asciidiagram.py) code

### 29 Sept 2021
* *1 hour* Implementing [QUIC structure parser](../ips-protodesc-code/npt/parser_quicstructures.py)
* *5 hours* Stepping through the program line for line to get a better understanding of the parsing process

### 30 Sept 2021
* *1 hour* Extending the RFC txt grammar to accept QUIC structures, still unsure if the txt parsing is working
* *3 hours* Added option to npt to allow a user to specify the parser type. Working on the QUIC parser object and grammar.

### 1 Oct 2021
* *1 hour* Building [QUIC structure parser](../ips-protodesc-code/npt/parser_quicstructures.py)

## Week 3

### 5 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-10-05](meetings/2021-10-05.md)
* *1 hour* Looking at areas of the code to refactor and adding some helper functions to deal with QUIC encoding
  
### 7 Oct 2021
* *3 hours* Processing RFC sections with the QUIC structure parser
* *3 hours* Converting parsed data to internal representation objects

## Week 4

### 12 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-10-12](meetings/2021-10-12.md)

## Week 5

### 19 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-10-19](meetings/2021-10-19.md)
* *7 hours* Building a custom wrapper to automatically apply constraints for different field types

## Week 6

### 26 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-10-26](meetings/2021-10-26.md)

## Week 7

### 5 Nov 2021
* *1 hour* Researching ideas for parsed representation

## Week 8

### 7 Nov 2021
* *3 hours* Building diagrams and boilerplate code for the parsed representation

### 8 Nov 2021
* *3 hours* Completed code for parsed representation

### 9 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-11-09](meetings/2021-11-09.md)

## Week 9

### 15 Nov 2021
* *6 hours* Rough conversion of parsed representation into internal representation

### 16 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-11-16](meetings/2021-11-16.md)

# Week 10

### 23 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-11-23](meetings/2021-11-23.md)

# Week 11

### 29 Nov 2021
* *2 hours* Defining the boundaries of parsed representation and understand the next stages of the project

### 30 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-11-30](meetings/2021-11-30.md)

### 1 Dec 2021
* *2 hours* Brainstorming variable-length integer definition and field types

# Week 12

### 7 Dec 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-12-07](meetings/2021-12-07.md)
* *2 hours* Lecture regarding dissertation writing and project status