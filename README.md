## [ECE 2112] ADVANCED COMPUTER PROGRAMMING AND ALGORITHMS
S.Y. ‘26 - ‘27  | SECOND YEAR | FIRST SEM | hzlcbl

## Module 1: Base Computing with Python
#### Python Base Types
Basic data types used in Python programming

`type()` → returns the type of an object at runtime

``` python
type(346)   #int - whole numbers
type(45.3)  #float - numbers with decimal places
type('c')   #str - textual data
type(true)  #bool - true or false
```

#### Python Type Conversion
How will I convert 34.5 to integer? `int(34.5) → 34`
<br>How will I convert 45 to float? `float(45) → 45.0`

#### Operations in INTs and FLOATs
| Operation | Symbol | Example | Output |
| :---: | :---: | :---: | :---: |
| Addition | + | 78+85 | 163 |
| Subtraction | - | 78-85 | -7 |
| Multiplication | * | 78*85 | 6630 |
| Exponentiation | ** | 78**85 | 6730405... |
| Division (float) | / | 20/6 | 3.3333 |
| Division (int) | // | 20//6 | 3 |
| Modulo | % | 20%6 | 2 |

#### Operation on String
**Strings** - letters, special characters, spaces, and digits enclosed in single or double quotation marks

```python
s = "Advanced Programming"
s.swapcase() → "aDVANCED pROGRAMMING" # uppercase letters → lowercase; lowercase letters → uppercase
max(s) → "v" # highest value
s.isupper() → False # identifies if given variable is in uppercase
s.replace("m", "*") → "Advanced Progra**ing" # replaces one character to another
x = "gram" in s → True #
s[0:20:4] → "An gm" # slicing string_name(index of first element; number of characters; increment)
```
