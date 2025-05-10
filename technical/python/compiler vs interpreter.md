
Programming Concepts & Variables (from image)
├─── Key Terms (Definitions from Comments)
│    ├─── Source Code
│    │    └── Definition: Original Code You Write it in Computer
│    │    └── Example: The Python lines `x = 10`, `x = "Hello"`, `print(x)`
│    │
│    ├─── Translation
│    │    └── Definition: Converting Source Code Into Machine Language
│    │    └── Example: A Python interpreter converting Python code to bytecode, which is then executed by the Python Virtual Machine.
│    │
│    ├─── Compilation
│    │    └── Definition: Translate Code Before Run Time
│    │    └── Example: A C++ compiler (`g++`) taking a `.cpp` file and producing an executable machine code file before you can run it.
│    │
│    ├─── Run-Time
│    │    └── Definition: Period App Take To Executing Commands
│    │    └── Example: The duration when the `print(x)` command is actually being carried out by the computer after the script is launched.
│    │
│    └─── Interpreted
│         └── Definition: Code Translated On The Fly During Execution
│         └── Example: Python is an interpreted language. When you run `python script.py`, the interpreter reads, translates, and executes each line (or block) more or less sequentially.
│
└─── Variables (Example from Python code)
     ├─── Concept: A named storage location that holds a value. The value can change (vary).
     │
     ├─── Line 1: `x = 10`
     │    └── Action: Assigns the integer value `10` to the variable named `x`.
     │    └── State: `x` now holds the integer `10`.
     │
     ├─── Line 2: `x = "Hello"`
     │    └── Action: Reassigns the string value `"Hello"` to the *same* variable `x`.
     │    └── State: `x` now holds the string `"Hello"`. (This demonstrates Python's dynamic typing - the type of the variable can change).
     │
     └─── Line 3: `print(x)`
          └── Action: Retrieves the current value stored in `x` and displays it to the console.
          └── Output: Hello