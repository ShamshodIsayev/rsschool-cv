# Shamshod Isayev

Frontend web developer

## Contacts

- Email: <abdushamshod@gmail.com>
- Telegram: <https://t.me/alwaystrybest>
- LinkedIn: [shamshodisayev](https://www.linkedin.com/in/shamshod-isayev-b58391215/)
- Facebook: [shamshodisayev](https://www.facebook.com/shamshod.isayev/)
- Tel: +998933924261

## About

Curios developer from Tashkent. Trying to implement people's unusual , wondrous wishes in Web development

## Skills

- HTML5
- CSS3
- Javascript
- jQuery
- Vue.js
- VueX
- Vue-Router
- Bootstrap
- Vue-Bootstrap
- Webpack
- Wordpress(basic)

## Experience

> 2020-2021 Letcop company as a Frontend developer

## Education

> 2020-2021 Proweb IT-Center (GED)
> 2021 Udemy course (Frontend dev.)

## English

English level - B1

Some code from Codewars

> 6 kyu Find the odd int

```
function findOdd(A) {
    let count = {};
    for (let i = 0; i < A.length; i++) {
        let num = A[i];
        if (count[num]) {
            count[num] = count[num] + 1;
        } else {
            count[num] = 1;
        }
    }
    let result = 0;
    for (let number in count) {
        if (count[number] % 2 != 0) {
            result = number;
        }
    }
    return parseInt(result); // since object properies are strings
}
```
