# Natallia Motuz

_**Junior Software Engineer**_

**Adress:** Minsk, Belarus
**Email:** natalia.motuz@gmail.com
**Telegram:** @natalkamotuz

## Summary of Qualifications

>I am in the earlier stage of my journey as a software developer, have a small yet delightful portfolio of launched projects, and I’m hungry to learn more.

## Technical skills
* HTML - 8/10
* CSS - 7/10
* JavaScript - 2/10
* ReactJS - 1/10

>As a junior developer, I am able to craft clean and correct code with some supervision and guidance. Also I can execute on well specified or documented tasks by breaking them down into reasonable subtasks, and complete them.

## Code Example
``` javascript
module.exports = function solveEquation(equation) {
    const parsedEquation = equation.split(' ');
    const op1 = parsedEquation[3];
    const op2 = parsedEquation[7]; 
    const a = parsedEquation[0];
    const b = parsedEquation[4] * (op1 === '-' ? - 1 :1 );
    const c = parsedEquation[8] * (op2 === '-' ? - 1 :1 );
    const D = Math.sqrt(b * b - 4 * a * c);
    const x1 = Math.round((-b + D) / (2 * a));
    const x2 = Math.round((-b - D) / (2 * a));
  
    return [x1, x2].sort(function (a, b) {return a - b};
};
``` 

## Education
* _2008-2010_ MA in Belarusian Linguistics, University of Warsaw, Poland
* _2008-2010_ BA in Visual Cultural Studies, University of Warsaw, Poland
* _2003-2006_ Belarusian State Pedagogical University, Belarusian Linguistics

## Informal Education
**Basics of Computer Science**, IT-Academy, 2017

**Website development using HTML, CSS & Javascript**, IT-Academy, 2020

**Online courses:** Basic course in Java programming, The Basics of Object Oriented Programming, Database, Regular expressions.

## English skills
I have successfully completed a 160-hours General English course at the **Intermediate level** in Streamline Language School.

[![github account](assets/hub.png)](https://github.com/nataliamotuz)