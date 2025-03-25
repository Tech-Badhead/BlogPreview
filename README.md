# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Live Site URL: https://tech-badhead.github.io/BlogPreview/

### Built with

- Semantic HTML5 markup
- Flexbox
- Desktop-first workflow

### What I learned

I learnt about structuring content on the web page which is where the css width and max-width comes in handy for this project. What really stood out for me in this project was the clamp property which allows to reduce font size smoothly for smaller screens without using media queries.

```css
proud-of-this-css html {
  font-size: clamp(14px, 1vw, 24px);
}

#main {
  box-shadow: 3px 2px 0 3px #000;
}
```

### Continued development

Going forward i really want to improve on how to structure content on web page efficiently, writing semantic html, accessibility best practice, as well as working with responsiveness

### Useful resources

- ChatGPT! it helped me with the clamp property because this project was my first time using the property, hopefully first of many.

## Author

- Frontend Mentor - [usman frontend 360] https://www.frontendmentor.io/profile/Tech-Badhead
- Twitter - [usman_Dev] https://x.com/AkeemUsman10482

## Acknowledgments

All credits goes to usman for his never ending curiosity!
