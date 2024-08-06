# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [frontend mentor solution](https://www.frontendmentor.io/solutions/3-column-preview-card-component-solution-CbSw8u1AGA)
- Live Site URL: [website](https://hanifanwary.github.io/3-column-preview-card-component-main/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

During this project, I gained a deeper understanding of how to structure a responsive web layout using Flexbox. One key learning was the implementation of media queries to adjust the layout based on screen size. For example, I used the following code to change the flex direction from row to column on smaller screens:

css
@media (max-width: 640px) {
  .card {
    flex-direction: column;
  }
}

This ensures that the cards stack vertically on smaller devices, enhancing the user experience.

Additionally, I improved my skills in customizing buttons and applying hover effects. The following code snippet shows how I styled the buttons and added a hover effect:

.btn {
  width: 130px;
  height: 40px;
  border: 2px solid white;
  border-radius: 45px;
  transition: all 0.3s;
  cursor: pointer;
  background: hsl(0, 0%, 95%);
  font-size: 1em;
  font-weight: 550;
  font-family: "Lexend Deca", sans-serif;
}

.btn:hover {
  color: black;
  font-size: 1.2em;
}


### Continued development

In future projects, I plan to continue focusing on improving my responsiveness skills and mastering CSS Grid for more complex layouts. I also aim to enhance my JavaScript skills to add more interactivity to my projects.


## Author

- Frontend Mentor - [@hanifanwary](https://www.frontendmentor.io/profile/@hanifanwary)
- Instagram - [@hanifanwary17](https://www.Instagram.com/@hanifanwary17)


## Acknowledgments

I would like to thank the developers and designers whose resources and tutorials inspired me to complete this project. Special thanks to the online communities and forums where I found valuable tips and support.

