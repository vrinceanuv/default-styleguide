## Default style guide

This style guide is done so we can have a starting point for future projects.
The reset used is Eric Meyer's Reset.

## Features
- **Typography**
- **Grid**
- **Branding**

## Typography
_(coming soon)_

## Grid
- **12 columns grid**
- **Simple and not responsive(yet)**
```html
<div class="container">
  <div class="row">
    <div class="col col-6"></div>
    <div class="col col-4"></div>
    <div class="col col-2"></div>
  </div>
</div>
```

## Branding
_(coming soon)_

## Elements
- **Forms**
```html
<form action="#">
  <!-- Legend element -->
  <legend>Form Legend</legend>

  <!-- Text input -->
  <input type="text">

  <!-- Textarea -->
  <textarea rows="5"></textarea>

  <!-- Title heading for a radio group -->
  <span class="group-title">What are your hobbies?</span>

  <!-- Checkboxes -->
  <input type="checkbox" id="cycling" name="hobbies"> <label for="cycling">Cycling</label>
  <input type="checkbox" id="running" name="hobbies"> <label for="running">Running</label>

  <div class="clearfix"></div>

  <!-- Title heading for a radio group -->
  <span class="group-title">In what department are you working?</span>

  <!-- Radio buttons -->
  <input type="radio" id="designer" name="profession-choice"> <label for="designer">Creative</label>
  <input type="radio" id="developer" name="profession-choice"> <label for="developer">Development</label>
</form>
```

- **Buttons**
```html
<!-- Default button -->
<button>Cancel</button>

<!-- Default button disabled -->
<button disabled>Cancel</button>

<!-- Primary button -->
<button class="button-primary">Submit</button>

<!-- Primary button disabled-->
<button class="button-primary" disabled>Submit</button>
```
- **Cards**
_(coming soon)_

## Reusable classes
- Float
```html
<!-- floating an element to the left -->
<div class="float-left"></div>

<!-- floating an element to the right -->
<div class="float-right"></div>
```

- Paddings { small: 5px, medium: 10px, large: 15px, xlarge: 25px }
```html
<!-- padding on all sides -->
<div class="padding-round-small"></div>

<!-- padding top and bottom -->
<div class="padding-vertical-small"></div>

<!-- padding left and right -->
<div class="padding-horizontal-small"></div>

<!-- padding top -->
<div class="padding-top-small"></div>

<!-- padding right -->
<div class="padding-right-small"></div>

<!-- padding bottom -->
<div class="padding-bottom-small"></div>

<!-- padding left -->
<div class="padding-left-small"></div>
```

- Margins { small: 5px, medium: 10px, large: 15px, xlarge: 25px }
```html
<!-- margin on all sides -->
<div class="margin-round-small"></div>

<!-- margin top and bottom -->
<div class="margin-vertical-small"></div>

<!-- margin left and right -->
<div class="margin-horizontal-small"></div>

<!-- margin top -->
<div class="margin-top-small"></div>

<!-- margin right -->
<div class="margin-right-small"></div>

<!-- margin bottom -->
<div class="margin-bottom-small"></div>

<!-- margin left -->
<div class="margin-left-small"></div>
```

- Alignment
```html
<!-- horizontally centering a block element -->
<div class="center-align"></div>
```

- Text transforms
```html
<!-- transforming the text inside the element to uppercase -->
<div class="uppercase"></div>

<!-- transforming the text inside the element to lowercase -->
<div class="lowercase"></div>
```

## Contributing
```
$ npm install
$ npm run watch
$ npm run build
```
The watcher will watch any scss changes and the build will covert to css.
After the above 3 steps, commit, push and raise a PR.
