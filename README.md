# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### Screenshot

![](./screen.png)


### Built with

- Flexbox
- Media Queries
- JavaScript DOM
- Multiple Background Images

### What I learned

- Using CSS Flexbox
- Using Media Queries
- Add Elements to the DOM via JavaScript
- Create Backgrounds with multiple Images
- Positioning of multiple Background Images


### Code snippets

```css
/* Extra small devices (phones, 950px and down) */
@media only screen and (max-width: 500px) {
  /* ... */
}

/* multiple background images and positioning of them */
.wrapper {
    background-color: var(--dark-cyan);
    background-image: url(images/bg-pattern-top.svg), url(images/bg-pattern-bottom.svg);
    background-position: -320px -490px, 690px 379px;
    background-size: 1000px;
    background-repeat: no-repeat;
}
```

```js
// create an image with JavaScript
const image = document.createElement("img"); 
const box_top = document.querySelector(".box_top");
image.setAttribute("id", "image_victor");
image.setAttribute("src", "images/image-victor.jpg")
image.setAttribute("title", "An image that shows Victor");
box_top.insertBefore(image, box_top.firstChild);
```