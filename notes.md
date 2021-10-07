# Project Notes

## Useful Links
- https://github.com/glasgow-ipl/ips-protodesc-code
- https://github.com/fork-bombed/level4-project

## Understanding the project code
- Stepping through the program line-by-line using a debugger to understand how it works
  - Using VSCode debugger with options to use ascii diagrams or quic parser
- Altering the input options to allow for different parsers
- Creating my own QUIC parser class
- RFC XML parser seems to be able to parse the artwork data already
- Still unsure how text parsing works as I've been unable to get a single text file to parse so far

## Parsing
- Had to make slight changes to the RFC XML parser to accept tables with empty values (as seen in [Section 12.4](https://datatracker.ietf.org/doc/html/rfc9000#section-12.4) in RFC9000)
- Parsing straight to objects seems to simplify the code a lot, but I might encounter issues when types haven't been parsed/initialised yet?


## Refactoring Ideas
- Build custom ParserException base class in parser.py. Allows for more accurate error handling in future.
- Generate internal representation types straight from the grammar file
- Increase modularity and readability by returning values from functions and then updating attributes rather than overwriting attributes within functions