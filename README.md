# Comparing Programming Languages

## Java vs Python vs Ruby

#### Syntax
#####Lexical Tokens 
######(Considering only ASCII set)

`Tokens`                 | `Java`  | `Python` | `Ruby` 
---                   |:---:  | :---:  | :---:
  Comments               | ```// Single Line``` <br/> ```/* */ Multiline```  <br/> ```/** */ Documentation``` | ```# Single line``` <br /> ```""" DocString``` | ```# Single line```<br/> ```=begin =end Multiline ```   
Identifiers            | ```(letter```&#124;```$```&#124;```_)``` <br/> ```(letter```&#124;```$```&#124;```_```&#124;```digits)*``` <br/> ```Symbols starting with $ have special meaning```  |  ```(letter``` &#124; ```"_")```<br/>```(letter```&#124;```dig```&#124;```"_")*```  <br/> ```Symbols starting with _ have special meaning``` | ```(letter```&#124;```_)```<br/>```(letter```&#124;```_```&#124;```dig)``` <br/> ```@, @@, $-Identifiers can also begin with these characters.```
Literals               | ```Int```&#124;```Double```&#124;```boolean```&#124;```char```&#124;```String```&#124;```null```    | ```Int```&#124;```Float```&#124;```Imaginary```&#124;```bool```&#124;```String```&#124;```Bytes```&#124;```NoneType``` <br/> ```Use``` `\` ```to escape characters``` <br/> ```Use``` `"` ```string literal for text that is exposed to the user and ``` `'` ```for strings that relate to functionality in code``` | ```Int```&#124;```Float```&#124;```Boolean```&#124;```String```&124;```Date```  
Punctuation/Separators | ```Grouping```&#124;```Punctuations/Delimiters```   | ```Grouping```<br/>```Punctuations```<br/>```Assignments```    | ```Grouping```&#124;```Delimiters``` 
Operators              |  ```Arthimetic```<br/>```Logical```<br/>```Relational```<br/>```Bit-wise```  | ```Arthimetic```<br/>```Logical```<br/>```Relational```<br/>```Bit-wise```    | ```Arthimetic```<br/>```Logical```<br/>```Relational```<br/>```Bit-wise```  
Keywords               |   ```49 keywords, all starting with small letter```    | ```Predefined Literals```<br/>```(33 keywords)```<br/>**True,False,None**<br/>```Only keywords starting with capital letters```       |  ```41 keywords```
 
**Python:** 

Python lexical analyzer uses special tokens called `INDENT` and `DEDENT` to check the indentation and dedentation in the program. `Whitespaces` and `new line` characters are used to separate tokens and lines respectively. `Whitespaces` in `comments` and `strings` doesn't separate tokens. 

#####Blocks

#### Execution
