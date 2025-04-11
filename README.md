# 💻 🧮 = PXPR - Expression Parser = 🧮 💻
PXPR (**P**arse e**XPR**ession) is a fast arithmetic and boolean expression parser written in Rust, supporting arithmetic operations such as addition, subtraction, multiplication, division, modulo, 
expressions with nested parentheses, as well as C-style boolean expressions such as the logical not, and, or operators and the logical implication operator. PXPR can be evaluate expressions directly from the command line
or via the PXPR REPL. The goal of PXPR is to provide an easy-to-use, but feature rich command line calculator. Rather than opening up an IDE or text-editor, writing some code, compiling that code, and running it all to get the value 
of a basic expression, PXPR can evaluate the expression directly from the command line.

## Sections
- [How to use PXPR](#Examples)
- [Installing PXPR](#Installation)

## Examples ✍️
### Compute an expression via the CLI
```sh
pxpr "3 - (2 + 5) + 2"
```
Which outputs:
```sh
    = -2
```

### Compute an expression via the REPL
```sh
pxpr
```
Which will initialize the REPL:
```
expr > 3 - (2 + 5) + 2
        = -2
```

## Installation 📲
To install PXPR, clone this repository:
```sh
git clone https://github.com/brayner05/pxpr.git
```

Next, switch to the repository directory and run the installation script:
```sh
cd expression-evaluator
chmod +x ./install.sh
./install.sh
```

If no errors occurred, then PXPR is now installed on your machine.
