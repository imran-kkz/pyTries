# Compilers
- Lexical Analysis
    - the process of breaking up code into identified tokens
- Syntax Analysis (Parsing)
    - take the pieces that have been broken up and figure out which pieces need to be executed first
- Semantic Analysis
    - process of applying language rules 
    - includes raising errors when rules are broken
    - eg. type mismatch, undeclared variable etc.
- Optimization
- Code Generation

# Interpreters
- Take source code and execute on the code
- Parsing source code and executing it directly
- Compile to intermediate form (bytecode) and then execute
    - Python does this (vm runs under the hood)
    - Python is an interpreted language, but source code is compiled to bytecode before being run

# Python Specific Keywords
|False|finally|while|
|await|is|assert|
|else|return|del|   
|import|and|global|
|pass|continue|not|
|None|for|with|
|break|lambda|async|
|except|try|elif|
|in|as|if|
|raise|def|or|
|True|from|yield|
|class|nonlocal|