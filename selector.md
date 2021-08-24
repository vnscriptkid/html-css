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

## :star: Psuedo-class selectors
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
