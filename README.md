# Reducing-WTFs-Per-Minute
![WTFM](http://www.osnews.com/images/comics/wtfm.jpg)


## Description
High quality code should not surprise us. Instead, we should be able to quickly and easily discern the structure and intent of the code.

Admittedly, the rationality of code structure plays an important role in code review. If the structure of your code is messed up, you will probably end up with bad reputations together with your code. But what if the person evaluating code isn’t familiar with the patterns used by the original developer, and what if all delicate patterns therein displayed are blind for them, in this case they are likely to harshly judge the code based on miscomprehension. 

Therefore, we need to reach some consensuses at the code level, which I am going to talk about in detail.


## Criteria
How to analyze code quality?

- Readability. 
Is the source code legible? Is it correctly formatted and idiomatic?

- Patterns. 
Has the author used common patterns where appropriate? Similarly, have they avoided anti-patterns?

- Testability. 
Are there unit tests? How much coverage? How hard would it be to add such tests?

- Data structures(Algorithms). 
Are the data structures used appropriate for the code? Are they at the correct level of abstraction? Use appropriate algorithms.

- Changeability. 
How hard is it to make changes to the codebase? Is it modular? How difficult would it be to change an algorithm or data structure?

- **Simplicity**.
Does the code avoid unnecessary complexity? Is it concise without being obfuscated?


## Simplicity
Simplicity is both the goal and the key to solving the problem of Reducing WTFs/Minute. And shorter code turns out to be easier to understand and debug.

- DRY
- SOLID: React / SDK
- MVC / MVVM
- Functional & OOP
- Use Framework correctly(or not use)?


## Common Design Pattern

* Design Pattern
    
    **Creational**: (Abstract)Factory, Singleton, Prototype
    
    **Structural**: Adaptor, Composite, Proxy, Decorator
    
    **Behavioral**: Observer(Sub/Pub), Iterator, Strategy(predicate)

    - [design-patterns-for-humans](https://github.com/kamranahmedse/design-patterns-for-humans)
    - [TomXu: Dive into Javascript series](http://www.cnblogs.com/TomXu/archive/2011/12/15/2288411.html) 

* Javascript
    - [Getify: Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS)
    - [Getify: You don't know Javascript](https://github.com/getify/You-Dont-Know-JS)
    - [Dmitry Soshnikov: ECMA-262-3,5 & Interpretation](http://dmitrysoshnikov.com/)

    
* Clean Code & Refactor:
    - [Clean Code for Javascript](https://github.com/ryanmcdermott/clean-code-javascript)
    - [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
    - [Martin Flower: Refactor](https://martinfowler.com/books/#refactoring)


## References
- https://www.software.ac.uk/blog/2016-10-06-wtfsmin-indicator-code-quality
- https://www.42lines.net/2012/07/06/clean-code-reducing-wtfs-per-minute/


