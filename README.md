# C-Parser
Syntax checker for C language code

I have developed the code for a syntax checker conforming with the rules of C-language. Just like the GCC compiler first runs the syntax check, this code will parse the input code and comment if the syntax is correct or not. The grammar is built from scratch and can handle basic C-programs as well as complex programs containing loops, if-else, switch-case, structures, functions. Note: It cannot handle array intialisations (only declarations are taken care of) and dynamic memory allocations. 

I have used the lexer, LEX and the parser, YACC from the PLY module. These files are given separately as 'lexing.py' and 'parsing.py' files. These files will be required while running the python notebook. 

