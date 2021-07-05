# Frontend Mentor - Stats preview card component solution

This is CKodes's **second** solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). This solution was completed **without the use of Bootstrap framework**.

[The first submission to this solution utilized Bootstrap.](https://github.com/CKodes/FEM.StatsPreviewCardComponent_Bootstrap)

Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

#### Desktop Screenshot

<img width="1680" alt="Desktop" src="https://user-images.githubusercontent.com/78678795/124455344-0c9ae500-ddbc-11eb-8b4e-1a010a1691ce.png">


#### Mobile Page 1 Screenshot

<img width="372" alt="MobilePg1" src="https://user-images.githubusercontent.com/78678795/124455348-0efd3f00-ddbc-11eb-9a18-a4c27df980b9.png">


#### Mobile Page 2 Screenshot

<img width="376" alt="MobilePg2" src="https://user-images.githubusercontent.com/78678795/124455357-115f9900-ddbc-11eb-83c6-8452c4822482.png">

### Links

- [Frontend Mentor Solution Page](https://www.frontendmentor.io/solutions/stats-preview-card-component-qlCE8TBSN)
- [Live Site](https://ckodes.github.io/FEM.StatsPreviewCardComponent/)

## My process

### Built with

- HTML | CSS

### What I learned

- Prioritize media query for mobile wiew

Instead of working the site responsiveness from desktop to mobile view, I prioritized the media query for 375px first and then worked on the in-between widths.

- Centering

```css
body,
html {
  height: 100%;
  margin: 0;
  width: 100%;
}

.holder {
  box-sizing: border-box;
  height: 100%;
  min-height: 100%;
  overflow-x: hidden;
  overflow-y: hidden;
  padding: 10% 15%;
  width: 100vw;
}
```

- Better CSS formating

I grouped the CSS according to sections and arranged the properties in **alphabetic order**.

### Continued development

- Add dark mode toggle
- Refactor code. Alot of repetitive lines especially in CSS.

### Useful resources

[Centering to vh and vw](https://medium.com/developer-rants/what-if-height-100vh-is-bigger-than-your-screen-7f39c62ac170)

- I liked this solution on how to **center elements to 100vh and 100vw** by using **hidden overflows**;

## Author

- Frontend Mentor Profile [@CKodes](https://www.frontendmentor.io/profile/CKodes)

## Acknowledgments

Thank you to Dr. Angela Yu of [The App Brewery](https://www.appbrewery.co/) for [The Complete 2021 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) course and for introducing Frontend Mentor as a means to hone FE dev skills. This is my first Frontend Mentor challenge, and it was attempted after completing Lecture 84 - Media Query Breakpoints.
