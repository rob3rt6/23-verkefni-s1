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


# Litir og myndir í bakgrunni vefsíðu

```CSS

body {
    background-color: #6ff;
    background-image:url(flott-logo.svg);
    background-repeat: no-repeat;     /* repeat-x eða repeat-y */
    background-position: 200px 300px; /* föst staðsetning frá vinstra horni efst */
    background-position: center middle;
    /* X lárétt: left, center, right. Y lóðrétt: top, middle, bottom */
    background-attachment: fixed; /* scroll */	
}
body {			
	background: rgb(3,3,3) url(image.jpg) 0px -5px scroll no-repeat;
            /*  litur,   mynd,  staðsetning X-Y,  fixed,  repeat -x -y */

}

```