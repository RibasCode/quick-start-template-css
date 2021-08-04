# quick-start-template
## A template with the basics already set up to start web projects using HTML, CSS, JavaScript and Php faster.



### @font-face
- Use of Poppins & Open Sans localy
- Fast performance optimitzation

* Also a Google fonts CDN @import comented on the css, to launch a quick start in case you want a lighter weith project, you can remove the local files on:
- assets/font
- assets/css/font/css



### mobile frist
- This project it's done with mobile frist to keep good practices



### jQuery
- Contains a local script for making use of jQuery on its version 3.6.0
- Fast performance optimitzation

* Also jQuery CDN comented for quick start in case you want lighter weith project, you can remove the local files on:
- assets/js/jquery



### butter
- Commented by defauld
- Warning, fixed elements has to be outside of ```<main id="butter">``` for its proper functioning
- if you want butter on your project you have to uncoment the following lines:
```
   <!-- <script src="assets/js/butter.js"></script>
	<script>
		butter.init({cancelOnTouch: true});
	</script> -->
```

- if you dont want butter.js in your project you can remove the local files on:
- assets/js/butter.js
- and its respective lines of code previously mentioned



### normalize
- A library to neutralize css styles in all browsers
- you can find normalize.css at:
```
	CSS at (style.css)
     /* @import url(normalize.css); */

```



### AOS
- Commented by defauld
- A library to animate your website
- if you want AOS on your project you have to uncoment the following lines:
```
	CSS at (style.css)
     /* @import url(aos.css); */

	JS at (index.html)
   <!-- <script src="assets/js/aos.js"></script>
	<script>
		AOS.init();
	</script> -->
```
    
- if you dont want AOS in your project you can remove the local files on:
- assets/css/aos.css
- assets/js/aos.js
- and its respective lines of code previously mentioned



### @media

#### Custom (currently using this)
- Apple & Bootstrap mixt
```
/* Small devices (phones, 0px and up) */

/*--------------------------------------------------------------
    @media - Mobile First
--------------------------------------------------------------*/

/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { ... }

/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { ... }

/* Large devices (small laptops, 1069px and up) */
@media (min-width: 1069px) { ... }

/* Large devices (laptops, 1281px and up) */
@media (min-width: 1281px) { ... }

/* Extra large devices (desktop and macbook 16", 1441px and up) */
@media (min-width: 1441px) { ... }

/*--------------------------------------------------------------
    @media - Compressed Screens
--------------------------------------------------------------*/

/* Tablets compressed height */
@media screen and (max-width: 1068px) and (min-width: 768px) and (max-height: 733px) and (min-height: 0px) { ... }

/* Laptops compressed height */
@media screen and (max-width: 1440px) and (min-width: 1069px) and (max-height: 775px) and (min-height: 0px) { ... }

/* Desktop compressed height */
@media screen and (max-width: 1441000px) and (min-width: 1441px) and (max-height: 775px) and (min-height: 0px) { ... }
```


#### Aple
```
/* Small devices (phones, 0px and up) */

/*--------------------------------------------------------------
    @media - Apple
--------------------------------------------------------------*/

/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) { ... }

/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { ... }

/* Large devices (laptops, 1069px and up) */
@media (min-width: 1069px) { ... }

/* Extra large devices (desktop and macbook 16", 1441px and up) */
@media (min-width: 1441px) { ... }

/*--------------------------------------------------------------
    @media - Compressed Screens
--------------------------------------------------------------*/

/* Tablets compressed height */
@media screen and (max-width: 1068px) and (min-width: 768px) and (max-height: 733px) and (min-height: 0px) { ... }

/* Laptops compressed height */
@media screen and (max-width: 1440px) and (min-width: 1069px) and (max-height: 775px) and (min-height: 0px) { ... }

/* Desktop compressed height */
@media screen and (max-width: 1441000px) and (min-width: 1441px) and (max-height: 775px) and (min-height: 0px) { ... }
```


#### Bootstrap
```
// Extra small devices (portrait phones, less than 576px)
// No media query for `xs` since this is the default in Bootstrap

/*--------------------------------------------------------------
    @media - Bootstrap
--------------------------------------------------------------*/

// Small devices (landscape phones, 576px and up)
@media (min-width: 576px) { ... }

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) { ... }

// Large devices (desktops, 992px and up)
@media (min-width: 992px) { ... }

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) { ... }
```