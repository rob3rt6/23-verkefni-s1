# Skipulag vefsíðu - webpage layout

Í verkefni 3.1 getur þú afritað [index.html](index.html) vefsíðuna yfir í áfangageymsluna þína. Stílsíðuna býrðu til sjálfur og í verkefni 3.2 setur þú upp vefsíðu og stílsíðu. Innihald vefsíðunnar er svokallaður _"dummy"_ texti sem hægt er að afrita héðan: [Lorem Ipsum](https://lipsum.com/)

### HTML 5 ritháttur (_semantic_)

* [Semantic HTML5 Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)
* [Moz:lla glósur](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

# Svegjanleg hönnun

### Viðmið (_Breakpoints_) - "_Mobile up_"

```CSS
/* Fyrst koma stílar sem gilda í öllum skjástærðum ss. leturtýpa og litir */
body {
background-color: lightblue;
font-family: sans-serif;
color: white;
}

@media only screen and (min-width: 37.5em) {  /* skjáir (screen) sem eru stærri en 37.5em (600px) */
  body {
    background-color: blue;
  }
}

@media only screen and (min-width: 48em) {  /* skjáir (screen) sem eru stærri en 48em (768px) */
  body {
    background-color: green;
  }
}

@media only screen and (min-width: 60em) {  /* skjáir (screen) sem eru stærri en 60em (960px) */
  body {
    background-color: red;
	max-width: 60em;
	margin: 0 auto;
	border: 2px solid yellow;
  }
}

``` 

#### Skipulag með CSS grindakerfi

* https://gridbyexample.com/
* [CSSGRID.IO](https://cssgrid.io/)
* [Codrops - CSS References](https://tympanus.net/codrops/css_reference/grid/)
* [Learn CSS Grid](https://scrimba.com/g/gR8PTE)
