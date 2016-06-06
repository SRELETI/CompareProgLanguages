# Comparing Programming Languages

## Java vs Python vs Ruby

####Lexical Tokens 
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

---

####Typing
| `Java` | `Python` | `Ruby` |
| :--: | :--: | :--: |
| `Static` | `Dynamic` | `Dynamic` |

<br/>
**Static Typing:**
A language is statically typed, if the type of the variable is known at compile time. 
<br/>

    ADV:
    * All kinds of type checking can be done by the compiler and therefore a lot of stupid bugs can be caught at compile time itself. 
    * Better documentation, in the form of type signatures.

    DISADV:
    * Type of the variable has to be specified each and every time.
    * Restrictive in the sense that, the developer has to know the type of the variable during prototyping itself.
<br/>

**Dynamic Typing:**A language is dynamically typed, if the type of the variable is interpreted at runtime. 
<br/>

    ADV:
    * More productive for the developer, as he doesnt have to specify the type each and every time.
    * Easier to prototype a product. 

    DISADV:
    * More bugs at run time.  
---

#####Blocks

#### Compilation

|`Java` | `Python` | `Ruby`
| :--:  | :--: | :--:
| `Java compiles the source code into bytecode. A tool +javac+ is used for compilation. As the complete program is read and compiled, javac uses a lot of memory.` | `Python compiles the source code into a intermediate form internally during execution. As it is a interpreted language, each line is interpreted at a time. So, it doesn't need large memory`| `Ruby compiles the source code into intermediate form internally during execution . Doesn't require much memory. Till 1.8, no intermediate conversion was done. From 1.9, the source code is compiled into intermediate form.`

---

#### Runtime

| `Java` |`Python` | `Ruby` |
| :--: | :--: | :--: |
| `Runs inside a JVM. The compiled code(by tecode) is executed by JVM. As bytecode is nearer to machine code, the code executes quickly.` | `Runs inside a VM. The interpreter, converts the source code into a intermediate form(.pyc) and executes it` | `Runs inside a VM. The interpreter converts the source into a intermediate form(YARV inst, from 1.9) and executes it` |

**TODO:** Memory usage and runtime speed comparsion

---




