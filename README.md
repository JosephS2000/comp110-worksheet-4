# COMP110 Worksheet 4

Please edit this README.md file with your answers to the worksheet questions.

## Question 1

### a 
|A | B | NOT C | A AND B | A AND B AND NOT C|
|:-|:-:|:-----:|:-------:| ----------------:|
|F | F |   T   |   F     |        F         |
|F | F |   F   |   F     |        F         |
|F | T |   T   |   F     |        F         |
|F | T |   F   |   F     |        F         |
|T | F |   T   |   F     |        F         |
|T | F |   F   |   F     |        F         |
|T | T |   T   |   T     |        T         |
|T | T |   F   |   T     |        F         |

### b 
|A | B | NOT C | B AND NOT C | NOT(B AND NOT C) | A AND NOT(B AND NOT C)|
|:-|:-:|:-----:|:-----------:|:----------------:| ---------------------:|
|F | F |   T   |    F        |        T         |           F           |
|F | F |   F   |    F        |        T         |           F           |
|F | T |   T   |    T        |        F         |           F           |
|F | T |   F   |    F        |        T         |           F           | 
|T | F |   T   |    F        |        T         |           T           |
|T | F |   F   |    F        |        T         |           T           |
|T | T |   T   |    T        |        F         |           F           | 
|T | T |   F   |    F        |        T         |           T           |

### c 
|A | B | C | NOT B | (A OR NOT B) | (A OR C) | (A OR NOT B) AND (A OR C)|
|:-|:-:|:-:|:-----:|:------------:|:--------:| ------------------------:|   
|F | F | F |   T   |       T      |    F     |            F             |
|F | F | T |   T   |       T      |    T     |            T             |
|F | T | F |   F   |       F      |    F     |            F             |
|F | T | T |   F   |       F      |    T     |            F             |
|T | F | F |   T   |       T      |    T     |            T             |
|T | F | T |   T   |       T      |    T     |            T             |
|T | T | F |   F   |       T      |    T     |            T             | 
|T | T | T |   F   |       T      |    T     |            T             |

### d 
|B | D | NOT C | NOT A | NOT (B OR NOT C) | (NOT A AND D) | NOT (B OR NOT C) AND (NOT A AND D)|A AND NOT (B OR NOT C) AND (NOT A AND D)|
|:-|:-:|:-----:|:-----:|:----------------:|:-------------:|:---------------------------------:| --------------------------------------:|
|F | F |   T   |  T    |        F         |       F       |                 F                 |                   F                    |
|F | T |   T   |  T    |        F         |       T       |                 F                 |                   F                    |
|F | F |   F   |  T    |        T         |       F       |                 F                 |                   F                    |
|F | T |   F   |  T    |        T         |       T       |                 T                 |                   F                    |
|T | F |   T   |  T    |        F         |       F       |                 F                 |                   F                    |
|T | T |   T   |  T    |        F         |       T       |                 F                 |                   F                    |
|T | F |   F   |  T    |        F         |       F       |                 F                 |                   F                    |
|T | T |   F   |  T    |        F         |       T       |                 F                 |                   F                    |
|F | F |   T   |  F    |        F         |       F       |                 F                 |                   F                    |
|F | T |   T   |  F    |        F         |       F       |                 F                 |                   F                    |
|F | F |   F   |  F    |        T         |       F       |                 F                 |                   F                    |
|F | T |   F   |  F    |        T         |       F       |                 F                 |                   F                    |
|T | F |   T   |  F    |        F         |       F       |                 F                 |                   F                    |
|T | T |   T   |  F    |        F         |       F       |                 F                 |                   F                    |
|T | F |   F   |  F    |        F         |       F       |                 F                 |                   F                    | 
|T | T |   F   |  F    |        F         |       F       |                 F                 |                   F                    |

## Question 2

### a ![2a)](C:\Users\Spaul\Documents\COMP 110\Worksheets)

### b ![2b)](C:\Users\Spaul\Documents\COMP 110\Worksheets)

### c ![2c)](C:\Users\Spaul\Documents\COMP 110\Worksheets)

### d ![2d)](C:\Users\Spaul\Documents\COMP 110\Worksheets)

## Question 3

### a 
|A | B | (A OR B) | NOT (A OR B)|
|:-|:-:|:--------:| -----------:|   
|F | F |    F     |      T      |   
|F | T |    T     |      F      |
|T | F |    T     |      F      |
|T | T |    T     |      F      |

|NOT A | NOT B | NOT A AND NOT B|
|:---- |:-----:| --------------:|   
|  T   |   T   |       T        |
|  T   |   F   |       F        |
|  F   |   T   |       F        |
|  F   |   F   |       F        |

### b 
|A | B | (A AND B) | NOT (A AND B)|
|:-|:-:|:---------:| ------------:|     
|F | F |    F      |     T        |
|F | T |    F      |     T        |
|T | F |    F      |     T        |
|T | T |    T      |     F        |

|NOT A | NOT B | NOT A OR NOT B|
|:-----|:-----:| -------------:|      
|  T   |   T   |       T       |
|  T   |   F   |       T       |
|  F   |   T   |       T       |
|  F   |   F   |       F       |

### c 
|A | B | C | (A AND B) | (A AND C) | (A AND B) OR (A AND C)|
|:-|:-:|:-:|:---------:|:---------:| ---------------------:|    
|F | F | F |    F      |     F     |          F            |
|F | F | T |    F      |     F     |          F            |
|F | T | F |    F      |     F     |          F            |
|F | T | T |    F      |     F     |          F            |
|T | F | F |    F      |     F     |          F            |
|T | F | T |    F      |     T     |          T            |
|T | T | F |    T      |     F     |          T            |
|T | T | T |    T      |     T     |          T            |

|(B OR C) | A AND (B OR C)|
|:--------|--------------:|    
|   F     |      F        |
|   T     |      F        |
|   T     |      F        |
|   T     |      F        |
|   F     |      F        |
|   T     |      T        |
|   T     |      T        |
|   T     |      T        |

### d 
|A | B | C | (A OR B) | (A OR C) | (A OR B) AND (A OR C)|
|:-|:-:|:-:|:--------:|:--------:|---------------------:|       
|F | F | F |    F     |     F    |           F          |
|F | F | T |    F     |     T    |           F          |
|F | T | F |    T     |     F    |           F          |
|F | T | T |    T     |     T    |           T          |
|T | F | F |    T     |     T    |           T          |
|T | F | T |    T     |     T    |           T          |
|T | T | F |    T     |     T    |           T          |
|T | T | T |    T     |     T    |           T          |

|(B AND C) | A OR (B AND C)|
|:---------|--------------:|    
|    F     |       F       |
|    F     |       F       |
|    F     |       F       | 
|    T     |       T       |
|    F     |       T       |
|    F     |       T       |
|    F     |       T       |
|    T     |       T       |

## Question 4

### a The progrmas in A are equivilent becasue NOT(A AND B) = NOT A AND NOT B. You can see the resemblance between that and the pair of programs. 

### b The pair of programs are the same in B becasue (A AND B) OR (A AND C) = A AND (B OR C). Further up the page, you can see why (A AND B) OR (A AND C) would give out the same values as A AND (B OR C).

### c The pair of programs will put out oposite answers becasue A AND B and NOT A OR NOT B will put out oposite answers. The programs would be the same as A AND B and NOT A OR NOT B if you replaced the x and y values with A and B. A AND B and NOT A OR NOT B can be shown in the truth table I have drawn up here: 
|A | B | A AND B|
|:-|:-:|-------:|      
|F | F |    F   |
|F | T |    F   |
|T | F |    F   |
|T | T |    T   |


|NOT A | NOT B | NOT A OR NOT B|
|:-----|:-----:|--------------:|
| T    |   T   |       T       |
| T    |   F   |       T       |
| F    |   T   |       T       |
| F    |   F   |       F       |

### d Ds pair of programs show that A Or (A AND B) will put out the same result as C AND (C OR D). Here is the truth table I drew up to show this:
|A | B | A AND B | A OR (A AND B)|
|:-|:-:|:-------:|--------------:|        
|F | F |    F    |       F       |
|F | T |    F    |       F       |
|T | F |    F    |       T       |
|T | T |    T    |       T       |

|C | D | C OR D | C AND (C OR D)|
|:-|:-:|:------:|--------------:| 
|F | F |    F   |        F      |
|F | T |    T   |        F      |
|T | F |    T   |        T      |
|T | T |    T   |        T      |


