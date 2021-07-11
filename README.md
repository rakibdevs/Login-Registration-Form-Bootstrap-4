# Login Registration Modal Form - Bootstrap 4.0
Click to see live demo [here](https://rakibdevs.github.io/Login-Registration-Form-Bootstrap-4/) or edit preview in  [Codepen](https://codepen.io/rakibhstu/project/editor/Xawarw)

Modern bootstrap login and registration forms design.

  - Dark and Light version
  - Easy to customize
  - Well Documentation
  
 [![N|Solid](https://rakibul.dev/demo/01_preview_1.jpg)](https://rakibul.dev/)
 [![N|Solid](https://rakibul.dev/demo/05_preview_5.jpg)](https://rakibul.dev/)


### Requirements

* [Bootstrap 4.0](https://getbootstrap.com/docs/4.0/getting-started/introduction/) 
* [jQuery 3.5.0](https://jquery.com/download/) 
* [Font Awesome 5.5.0 free version](https://fontawesome.com/) 


### Installation

Include Bootstrap 4, font awesome and jQuery library. Add css files in head and scripts before ending of body tag. **If you integrate with laravel, no need to include external scripts. It is compatible with app.css and app.js** 

```html
<!DOCTYPE html>
<html>
<head>
	<!-- font awesome v5.5.0 free version -->
	<link href="assets/vendor/fontawesome-free/css/all.min.css" rel="stylesheet">
	<!-- bootstrap version v4.0.0 -->
	<link href="assets/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

    <!-- jQuery v3.5.0 or latest version of jQuery -->
	<script src="assets/js/jquery-3.5.1.min.js" ></script>
	<!-- bootstrap js -->
	<script src="assets/vendor/bootstrap/js/bootstrap.min.js" ></script>
</body>
</html>
```
Select a design you want to integrate. Open index.html file and select code from your desired design. Suppose you have selected **modal style 1**, then copy & paste the code as follows-

```html
<!--modal style 1 start -->
	<!-- login modal 1 -->
	<div id="loginModal1" class="modal-style-1 modal ">
	.....................................................
	.....................................................
	</div>
	<!-- register modal 1 -->
	<div id="registerModal1" class="modal-style-1 modal ">
	....................................................
	....................................................
	</div>
<!--modal style 1 end -->
```
now add this anchor tags `<a></a>` anywhere in menu. Dont forget to add `data-toggle="modal"` attribute
```html
<!-- action button for modal style 1 start -->
<a href="#loginModal1" data-toggle="modal" class="btn btn-primary text-white"> Login</a>
<a href="#registerModal1" data-toggle="modal" class="btn btn-success text-white">Register</a>
<!-- action button for modal style 1 end -->
```

And finally you have to include css. Open **style.css** from `assets/css/ directory`. Copy and paste the code into your own css file. You can easily change theme color from css. Change color in `:root {}` selector
```css
:root {
    --color-facebook: #3b5998;
    --color-google: #ea4335;
    --color-twitter: #1da1f2;

    --style-1-color: #009688;
}
/*-------------------------------------------------
 * Modal Style 1 CSS start
 *-----------------------------------------------*/
.modal-style-1 .modal-login{
	.....................................
/*modal style 1 end*/
```

### Swith to Dark or Light
It is very easy to switch between light or dark mode. In order to switch dark mode add an extra class `dark`. and for light mode remove `dark` class

```html
<!-- Dark Mode -->
<div id="loginModal1" class="modal-style-1 dark modal ">
........................................
</div>
<div id="registerModal1" class="modal-style-1 dark modal ">
........................................
</div>

<!-- Light Mode -->
<div id="loginModal1" class="modal-style-1 modal ">
........................................
</div>
<div id="registerModal1" class="modal-style-1 modal ">
........................................
</div>
```
outpu,
<p align="center">
  <img src="https://rakibul.dev/demo/style-1-demo.jpg">
</p>

### Customization
You can change color as well as mixup the desings with other variants. Suppose, you want to change theme color of **style 1**. Pick the color hex code. replace the color value in `:root{}` selector. We assume your selected color hex code is `#607D8B`

```css
:root {
     --style-1-color: #607D8B;
}
```
now output will be,
<p align="center">
  <img src="https://rakibul.dev/demo/style-1-demo-change.jpg">
</p>


### Contribute

Want to contribute? Great! fork the repository.


License
----
MIT

### Designed By
[![N|Solid](https://rakibul.dev/images/logo.png)](https://rakibul.dev/)
