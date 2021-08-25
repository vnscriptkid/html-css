## Select by attribute
<img width="300px" src="https://user-images.githubusercontent.com/28957748/130664890-afe0927b-927a-493f-8af3-fe4a37874567.png" />

## :star: Relational selectors
#### :one: Descendants
```css
.products p {}
```
#### :two: Direct children
```css
.product > p {}
```
#### :three: Sibling immediate after
```css
.product + p {}
```
#### :four: All sibilings come after
```css
.product ~ p {}
```

## :star: Pseudo-class selectors (Style elements at a particular state)
#### First child of ul with any type
```css
ul :first-child { }
```
#### First child of div with type p
```css
div p:first-of-type { }
```
#### Last child of ul with type li
```css
ul li:last-child { }
```
#### Odd children of ul with type li
```css
ul li:nth-child(odd) { }
```
#### Links at different states
```css
a:visited,
a:link {
  color: dodgerblue;
}

a:hover,
a:focus {
  color: deeppink;
}
```

## :star: Pseudo-elements (style part of element)
#### First letter of element p
```css
p::first-letter {
  font-size: 300%;
  font-weight: bold;
}
```
#### First line of element p
```css
p::first-line {
  color: red;
}
```
#### Selection part of any element
```css
::selection {
  background-color: pink;
}
```
#### Append pseudo-element to head of p && end of p
```css
/* inline element by default */
p::before {
  content: "..."
}

p::after {
  content: "...";
  display: block;
}
```

## :star: Specificity

<img src="https://user-images.githubusercontent.com/28957748/130725958-58558859-121f-4591-9da4-6f31791e428c.png" width="700px" />
