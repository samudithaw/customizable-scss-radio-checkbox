# Customizable Radio & Checkbox

Pure CSS only customizable radio button and checkbox.

![Image](/example/custom.png?raw=true)

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
```css
Checkbox SCSS Variables
// Check Box Styles
$check-box-background-color: transparent !default;
$check-box-box-shadow: 2px 2px 10px rgba(0, 0, 0, .2) !default;
$check-box-border-radius-value: 1px !default;
$check-box-border-color: #344 !default;
$check-box-border-width: 2px !default;
$check-box-width: 20px !default;
$check-box-height: 20px !default;
$check-box-label-left-padding: 10px !default;
$check-box-label-vertical-align: center !default;

// Selected Styles (Tick)
$check-box-tick-color: #fff !default;
$check-box-selected-background-color: #f00 !default;
$check-box-selected-border-color: #344 !default;

// Selected Styles (Box)
$check-box-box-background: #fff !default;
$check-box-box-border-color: #344 !default;

Radio SCSS Variables
// Radio Styles
$radio-background-color: #fff !default;
$radio-box-shadow: 2px 2px 10px rgba(0, 0, 0, .2) !default;
$radio-border-radius-value: 1px !default;
$radio-border-color: #344 !default;
$radio-border-width: 2px !default;
$radio-width: 20px !default;
$radio-height: 20px !default;
$radio-label-left-padding: 10px !default;
$radio-label-vertical-align: center !default;

// Selected Styles (Circle)
$radio-selected-background-color: #f00 !default;
$radio-selected-border-color: #f00 !default;

// Selected Styles (Tick)
$radio-tick-color: #fff !default;
$radio-tick-selected-border-color: #344 !default;
$radio-tick-selected-background: #f00 !default;
```
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