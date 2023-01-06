# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202023-01-06%20at%201.13.18%20AM.png)
![](./images/Screenshot%202023-01-06%20at%202.26.11%20AM.png)

### Links

- Solution URL: [My GitHub](https://github.com/VSandwar74/nft-preview-card-component-main)
- Live Site URL: [My Live Site!](https://stellular-youtiao-ec7322.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```css
.overlay {
    width: 300px;
    height: 300px;
    border-radius: 10px;
    cursor: pointer;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    opacity: 0;
} 
.green {
    width: 100%;
    height: 100%;
    border-radius: 10px;
    background-color: #15F7F3;
    opacity: 0.5;
}
.eye {
    position: absolute;
    height: 48px;
    width: 48px;
}
.nftpic {
    position: absolute;
    width: 300px;
    height: 300px;
    align-self: center;
    border-radius: 10px;
    cursor: pointer;
    opacity: 1;
    display: block;
}
.overlay:hover {
    opacity: 1;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Position Absolute Guide](https://www.geeksforgeeks.org/how-to-stack-elements-in-css/) - This really helped me tackle the overlay task, I think I never fully grasped absolute.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Vishakh Sandwar](https://www.your-site.com)
- Frontend Mentor - [@VSandwar74](https://www.frontendmentor.io/profile/VSandwar74)

