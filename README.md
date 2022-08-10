# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)


## Overview
This is my initial solution to the QR Code component. The initial time given to the code was a day. This is because I am new to coding and thought that a lot of code would need to be researched. Luckily this was not the case and I was able to complete the solution in about 2 hours.

### Screenshot

![My Solution](./images/SOLUTION%20-%20fm-qr-code-component.png)

Above is a screenshot of the live website with the completed solution.

### Links

- Solution URL: [https://github.com/r0b3rt85/FM---QR-Code-Component](https://github.com/r0b3rt85/FM---QR-Code-Component)
- Live Site URL: [https://fm-qr-code-component-six.vercel.app](https://fm-qr-code-component-six.vercel.app)

## My process

There were a couple of stages that I tried to complete this solution, they are:

1. Create a GIT repository for the files to be saved and later published.
2. Import the design files into Figma to help with the sizing (padding, radius, sizing, etc...)
3. Define my CSS variables by using the style guide as a reference.
4. Go back and forth with the CSS definitions and nesting HTML content to show a useable structure. 
5. Commit the final code to my Git repository and publish on Vercel. 
6. Write the README.md with the steps I took.

### Built with

- HTML5 markup
- CSS custom properties
  - Flexbox
  - Media queries
  - Variable definitions
- Desktop-first workflow
- [Figma](https://figma.com/) - Design and sizing
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) - For CSS reference

### What I learned

When I was creating the solution to this challenge I really wanted to try and include CSS variables. This is something that I wanted to learn more about and impliment in one of my projects.

Below is the initial code needed to define the variables in your CSS file.

```css
:root{
  --white: hsl(0, 0%, 100%);
  --light-gray: hsl(212, 45%, 89%);
  --grayish-blue: hsl(220, 15%, 55%);
  --dark-blue: hsl(218, 44%, 22%);
}
```
Once the variable has been defined it can easily be used anywhere in your CSS file. This allows you to assign arbitrary values to a property with an author-chosen name, and the `var()` function. 

`:root` declares a custom property named `--white` on the root element, and assigns to it the value `hsl(0, 0%, 100%)`. This property is then inherited to the elements in the rest of the document. Its value can be referenced with the `var()` function:

```css
.card{  /* card style */
  width: 325px;
  height: 500px;

  background-color: var(--white);
  border-radius: 20px;
  box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
  padding: 16px;
}
```
I found that the variables are both case sensitive and font format specific as well. This is a creat solution and can be accessed in `@media` queries as well.


### Continued development

Further tweeks can be made to the code to make it more friendly on mobile devices. And some interactions when you hover over it might be nice (subtle 3D card effect).

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/--*) - This helped me understand how variables can be defined and used within CSS files. I really liked using this technique to define my main styles in an easy format.

## Author

- Website - [Under Construction]()
- Frontend Mentor - [@r0b3rt85](https://www.frontendmentor.io/profile/r0b3rt85)
- GitHub - [@r0b3rt85](https://github.com/r0b3rt85)

## Acknowledgments

Thank you to Frontend Mentors for providing an extensive range of resources to help new developers access projects based around web development.
