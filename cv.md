![avatar](avatar.jpg)
___

#Eugene Degtyaryov
## Frontend developer

- __Contacts__
    - [GitHub](https://github.com/disroland)
    - [Linkedin](https://www.linkedin.com/in/%D0%B5%D0%B2%D0%B3%D0%B5%D0%BD%D0%B8%D0%B9-%D0%B4%D0%B5%D0%B3%D1%82%D1%8F%D1%80%D0%B5%D0%B2-639036175/)
    - ___E-mail___: disroland@gmail.com
    - ___Discord:___ Eugene Degtyaryov (disroland)

## Profile:
_Junior front-end developer with knowledge in HTML, CSS, JavaScript.
Also  I worked as system administrator, so I have experience with Unix-
based operation systems, network supply and technical support of users._

##Skills: 
- HTML5, CSS3, SCSS(SASS), JavaScript, Jquery, Gulp, Adobe Photoshop, Vue.js

## Employment Hystory:
- 2001 - 2019 - Technical support engineer at Variant-95;
- 2019 - 2021 - System administrator at Variant-95

## Education:
1996 - 2000 - Kharkiv college of medical equipment - associate degree

## Courses:
- 2005 - IT-biz - Linux administration;
- 2017-2020 - Interlink - English;
- 2019-2020 - Beetroot Academy - Front-end development
- 2022 - Creative Practice - Design, Photoshop

## Languages:
- Russian (native)
- Ukrainian (native)
- English - Upper Intermediate (b2)

## Hobbies:
Hiking, reading, photography, cyclyng

## Code example:
### Task from Codewars
__Task:__  _I was given a string of space separated numbers, and had to return the highest and lowest number_

___

__Solution:__
```
function highAndLow(numbers) {
  let arr = numbers.split(' ').sort((a, b) => a - b);
  let max = arr.pop()
  arr.push(max)
  let min = arr.shift()
  let res = `${String(max)} ${String(min)}`
  return res
}
```