<img  height="50px" align="right" src="https://raw.githubusercontent.com/fchavonet/fchavonet/main/resources/images/logo-holberton_school.png" alt="Holberton School logo">

# Implement a design from scratch

<details>
        <summary>
        CLICK TO ENLARGE 😇
        </summary>
        📄 <a href="#description">Description</a>
        <br>
        🎓 <a href="#objectives">Objectives</a>
        <br>
        📋 <a href="#requirements">Requirements</a>
        <br>
        📝 <a href="#instructions">Instructions</a>
        <br>
        🔨 <a href="#tech-stack">Tech stack</a>
        <br>
        📂 <a href="#files-description">Files description</a>
        <br>
        ♥️ <a href="#thanks">Thanks</a>
        <br>
        👷 <a href="#authors">Authors</a>
</details>

## 📄 <span id="description">Description</span>

In this project, I am tasked with building a web page entirely from scratch, without relying on any external libraries. This challenge requires me to apply all the HTML, CSS, Accessibility, and Responsive Design knowledge that I have acquired so far. The project gives me creative freedom, with minimal instructions, allowing me to design and implement the page according to my own approach.

If you want to directly see the final result of all the project tasks, you can click [here](https://fchavonet.github.io/holbertonschool-headphones/101-index.html).

## 🎓 <span id="objectives">Objectives</span>

The primary objective of this project is straightforward: to develop a fully functional web page that faithfully replicates the appearance of the provided designer file. The goal is to ensure that the final product not only meets the visual specifications but also adheres to best practices in web development, ensuring accessibility and responsiveness across different devices and screen sizes.

Here the final result:

<img src="./resources/images/mockup.png" alt="Mockup">

This webpage has been designed by Nicolas Philippot, UI/UX designer.

## 📋 <span id="requirements">Requirements</span>

- you are not allowed to import external CSS framework (like Bootstrap).
- you are not to use Javascript.

## 📝 <span id="instructions">Instructions</span>

<details>
    <summary>
        <b>0. Read and be familiar with Figma</b>
    </summary>
    <br>

Create an account in Figma and open the project and “Duplicate to your Drafts” to have access to all design details.

If you can’t access to it, please find here the Figma [file](https://intranet.hbtn.io/rltoken/tWEPFyHyXyNO9Xfi2Er2EA).

<img src="./resources/images/figma.png" alt="Figma">

Important notes with Figma:

- If your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro) and [Spin-Cycle-OT](https://www.fontsquirrel.com/fonts/Spin-Cycle-OT).
- Some values are in float - feel free to round them.

For this task, please write an amazing README.md

**Interactions note:**

- The web page must switch to the mobile version when the screen width is 480px or less.
- Links hover/active: `#FF6565`.
- Button hover/active: `opacity: 0.9`.
- Max width of the content: 1000px centered in the page.

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `README.md`.
<hr>
</details>

<details>
    <summary>
        <b>1. Header</b>
    </summary>
    <br>

Building a web page the right way, is not easy - expect if you put in place strong foundations:

- Reset CSS styling.
- Use variables.
- Simple/"as generic as you can" CSS selectors.
- Avoid using super specific CSS selectors as much as possible.
- Simple HTML structure - `div` containers are your friend!

Last advice: personally, I always start to build a web page from outside to inside and from top to bottom. But you can try to other way - it’s fine - but you should structure the way that you will implement a component and not get lost with HTML tags.

Now, your turn!

For this first task: **create the header/hero piece**.

Here an archive of all assets needed: [images_.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/d1597894d79386c83b9b.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240817%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240817T073300Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=a6b681a3e20d06596441650e5838b11e32fe32629c582bb88864ade0902a5086).

**Desktop:**

<img src="./resources/images/task0-desktop.gif" alt="Desktop version of Header screenshot">

**Mobile:**

<img src="./resources/images/task0-mobile.gif" alt="Mobile version of Header screenshot">

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `0-index.html`, `0-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>2. "What we do..." section</b>
    </summary>
    <br>

Copy files from the previous task.

For this second task: **create the “What we do…” section**.

In this section, you will need custom font icons. Here the archive of it: [holberton_school-icon.zip](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240817%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240817T073300Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=d05e0f6a8813cbe98a40f0f3779004dfca04a4ceaab818a900c5174daa3df064) Inside you will find demo page of how to use it.

**Important:** try to build as generic as you can… you will probably need some components in next section.

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `1-index.html`, `1-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>3. "Our results" section</b>
    </summary>
    <br>

Copy files from the previous task.

For this third task: **create the “Our results” section**.

Now you can reuse components form the previous task!

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `2-index.html`, `2-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>4. Contact us</b>
    </summary>
    <br>

Copy files from the previous task.

A good landing page has always a contact form.

You are free to add any animations and/or constraints on fields.

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `3-index.html`, `3-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>5. Footer</b>
    </summary>
    <br>

Copy files from the previous task.

Last piece of the page… The Footer!

When you are done, here the result:

**Desktop:**

<img src="./resources/images/task5-desktop.gif" alt="Desktop version of Footer screenshot">

**Mobile**

<img src="./resources/images/task5-mobile.gif" alt="Desktop version of Footer screenshot">

And you are done!

**Good job!**

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `4-index.html`, `4-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>6. Replace background image with... code!</b>
    </summary>
    <br>

In the section "Our results"; without the use of an image file, draw each pentagon using HTML and CSS.

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `100-index.html`, `100-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>7. Let's animate items</b>
    </summary>
    <br>

From `4-index.html` and `4-styles.css`, add fun animations to "What we do…" and "Our results" sections items row. Either all the time, either when hover.

Scaling, opacity, rotation, bouncing… Many options!

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `101-index.html`, `101-styles.css`.
<hr>
</details>

<details>
    <summary>
        <b>8. And SASS??</b>
    </summary>
    <br>

Take your `101-styles.css` file and create a `102-styles.scss` that will be the SASS version of it.

```
$ sass 102-styles.scss > 102-styles.css
```

#
**Repo:**
- GitHub repository: `holbertonschool-headphones`.
- File: `102-index.html`, `102-styles.scss`.
<hr>
</details>

## 🔨 <span id="tech-stack">Tech stack</span>

<p align="left">
    <img src="https://img.shields.io/badge/HTML5-e34f26?logo=html5&logoColor=white&style=for-the-badge" alt="HTML5 badge">
    <img src="https://img.shields.io/badge/CSS3-1572b6?logo=css3&logoColor=white&style=for-the-badge" alt="CSS3 badge">
    <img src="https://img.shields.io/badge/SASS-cc6699?logo=sass&logoColor=white&style=for-the-badge" alt="SASS badge">
</p>

## 📂 <span id="files-description">File description</span>

| **FILE**          | **DESCRIPTION**                                                           |
| :---------------: | ------------------------------------------------------------------------- |
| `resources`       | Contains the fonts and images required for the page.                      | 
| `0-index.html`    | Index page for the task `1. Header`.                                      |
| `0-styles.css`    | CSS style sheet for the task `1. Header`.                                 |
| `1-index.html`    | Index page for the task `2. "What we do..." section`.                     |
| `1-styles.css`    | CSS style sheet for the task `2. "What we do..." section`.                |
| `2-index.html`    | Index page for the task `3. "Our results" section`.                       |
| `2-styles.css`    | CSS style sheet for the task `3. "Our results" section`.                  |
| `3-index.html`    | Index page for the task `4. Contact us`.                                  |
| `3-styles.css`    | CSS style sheet for the task `4. Contact us`.                             |
| `4-index.html`    | Index page for the task `5. Footer`.                                      |
| `4-styles.css`    | CSS style sheet for the task `5. Footer`.                                 |
| `100-index.html`  | Index page for the task `6. Replace background image with... code!`.      |
| `100-styles.css`  | CSS style sheet for the task `6. Replace background image with... code!`. |
| `101-index.html`  | Index page for the task `7. Let's animate items`.                         |
| `101-styles.css`  | CSS style sheet for the task `7. Let's animate items`.                    |
| `102-index.html`  | Index page for the task `8. And SASS??`.                                  |
| `102-styles.scss` | SASS file for the task `8. And SASS??`.                                   |
| `README.md`       | The readme file you are currently reading 😉.                             |

## ♥️ <span id="thanks">Thanks</span>

A big thank you to all my Holberton School peers for their help and support throughout these projects.

## 👷 <span id="authors">Authors</span>

**Fabien CHAVONET**
- Github: [@fchavonet](https://github.com/fchavonet)
