# Ekaterina Chistyakova

## Frontend developer | Javascript

---

email: thekatrin@bk.ru

linkedin: [https://www.linkedin.com/in/ekaterina-chistyakova/](https://www.linkedin.com/in/ekaterina-chistyakova-930bb1237/)

githab: [https://github.com/katriosa](https://github.com/katriosa)

---

## About me

An aspiring frondend developer.

## Technical skills

HTML, CSS, JAVASCRIPT

## Experience

Forkify project

## Education

__2010 - 2014__ State University of Aerospace Instrumentation.

- Faculty of Innovation

__2021 - 2022__ Udemy. 

- The Complete JavaScript Course 2022: From Zero to Expert.

__2022 - present__ RS school. 

- JavaScript/Front-end 2022

## Language

Russian: native

English: pre-intermediate

## Example code

_Task: Return the number (count) of vowels in the given string._

_We will consider a, e, i, o, u as vowels for this Kata (but not y)._

_The input string will only consist of lower case letters and/or spaces._

```javascript
function getCount(str) {
  let vowelsCount = 0;
  const counts = ["a", "e", "i", "o", "u"];
  str.split("").forEach(function (letter) {
    counts.includes(letter) ? vowelsCount++ : vowelsCount;
  });
  return vowelsCount;
}
```
