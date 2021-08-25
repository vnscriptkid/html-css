## Why not `<i>`, `<b>`:
- HTML is not intended for styling, use css instead
- Alternative: `<em>`: emphasize, `<strong>`: very important. These gives guidance for search engine

## Heading
- Only 1 `<h1>` for one page. Do not confuse search engine

## Entities
- Hey, it's just text i don't mean tag: `&lt;` ; `&gt;` &lt;HTML&gt;
- Fancy symbols: `&copy;` &copy;
- Do not break line there: `&nbsp;` (not breaking space)

## Links
<img height="200px" src="https://user-images.githubusercontent.com/28957748/130650881-5f617be0-0d18-402f-9887-7be6117c0d8c.png" />

## Images
https://unsplash.com/
```css
img {
    width: 800px;
    height: 200px;
    /* within the box, remains the ratio */
    object-fit: cover;
}
```

## Videos
https://www.pexels.com/
```html
<video controls autoplay loop width="300px" src="videos/ocean.mp4">
    Your browser doesn't support videos.
</video>
```

## Tables
```css
table,
td,
th {
    border: 1px solid black;
    border-collapse: collapse;
    padding: 5px;
}
```

## Element Types
- Block
    - Starts in a new line
    - Fill up entire available space
    - Example: `<p>`, `<div>`
- Inline
    - Example: `<span>`

## Containers
<img src="https://user-images.githubusercontent.com/28957748/130657331-376046f1-1891-4302-8017-b6d5a30a3ce4.png" width="100px"/>
<img src="https://user-images.githubusercontent.com/28957748/130657384-ae83040a-284d-48fa-a661-fb1748962b51.png" width="100px"/>

## :star: Inheritance
https://flaviocopes.com/css-inheritance/
- Usecase 1: Font color is __inherited__ by default (from parent)
```css
/* Force it not */
p span {
  color: initial;
}
```
- Usecase 2: Border is __not inherited__ by default (from parent)
```css
p {
  border: 1px solid black;
}
/* Force it to inherit */
p span {
  border: inherit;
}
```

## :star: Color
<img src="https://user-images.githubusercontent.com/28957748/130728301-bf7228dd-19ec-42fd-8c8f-77590750721c.png" width="700px" />

## :star: Gradients
https://cssgradient.io/
```css
.box {
  height: 500px;
  width: 900px;
  background: linear-gradient(to right, yellow, green);
}
```

## :star: Border
- Width, type, color
```css
.box {
  border: 1px solid black;
}
```
- Radius
https://css-tricks.com/the-shapes-of-css/

## :star: Shadow
```css
.box {
  box-shadow: 0 0 30px grey;
}

h1 {
  text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.2);
}
```
