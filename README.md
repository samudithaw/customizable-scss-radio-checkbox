# Customizable Radio & Checkbox

Pure CSS only customizable radio button and checkbox.

## Installation

```bash
npm i --save customizable-scss-radio-checkbox
```
## Import
Custom Checkbox

```scss
@import "../node_modules/customizable-scss-radio-checkbox/css-only-checkbox";
```
Custom Radio Button

```scss
@import "../node_modules/customizable-scss-radio-checkbox/css-only-radio";
```
## Customize
Edit the checkbox & radio variable files to change the colors & sizes.

## Usage

Input filed should contain id tag & label tag should have valid for attribute
```html
<div class="sw-checkbox box">
  <input type="checkbox" id="checkbox">
  <label for="checkbox">Check Box</label>
</div>

<div class="sw-checkbox">
  <input type="checkbox" id="checkbox1">
  <label for="checkbox1">Check Box</label>
</div>

<div class="sw-radio check">
  <input type="radio" name="radio" id="radio">
  <label for="radio">Radio</label>
</div>
<div class="sw-radio">
  <input type="radio" name="radio" id="radio1">
  <label for="radio1">Radio</label>
</div>
```

## License
[MIT](https://choosealicense.com/licenses/mit/)