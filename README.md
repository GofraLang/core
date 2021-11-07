# Most Simple|Stupid Programming language. (MSPL) 
 ***Stack - Based programming language "written in Python"***


## Features
- Interpretate code (Run it).
- Generate graph for the code (`.dot` graphviz).
- Compile (Generate) python code (MSPL -> Python).
- Lint (Type check) [WIP].

## Language features
- Stack implementation (push, pop)
- Conditional IFs ([bool_from_stack] if [code] else [code] endif).
- WHILE loops (while [expression] then [code] endif)
- Bytearray Memory (mbwrite, mbread, mbshowc, mbptr etc...)

## Simple example
```mode: opascal
35 // Push 35 in the stack.
5 // Push 5 in the stack.
+ // Pop both 35 and 5, and push their sum in the stack.
show // Pop value from the stack and show it on the screen.
```

## Documentation: `DOCUMENTATION.MD`, Examples: `./examples/README.MD`.