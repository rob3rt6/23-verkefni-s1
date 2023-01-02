#### Verkefni 2.1

![box model](box-model.png)

https://www.w3schools.com/css/css_boxmodel.asp

---

#### Verkefni 2.2

```CSS

.ex1 {display: none;}
.ex2 {display: inline;}
.ex3 {display: block;}
.ex4 {display: inline-block;}

```

https://www.w3schools.com/cssref/pr_class_display.asp

---
## Box Modelið

![Boxmodel](Box model/box-model.png)

Explanation of the different parts:

- Content - The content of the box, where text and images appear
- Padding - Clears an area around the content. The padding is transparent
- Border - A border that goes around the padding and content
- Margin - Clears an area outside the border. The margin is transparent

The box model allows us to add a border around elements, and to define space between elements. 

# Display

## Block-level Elements

A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

The &lt;div> element is a block-level element.
Examples of block-level elements:

```HTML
<div>
<h1> - <h6>
<p>
<form>
<header>
<footer>
<section>
```

## Inline Elements
An inline element does not start on a new line and only takes up as much width as necessary.

This is an inline &lt;span> element inside a paragraph.

Examples of inline elements:

```HTML

<span>
<a>
<img>

```

## Display: none;

display: none; is commonly used with JavaScript to hide and show elements without deleting and recreating them. Take a look at our last example on this page if you want to know how this can be achieved.

The &lt;script> element uses display: none; as default. 

