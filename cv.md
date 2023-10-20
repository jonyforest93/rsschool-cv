# Yauheni Struneuski

---

![avatar](https://firebasestorage.googleapis.com/v0/b/opiniosphere.appspot.com/o/CV_avatar.jpeg?alt=media&token=2647f3da-60d9-4a29-b1c1-6d776bdcb6bd&_gl=1*npqa50*_ga*MTU5NjU3NjQwMC4xNjk0Njg0MzA5*_ga_CW55HF8NVT*MTY5NzgxMzgzNC4yOS4xLjE2OTc4MTM5OTAuNTEuMC4w)

## Junior Frontend Developer

---

### Contact information:

**Phone:** +375 44 7501619
**E-mail:** y.struneuski@gmail.com
**Telegram:** @eugenenutt
[Git](https://github.com/jonyforest93)

---

### Briefly About Myself:

I am a Frontend Developer with a passion for creating interactive and efficient
user interfaces using modern technologies and best development practices.

---

### Skills and Proficiency:

**Front-end:** HTML/CSS, JavaScript, React, Tailwind, Bootstrap
**Back-end:** Node.js, express, mongodb, REST
**Web design:** Figma, Photoshop

---

### Code Example

**An example of solving a problem from the codewars website:** In a string of numbers, find the odd values ​​in the odd places

```
function findOddInOddPlace(str) {
    if (str.length == 0) {
        return "";
    }
    if (str.length % 2 == 0) {
        return findOddInOddPlace(str.slice(0, -1));
    }
    if (parseInt(str[str.length - 1]) % 2 == 0) {
        return findOddInOddPlace(str.slice(0, -1));
    } else
        return `${findOddInOddPlace(str.slice(0, -1))} ${
            str[str.length - 1]
        } in place (${str.length});`;
}
```

---

### Experience

**ITransition trainee** (**_July 2023 - September 2023_**)

-   Creating and deploying a complete web application covering both server-side and client-side components.
-   Server-Side Development:
    -   Writing routes and controllers using Node.js and Express.js to handle HTTP re quests;
    -   Working with MongoDB for creating and managing data models.
-   Database Modeling in MongoDB:
    -   Designing and creating data models for efficient data storage and manipulation in MongoDB ;
    -   Working with schemas and data migrations to ensure data integrity and security.
-   Client-Side Development using React:
    -   Building an interactive user interface with React, including components and routing ;
    -   Interacting with the server-side through APIs for data transmission and retrieval;
    -   Optimizing performance and ensuring a great user experience (UX).

[pet project](https://opnio-sphere.onrender.com/)

[certificate](https://firebasestorage.googleapis.com/v0/b/opiniosphere.appspot.com/o/Yauheni%20Struneuski%20-%20Front-end%20-%20Sep%2029th,%202023.pdf?alt=media&token=a732cad3-7d08-451d-8ca8-9e33c63222cb)

---

### Courses

-   RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
-   JavaScript Manual on learnjavascript.ru (in progress)
-   HTML Academy

### Languages

-   English - A2
-   Russian - native
