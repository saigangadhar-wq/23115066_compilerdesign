# 23115066_compilerdesign
Design a custom instruction for a given equation in compiler.
# Custom XOR Compiler with TAC, Assembly & Optimization

This C++ project simulates a simple compiler pipeline to compute XOR of three integers.
It includes:
- **Lexical Analysis**
- **Parsing to AST**
- **Optimization**
- **Three Address Code (TAC) generation**
- **Assembly Code simulation**
- **Execution**

## How to Compile and Run

1. Compile with g++:
```bash
g++ main.cpp -o xor_compiler
```

2. Run the program:
```bash
./xor_compiler
```

3. Enter three integers separated by space when prompted.

## Example

**Input:**
```
1 2 3
```

**Output:**
```
Three Address Code:
t1 = 1 ^ 2
t2 = t1 ^ 3

Assembly Code:
MOV R1, #1
XOR R1, #2
XOR R1, #3

Optimized XOR result: 0
```
## GITHUB LINK 
https://github.com/saigangadhar-wq/23115066_compilerdesign# Custom XOR Compiler with TAC, Assembly & Optimization

This C++ project simulates a simple compiler pipeline to compute XOR of three integers.
It includes:
- **Lexical Analysis**
- **Parsing to AST**
- **Optimization**
- **Three Address Code (TAC) generation**
- **Assembly Code simulation**
- **Execution**

## How to Compile and Run

1. Compile with g++:
```bash
g++ main.cpp -o xor_compiler
```

2. Run the program:
```bash
./xor_compiler
```

3. Enter three integers separated by space when prompted.

## Example

**Input:**
```
1 2 3
```

**Output:**
```
Three Address Code:
t1 = 1 ^ 2
t2 = t1 ^ 3

Assembly Code:
MOV R1, #1
XOR R1, #2
XOR R1, #3

Optimized XOR result: 0
```
