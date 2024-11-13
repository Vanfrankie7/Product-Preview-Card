# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

This is a project built solely with HTML and CSS

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I built the it with Mobile first the did a media query for screen sizes above 768px

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I learned that when building a mobile-first layout and you change a 1 column grid which has an image on the first grid cell and text content on the second grid cell to a 2 column grid for larger screens, the image dont usually fit, the height get shorter and not fit the grid cell, to solve this, you increase the max-width of the grid-container and maybe, put height on the image to 100% in the image class itself (I chose not to in this project because it seemed to affect the aspect ratio)
See a Snippet:

.container {
grid-template-columns: 1fr 1fr;
margin-bottom: 2rem;
max-width: 69rem;
}

.img-desktop {
width: 100%;
display: block;
/_ height: 100%; _/
}

### Continued development

I am going to continue learning and expanding my knowledge

### Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@vanfrankie7](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@vanfrankie](https://www.twitter.com/yourusername)
#   P r o d u c t - P r e v i e w - C a r d  
 