# Frontend Mentor - Huddle landing page with curved sections solution

This is a solution by me for [Huddle landing page with curved sections challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2).

### Screenshot

### Links

- [Solution Link](example.com)
- [Live Site Link](exmaple.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- scss
- Flexbox
- javascript for email validation

### What I learned

Got more used to dealing with svg, used flexbox, made the site responsive, used mobile first approach, used media queries and scss variables

### code snippets:

```js
/* javascript email validation */
function ValidateEmail(value) {
  if (/^\w+([\.-]?\w+)*@\w+([\.-]?\w+)*(\.\w{2,3})+$/.test(value)) {
    return true;
  } else {
    return false;
  }
}
```

### Useful resources

- [scss](https://sass-lang.com/documentation) - This helped me understand how to use scss for this project
- [stackoverflow](https://stackoverflow.com/questions/32027935/addeventlistener-is-not-a-function-why-does-this-error-occur) - This helped me resolve the issue of the getElementsByClassName returning a array, I had assumed it would only give me a single item due which I got a error
- [semantic html tags](https://www.w3schools.com/html/html5_semantic_elements.asp) - This helped me understand the semantic meaning of the tags, previous mostly only used div's.
