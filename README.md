# Frontend Mentor - Results summary component

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

## Preview

![](/images/animation.gif)

## Users should be able to:

View the optimal layout depending on their device's screen size
See hover and focus states for interactive elements

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

## My process

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS Reset by Josh Comeau

## Some code:

```
.result__button {
    margin: 15px 0;
    border-radius: 25px;
    border: none;
    padding: 15px;
    color: var(--color-white);
    font-weight: bold;
    background-image: var(--btn-gradient);
    letter-spacing: 1.3px;
    cursor: pointer;
    background-size: 300%;
    background-position: left;
    transition: 1s background-position ease-in-out, 0.8s box-shadow ease-in-out;
}

.result__button:hover {
    box-shadow: 0 5px 12px var(--color-darkLavender);
    background-position: right;
}

.result__button:focus {
    box-shadow: 0 5px 12px var(--color-darkLavender);
    background-position: right;
}
```
