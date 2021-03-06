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
* *0.5 hours* Meeting with supervisor to discuss start of project, minutes found in [meetings/2021-09-28](meetings/2021-09-28.md)
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
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-10-05](meetings/2021-10-05.md)
* *1 hour* Looking at areas of the code to refactor and adding some helper functions to deal with QUIC encoding
  
### 7 Oct 2021
* *3 hours* Processing RFC sections with the QUIC structure parser
* *3 hours* Converting parsed data to internal representation objects

## Week 4

### 12 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-10-12](meetings/2021-10-12.md)

## Week 5

### 19 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-10-19](meetings/2021-10-19.md)
* *7 hours* Building a custom wrapper to automatically apply constraints for different field types

## Week 6

### 26 Oct 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-10-26](meetings/2021-10-26.md)

## Week 7

### 5 Nov 2021
* *1 hour* Researching ideas for parsed representation

## Week 8

### 7 Nov 2021
* *3 hours* Building diagrams and boilerplate code for the parsed representation

### 8 Nov 2021
* *3 hours* Completed code for parsed representation

### 9 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-11-09](meetings/2021-11-09.md)

## Week 9

### 15 Nov 2021
* *6 hours* Rough conversion of parsed representation into internal representation

### 16 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-11-16](meetings/2021-11-16.md)

## Week 10

### 23 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-11-23](meetings/2021-11-23.md)

## Week 11

### 29 Nov 2021
* *2 hours* Defining the boundaries of parsed representation and understand the next stages of the project

### 30 Nov 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-11-30](meetings/2021-11-30.md)

### 1 Dec 2021
* *2 hours* Brainstorming variable-length integer definition and field types

## Week 12

### 7 Dec 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2021-12-07](meetings/2021-12-07.md)
* *2 hours* Lecture regarding dissertation writing and project status

### 12 Dec 2021
* *2 hours* Working on structure/enum ideas to represent variable-length integers

## Week 13

### 13 Dec 2021
* *3 hours* Adding enums to the parsed representation
* *2 hours* Parsing enums correctly
* *1 hour* Fixing mypy problems
* *0.5 hours* Writing basic tests for parsed representation

### 14 Dec 2021
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2020-12-14](meetings/2021-12-14.md)
* *1 hour* Extending the QUIC syntax to represent enums
* *3 hours* Converting enums to the internal representation

### 16 Dec 2021
* *0.5 hours* Producing code for enums

## Week 14

### 21 Dec 2021
* *1 hour* Removing unused enum representations

## Week 15

### 30 Dec 2021
* *2 hours* Adding value constraints
* *1 hour* Removing outdated enum references
* *0.5 hours* Debugging value constraints because they weren't actually in the Rust formatter :/
* *0.5 hours* Cleaning up unnecessary code and fixing README formatting

## Week 16

### 6 Jan 2022
* *3 hours* Inferring sizes from corresponding length fields
* *2 hours* Unknown arbitrary fields handled

## Week 17

## Week 18

### 19 Jan 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-01-19](meetings/2022-01-19.md)
  
## Week 19

### 25 Jan 2022
* *4 hours* Altering QUIC RFC to explicitly state variable length integers

### 26 Jan 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-01-26](meetings/2022-01-26.md)

## Week 20

### 2 Feb 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-02-02](meetings/2022-02-02.md)
* *3 hours* Handling enums as field types

### 5 Feb 2022
* *4 hours* Working with enums

### 6 Feb 2022
* *4 hours* Fixing recursive enum building

## Week 21

### 8 Feb 2022
* *5 hours* Inferring PDUs from variant descriptions

### 9 Feb 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-02-09](meetings/2022-02-09.md)
* *4 hours* Bug fixing

## Week 22

### 16 Feb 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-02-16](meetings/2022-02-16.md)
* *1 hour* Focusing on dissertation writeup

## Week 23

### 23 Feb 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-02-23](meetings/2022-02-23.md)

### 25 Feb 2022
* *4 hours* Dissertation writeup

### 26 Feb 2022
* *5 hours* Dissertation writeup

## Week 24

### 01 Mar 2022
* *4 hours* Dissertation writeup

### 02 Mar 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-03-02](meetings/2022-03-02.md)
* *6 hours* Dissertation writeup

### 03 Mar 2022
* *6 hours* Dissertation writeup

### 04 Mar 2022
* *6 hours* Dissertation writeup

## Week 25

### 07 Mar 2022
* *6 hours* Dissertation writeup

### 08 Mar 2022
* *6 hours* Dissertation writeup

### 09 Mar 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-03-09](meetings/2022-03-09.md)
* *5 hours* Dissertation writeup

### 10 Mar 2022
* *6 hours* Dissertation writeup

### 11 Mar 2022
* *8 hours* Dissertation writeup

## Week 26

### 12 Mar 2022
* *6 hours* Dissertation writeup

### 15 Mar 2022
* *6 hours* Dissertation writeup

### 16 Mar 2022
* *0.5 hours* Meeting with supervisor to discuss progress and goals over the next week, minutes found in [meetings/2022-03-16](meetings/2022-03-16.md)
* *4 hours* Dissertation writeup

### 17 Mar 2022
* *6 hours* Dissertation writeup

### 18 Mar 2022
* *6 hours* Dissertation writeup

### 19 Mar 2022
* *8 hours* Dissertation writeup