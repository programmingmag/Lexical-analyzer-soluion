# Lexical-analyzer-soluion

Download Here: [Lexical analyzer soluion](https://jarviscodinghub.com/assignment/lexical-analyzer-soluion/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Write a lexical analyzer which reads a C- program, strips off comments (denoted by/* comments */), and generates four symbol tablets.

1. The KEYWORD table includes all keywords defined in Louden, pp.491). Each keyword is associated with an index. You may combine the special symbols into the KeyWord table. You may hardcode them.

Keyword Index
Else 1
If 2
int 3

2. The INDENTIFIER table includes all the user-defined identifiers. The table is similar to the keyword table except that it contains identifiers. Each identifier has its unique index.
3. The NUMBER table includes all integers and floats used in the program.

Num index attribute
60 1 integer
3.75 2 float

4. The TOKEN table includes all the tokens in the order that they are generated. The table should include the following information:

Token class index
Int kw 3
Gcd id 1
3.75 num 2
5. For the Regular Grammar for the tokens, refer to the Lexical Conventions of C- (Louden1). The input to your program is the example in Louden3 including the comments. Your program should strips off the comments.
6. The output from the program should include the program with comments stripped off. And all the tables mentioned above.
7. Please do file i/o, i.e. read the data from a file and send output to a file.

Please include a short report including the following:

Transition Diagrams corresponding to the identifier and the number in C- grammar. These are regular expressions.

Pseudo code

Upload the source code, executable, input and output.

