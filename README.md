# Comparing Programming Languages

## Java vs Python vs Ruby

#### Syntax
#####Lexical Tokens 
######(Considering only ASCII set, even though languages support Unicode)

`Tokens`                 | `Java`  | `Python` | `Ruby` 
---                   |:---:  | :---:  | :---:
  Comments               | ```// Single Line``` <br/> ```/* */ Multiline```  <br/> ```/** */ Documentation``` | ```# Single line``` <br /> ```""" DocString``` | Ruby  
Identifiers            | ```(letter```&#124;```$```&#124;```_)``` <br/> ```(letter```&#124;```$```&#124;```_```&#124;```digits)*``` <br/> ```Symbols starting with $ have special meaning```  |  ```(letter``` &#124; ```"_")```<br/>```(letter```&#124;```dig```&#124;```"_")*```  <br/> ```Symbols starting with _ have special meaning``` | 2:3  
Literals               | ```Int```&#124;```Double```&#124;```boolean```&#124;```char```&#124;```String```&#124;```null```    | ```Int```&#124;```Float```&#124;```Imaginary```&#124;```bool```&#124;```String```&#124;```Bytes```&#124;```NoneType``` <br/> ```Use``` `\` ```to escape characters``` <br/> ```Use``` `"` ```string literal for text that is exposed to the user and ``` `'` ```for strings that relate to functionality in code``` | 2:4  
Punctuation/Separators |0:5    | ```Grouping```<br/>```Punctuations```<br/>```Assignments```    | 2:5  
Operators              |0:6    | ```Arthimetic```<br/>```Logical```<br/>```Relational```<br/>```Bit-wise```    | 2:6  
Keywords               |       | ```Predefined Literals```<br/>```(33 keywords)```<br/>**True,False,None**<br/>```Only keywords starting with capital letters```       |      
 
**Python:** 

Python lexical analyzer uses special tokens called `INDENT` and `DEDENT` to check the indentation and dedentation in the program. `Whitespaces` and `new line` characters are used to separate tokens and lines respectively. `Whitespaces` in `comments` and `strings` doesn't separate tokens. 

#### Execution
