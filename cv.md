# Artsiom Trafimiuk

# Contact information

* **Location:** Portugal
* **Email:** <a href="mailto:algatecby@gmail.com" target="_blank">algatecby@gmail.com</a>
* **Linkedin:** <a href="https://www.linkedin.com/in/artsiom-trafimiuk/" target="_blank">Artem Trafimiuk</a>
* **Github:** <a href="https://github.com/Temons" target="_blank">Github</a>
* **Telegram:** <a href="https://t.me/artstrfm" target="_blank">@artstrfm</a>

# Summary

As an experienced front-end developer with a solid 5 -year background, I specialize in creating efficient and user-engaging web applications. My proficiency extends across key technologies like JavaScript, React, Redux, and TypeScript. I am committed to excellence in coding, adhering to best practices for maintainability and performance. Continually enhancing my skills through ongoing education, I am equipped to tackle complex challenges in web development.

# Skills

* JavaScript
* TypeScript
* HTML5
* CSS3
* React
* AngularJS
* Angular2+
* JQuery
* Redux
* Next.js
* Redux Toolkit
* Redux Thunk
* RTK Query
* React Query
* Axios
* i18next
* Jest
* React-testing-library
* Storybook
* Webpack
* Vite
* bootstrap

# Code examples

```js
/**
 * @param {string} s
 * @param {string} t
 * @return {boolean}
 */
var isIsomorphic = function(s, t) {
    const helperS = {};
    const helperT = {};

    for (let i = 0; i < s.length; i++) {
        const letterS = s[i];
        const letterT = t[i];

        if (helperS[letterS] && helperS[letterS] !== letterT) {
            return false
        }

        if (helperT[letterT] && helperT[letterT] !== letterS) {
            return false
        }

        helperS[letterS] = letterT;
        helperT[letterT] = letterS;
    }

    return true;
};
```

```js
/**
 * @param {number[]} nums1
 * @param {number[]} nums2
 * @return {number[]}
 */
var intersect = function(nums1, nums2) {
    const result = [];
    nums1.forEach(item => {
        const target = nums2.indexOf(item);
        if (target !== -1) {
            result.push(item);
            nums2.splice(target, 1);
        }
    })

    return result;
};
```

# Experience

* **LIFETECH (TURKCELL GROUP)**
    * Software Engineer 03.2021 - 08.2024
* **ABF PROGRAMMING**
    * Software Engineer 03.2020 - 03.2021
* **TEGRO.BY**
    * Software Engineer 03.2019 - 02.2020
* **FREELANCE**
    * Layout Engineer 01.2018 - 02.2019
    * Here was basically training — taking the initial courses, freelance projects that I had in the first 2 years, while constantly learning and improving my skills.

# Education

* **Bachelor's degree, Belarusian National Technical University, Minsk**
    * Faculty of Management Technologies and Humanities.
    * Energy efficient technologies and energy management (UNESCO)
* **Advanced Frontend Development**
    * <a href="https://ulbitv.ru/frontend" target="_blank">ulbitv.ru</a>

# Languages
* **English - B2**
    * Over 2 years of experience working in English-speaking teams, currently in my third year living and communicating in an English-speaking environment.


