# Reducing-WTFs-Per-Minute
![WTFM](http://www.osnews.com/images/comics/wtfm.jpg)

---
>  High quality code should not surprise us. We should be able to quickly and easily discern the structure and intent of the code.



## Description
> But doesn’t this then place software quality in the eyes of the beholder? What if the person evaluating the code isn’t familiar with the patterns used by the original developer? (Or – to be more cruel – what if they just aren’t competent enough to recognize the patterns used?) Are they not likely to harshly judge the code based on miscomprehension? (A similar suggestion to this measure is that software quality is inversely related to the amount of time required to make a modification; again the major problem with this is that it depends on the capability of the person making the change).
- Abstract from [on-code-quality](http://ogsa-dai.sourceforge.net/blog/2011/08/22/on-code-quality/)


## Criteria
How to analyse software quality?

- Readability. Is the source code legible? Is it correctly formatted and idiomatic?

- Patterns. Has the author used common patterns where appropriate? Similarly, have they avoided anti-patterns? 
- Testability. Are there unit tests? How much coverage? How hard would it be to add such tests? 
- Data structures(Algorithms). 
Are the data structures used appropriate for the code? Are they at the correct level of abstraction? Use appropriate algorithms.

- Changeability. How hard is it to make changes to the codebase? Is it modular? How difficult would it be to change an algorithm or data structure? 
- **Simplicity**
Does the code avoid unnecessary complexity? Is it concise without being obfuscated?


## Simplicity
> Shorter code is easier to understand and debug

- DIY
- OOP / MVC
- SOLID
- Use Framework or not (correctly)?

## Common Design Pattern
* Design Pattern
    - [design-patterns-for-humans](https://github.com/kamranahmedse/design-patterns-for-humans)
    - [大叔深入javascript系列](http://www.cnblogs.com/TomXu/archive/2011/12/15/2288411.html) 

* Javascript
    - [Getify: Functional](https://github.com/getify/Functional-Light-JS)
    - [Getify: You don't know Javascript](https://github.com/getify/You-Dont-Know-JS)
    - [Dmitry: ECMA3 & 5](http://dmitrysoshnikov.com/)

    
* Clean Code:
    - [Clean Code for Javascript](https://github.com/ryanmcdermott/clean-code-javascript)
    - [Martin Flower: Refactor](https://martinfowler.com/books/#refactoring)


## References
- https://www.software.ac.uk/blog/2016-10-06-wtfsmin-indicator-code-quality
- https://www.42lines.net/2012/07/06/clean-code-reducing-wtfs-per-minute/


