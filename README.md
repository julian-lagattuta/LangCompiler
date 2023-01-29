
# LangCompiler
A compiler is a program that converts code into a runnable program. Written in Python from Scratch. Lexer, parser, and compiler that compiles my own programming language named “Lang” to Intel syntax 32-bit x86. I made  during the summer before sophomore year. An older version of Lang supported an interpreter. 


There are Java style while loops. For loops look like this:
```
for VARIABLE in EXPR to EXPR {
	code in here
}
```
Variables are typed. 

Types:
int
bool


`int a =5`
No semicolons.

Classes exist, though functions may or may not work correctly.
```
class Jake{
    int a=5
    void Jake(){
        print(this.a)
    }
}
```
Constructors are return type void.

If statements are like this:
```
if 5==a{
	print(100)
}
```

Builtin functons:
input
print
# Build Instructions

Use a 32bit version of GCC

Install NASM

Run `python langcompiler/__init__.py`

Edit `make.bat` and replace `gcc` with the 32 bit version of gcc

Run `make.bat`

