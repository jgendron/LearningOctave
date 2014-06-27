# Professor Ng's Octave Tutorial

These notes capture the key code from the Octave software tutorial as presented by Dr. Andrew Ng in the Coursera [Machine Learning course](https://www.coursera.org/course/ml). The Table of Contents below contains the material as presented in Professor Ng's lectures.


##### Table of Contents  
[Basic Operations](#BasicOps)  
[Moving Data Around](#moving)  
[Computing on Data](#computing)  
[Plotting Data](#plotting)  
[Control Statements](#control)  
[Vectorization](#vector)  

<a name="BasicOps"/>
## Basic Operations  

#### Basic Math
```
5 + 6  
3 - 2  
5 * 8
1 / 2    
2 ^ 6  
```  

11  
1  
40  
0.500  
64  

#### Logical Operators
```
1 == 2 % false  
1 ~= 2 % true  
1 && 0 % AND
1 || 0 % OR
xor(1,0) % true
```

#### Changing the Octave Prompt

`PS1('>> ');` will change the prompt to `>>`

#### Working with Variables
