# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

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

## Overview

### The challenge

Your challenge is to build out this order summary card component and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Your users should be able to:

- See hover states for interactive elements

Want some support on the challenge? [Join our Slack community](https://www.frontendmentor.io/slack) and ask questions in the **#help** channel.

### Screenshot

![](images/SummaryCard.png)

### Links

- Solution URL: [https://github.com/Djokaras/order-summary-component]
- Live Site URL: [https://djokaras.github.io/order-summary-component/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

Positioning elements using flexbox. Setting up breakpoints for media queries.

```css trick learned to seperate one element in the flex with margin
.plan-section {
	background: hsl(225, 100%, 98%);
	padding: 2rem 3rem;
	border-radius: 16px;

	display: flex;
	gap: 2.4rem;
	align-items: center;
}

.plan-change {
	margin-left: auto;
}
```

### Continued development

Need to work on the responsive design more. And should try mobile-first approach.

### Useful resources

- [https://www.youtube.com/watch?v=Azfj1efPAH0&ab_channel=KevinPowell]
  This YT video helped me with margin-flexbox positioning.

## Author

Djordje Stevic
