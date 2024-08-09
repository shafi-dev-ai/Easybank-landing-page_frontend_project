# Easybank Landing Page

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [How to setup the project](#how-to-setup-the-project)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

The challenge is to create a landing page for Easybank, a modern bank promoting digital banking methods. Users should be able to-

- View the optimal layout for the site depending on their device's screen size.
- See hover states for all interactive elements on the page.

### How to setup the project

To set up the project locally, follow these steps:

1. Clone the repository using GitHub Desktop or Git Bash:
   ```bash
   git clone https://github.com/shafi-dev-ai/Easybank-landing-page_frontend_project.git
   ```
2. Open the project folder in your code editor.
3. Run the project using a live server extension or deploy it using Netlify, Vercel, or another web hosting and deployment service.

### Screenshot

![Design preview](/design/active-states.jpg)

### Links

- Solution URL: [Link to this repository](https://github.com/shafi-dev-ai/Easybank-landing-page_frontend_project)

## My process

### Built with

- HTML5
- CSS3
- JavaScript

You will find all the required assets in the `/images` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.

### What I learned

This project demands a good knowledge about CSS to execute the landing page as be as accurate relative to the design as possible. Knowledge about hover states executed as-

```
.nav-link:hover {
    background-size: 100% 4px, auto;
    cursor: pointer;
}
```

or knowledge about different states of same element on occurence of events-

```
#menu-toggle:checked+.menu-button-container .menu-button::before {
    margin-top: 0px;
    transform: rotate(405deg);
}

#menu-toggle:checked+.menu-button-container .menu-button {
    background: rgba(255, 255, 255, 0);
}

#menu-toggle:checked+.menu-button-container .menu-button::after {
    margin-top: 0px;
    transform: rotate(-405deg);
```

is crucial to make this project work.

### Continued development

The continuously learning journey of a programmer never ends. This project made me realize that there are many concepts that I need to work upon including fundamentals like flex-box and its properties, to more complex concepts like working with fetch and async await in javascript. These areas are some that I think I need to work more upon in the upcoming future as they highlight some of the most significant regions of web development that are important for every developer to know of.

These key points mentioned here will help me grow accountable and consistent towards improving at writing good quality code and be a successful full stack developer one day.

## Author

<b><strong>Shafi Habibi</strong></b>

## Acknowledgments

I feel like the solutions provided on the website and the continuous doubt solving by industry experts on discord for free is something that is unmatched by anyone else and need to be acknowledged for their efforts in improving me as a developer by suggesting the best practices in your respective tech stack.

## Got feedback for me?

I love receiving feedback! I am always looking to improve my code and take up new innovative ideas to work upon. So if you have anything you'd like to mention, please email 'hi' at shafihabibiwork@gmail.com.

If you liked this project make sure to spread the word and share it with all your friends.

**Happy coding!** ☺️🚀
