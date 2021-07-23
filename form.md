## HowTo: Trigger form submit with a button sitting outside the form
```html
<div>
  <form id="my-form">
    <label for="name">Name:</label>
    <input type="text" name="name"></input>
  </form>

  <!-- ... -->

  <button type="submit" form="my-form">Submit</button>
</div>
```
