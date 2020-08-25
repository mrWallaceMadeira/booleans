# Boolin'
This lesson will cover a new variable type: `boolean`\
`boolean` values are either true or false, simple as that.\
bools, as they're more commonly known will be our gateway to more interesting programming

### Starting to look familiar...
Just like `String`s and `Scanner`s, `boolean`s are declared and initialized the same way.\
Like this &nbsp;:arrow_down:\
`boolean myBoolean = true;`

### Boolean comparisons: yes or no?
If boolean variables can hold true or false, we need a way to "ask" the computer about the truth values.\
Think of the following like yes/no questions in English\
We ask these "questions" with comparison operators&nbsp;:arrow_down:
  - [x] `x == y` means does x = y?
  - [x] `x != y` means does x ≠ y?
  - [x] `x > y` means is x > y?
  - [x] `x < y` means is x < y?
  - [x] `x >= y` means is x ≥ y? (i.e. greater than or equal to)
  - [x] `x <= y` means is x ≤ y? (i.e. less than or equal to)
  
All of these operators will **return** a boolean value\
Meaning you can initialize a new bool witht these operations like this: `boolean theResult = 0 == 0`
  - `theResult` should be true given that the question "Does 0 = 0?" can be answered with yes.
  - `true` is how we answer with Java

### One step further
We've stated that comparison operators "return" a value of true or false.\
To create more complex statements, we can combine them with these operators: `&&` and `||`\
For example &nbsp; :arrow_down:
```
  boolean isTrue = (1 == 1) && (2 == 2);
  boolean isFalse = (1 == 2) && (2 == 2);
  boolean isTrue2 = (1 == 2) || (2 == 2);
  boolean isFalse2 = (1 == 2) || (1 == 2);
```

`||` is known as a logical or
  - it evaluates to true if _one or both_ sides of the operator are true

`&&` is known as a logical and 
  - it evaluates to true only if _both_ sides of the operator are true

### :hand:&nbsp;Stop!
Watch [this](https://themadeiraschool.sharepoint.com/sites/IntrotoCS/Shared%20Documents/General/Videos/lesson7Video1.mov)

### C'est fini
Entry ticket [here](https://forms.office.com/Pages/ResponsePage.aspx?id=P9fbuiFvgkyZJ5ogeV5C0bXAAGShYuhAq0O_bKHZJnxUN05YRlBPRkRPODRBMDRLMVdQQ1ZKS1g4USQlQCN0PWcu)


  
