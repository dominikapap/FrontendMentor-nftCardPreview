# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
This is a screenshot of a basic view:  
![](/screenshots/basic.PNG)

This one is with hover states:  
![](/screenshots/hover.PNG)

Solution and design comparison:  
![](/screenshots/designComparison.png)

### Links

- Solution URL: [GitHub repository](https://github.com/dominikapap/nftCardPreview)
- Live Site URL: [NFT Card Preview on Netlify](https://dominikapap-nft-card-preview.netlify.app/)


### Built with

- Semantic HTML5 markup
- SCSS,CSS custom properties
- Flexbox
- AWD



### What I learned

How to show elements with different opacity on hover and change one element while hovering over a different one.



```css
.overlay:hover{
  opacity: 0.4;
}

#icon{
  position: absolute;
  top:35%;
  z-index:-1;
}
.overlay:hover + #icon{
  z-index: 2;
}

```

## Author

- Linkedin - [My LinkedIn profile](https://www.linkedin.com/in/dominika-papierska-1ba09311a/)
- Frontend Mentor - [@dominikapap](https://www.frontendmentor.io/profile/yourusername)
- Email - domi.papierska@gmail.com

