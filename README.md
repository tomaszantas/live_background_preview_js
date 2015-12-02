# live_background_preview_js
Change the background image property in CSS on fly.

## Introduction

This tool allows to change the URL of background-image property of any of your elements by simple text input.

## Demo
http://codepen.io/tomaszantas/pen/QyLxaz


## Requirements

JQuery


## Usage

1. Import live_background_preview.js file.

2. Add text input and button to html file:

```html
<div class='live_background_preview_input_wrapper'>
    <input type="text" id='live_background_preview_input' data-target="#header" name="live_background_preview_input" placeholder="Put here the URL to the image">
    <button id='submit_live_background_preview'>Check background</button>
</div>
```

Change only **data-target** atrribute of input element. It should points on element which background should be changed.

3. Refresh your site in web browser and type any URL to the input text. Then click on button.
