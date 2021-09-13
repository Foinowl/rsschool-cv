# Evgeniy Edvabinskiy

### Contact information
City: Glazov
Phone: +79925267420
Telegram: +79925267420
E-mail: edvabinskij@yandex.ru
Discord: Evgeniy Edvabinkiy (@Foinowl)
GitHub: https://github.com/Foinowl

### Summary
At the moment I work as a junior specialist of SAP BI.

My main goal is to become a confident Junior Frontend Developer in order to get a job at Epam and develop in this company, gaining experience from qualified specialists.

During an internship at "Greenatom", I had to constantly study a new direction for myself and evolve in it, while performing tasks, I always writed the key steps for the implementation of the task strictly on time. I communicated and helped other interns to complete tasks, explained incomprehensible topics.

I want to deepen my knowledge in English and reach the B2 level.


### Technical Skills
*	HTML5, CSS3, SCSS
*	React
*	JavaScript, Python, C#
*	Git, GitHub
*	VsCode

### Example Code

Build a function sumNestedNumbers/sum_nested_numbers that finds the sum of all numbers in a series of nested arrays raised to the power of their respective nesting levels. Numbers in the outer most array should be raised to the power of 1.

```js script
function sumNestedNumbers(arr) {
  return sumNested(arr, 1)
}

const sumNested = (arr, dep = 1) => {
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    if (Array.isArray(arr[i])) {
      sum += sumNested(arr[i], dep + 1);
    } else {
      sum += Math.pow(arr[i], dep);
    }
  }
  return sum; 
};

sumNestedNumbers([1, [2], 3, [4, [5]]]) // --- > 1 + 2*2 + 3 + 4*4 + 5*5*5 === 149
```

### Working experience
Greenatom
Junior specialist
*August 2021 – Current time*  
Responsibility: Implementation of archived data sources. Support for the current functionality.

Greenatom
Trainee
*May 2021 – August 2021*  
Responsibility: Studying the creation of BW repositories, reporting in Analysis for Excel, immersion in the basis of OLAP systems and their creation.

### Education
* Glazov branch of Kalashnikov Izhevsk State Technical University(2018 – current time), Programmer, Faculty of Information Systems

### Languages
* English - A1-A2.