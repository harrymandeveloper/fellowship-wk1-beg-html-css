# Project: Homepage

---

## Some help

---

### Planning

Consistency, design patterns

- Content first
- What elements are reused, where?
- Do containers have consistent padding or margin?
- Fixed size? What if element’s contents overflow?

---

### Do a bit of prototyping

HTML sectioning elements first

Think about your boxes…

Layout early, test it

---

### Naming things

I want to see some classes

- What am I targeting?
- Do I want to target all of them on the whole site, or just for this particular use case?
- ...as that will inform how you target an element to change its styling

---

### The *cascade* is really important

Remember for now, what comes last is added last

It overrides what has been declared before

---

### CSS File Order

```css
/* 1) Layout */
Stuff to lay out your page structure

/* 2) Generic */
Fonts, colours, bullet point styles, link hover state, forms

/* 3) Specific */
Page/content specific, e.g. this one button
```
---

### Browsers add styles

Start clean - add reset.css

[https://meyerweb.com/eric/tools/css/reset/](https://meyerweb.com/eric/tools/css/reset/)

- Google it :)
- Either
	- Copy and paste it into the TOP of your CSS
	- Create a new file `reset.css` and remember to include it in your build

---

### Normalize

> Normalize.css is a small CSS file that provides better cross-browser consistency in the default styling of HTML elements.

[https://necolas.github.io/normalize.css/](https://necolas.github.io/normalize.css/)

- Download it
- Set it as first stylesheet
- Then pull in your stylesheet

---

### Use comments!

HTML
```
<div class=“header”>

</div><!-- /.header -->
```

CSS
```css
/* forms, input and buttons */
form {
	border: 1px solid red;
}
```

---

### Start as you mean to go on

- Keep your code neat
	- indenting
	- spacing
- keep CSS structured/organised

---

### Folder structure & filenames

- lowercase
- NO spaces, use underscore _ or hyphen -
- pick a style and stick to it
- new-january-newsletter-logo.jpg







