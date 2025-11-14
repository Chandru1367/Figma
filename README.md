# Ex09 Event Registration Web Application
## Date: 14.11.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:

## col1.html
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Iceland:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="css/reset.css" />
	<link rel="stylesheet" href="css/global.css" />
	<link rel="stylesheet" href="css/col1.css" />

</head>

<body>
	<img src="assets/col/img1.png" class="img1" />
	<img src="assets/img.png" class="img-top" />
	<img src="assets/col/img2.png" class="img2" />
	<h1 class="title-sports-day-events">SPORTS DAY EVENTS</h1>
	<button class="btn btn1 hover-bright">LOGIN</button>
	<button class="btn btn-register hover-bright">REGISTER</button>
</body>

</html>
```
## col1.css
```css

* {
	--max-screen-size: 567.6056518554688;
}

body {
	position: relative;
	gap: 42px;
	color: #fff;
	font-size: 48px;
	font-family: 'Inter';
	background-attachment: unset;
	padding: 46px 0 87px 2px;
}

.btn {
	position: relative;
	box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
	display: flex;
	font-style: normal;
	letter-spacing: 0px;
	border-radius: 8px;
}

.img1 {
	position: absolute; top: 0; left: 0; right: 0; 
	width: 100%;
	border: 1px solid #000;
	border-radius: 47px;
}

.img-top {
	position: relative; z-index: 4;
	margin-right: -2px;
	flex-shrink: 0;
	align-self: stretch;
}

.img2 {
	position: relative; z-index: 3;
	margin-left: -2px; margin-top: 33px;
	width: 239px;
	flex-shrink: 0;
}

.title-sports-day-events {
	position: relative; z-index: 5;
	margin: 9px auto 0 auto;
	width: 90%;
	max-width: 397px;
	color: #00477d;
	--min-font-size: 34; --max-font-size: 36; font-size: var(--interpolate);
}

.btn1 {
	z-index: 1;
	margin-left: 32px; margin-top: 11px;
	width: 205px;
	text-align: left;
	background-color: #0051ff;
	padding: 3px 24px 4px 24px;
}

.btn-register {
	z-index: 2;
	margin: 0 auto;
	width: 90%;
	max-width: 278px;
	justify-content: center;
	text-align: center;
	background-color: #2942ff;
	padding: 0 10px 7px 10px;
}



/** breakpoints (margin / paddings) **/

@media screen and (max-width: 480px) {
	.img-top {
		margin-inline: 0;
	}
	.title-sports-day-events {
		margin-inline: 0;
	}
	.btn-register {
		margin-inline: 0;
	}
}

```
## col2.html

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Iceland:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="css/reset.css" />
	<link rel="stylesheet" href="css/global.css" />
	<link rel="stylesheet" href="css/col2.css" />

</head>

<body>
	<h1 class="title-sports-day-events">SPORTS DAY EVENTS</h1>
	
	<div class="row row1">
		<object data="assets/col/row/row-star.svg" class="row-star-left" type="image/svg+xml"></object>
		<h1 class="row-title">CRICKET</h1>
	</div>
	
	<div class="row row2">
		<object data="assets/col/row/row-star.svg" class="row-star-left" type="image/svg+xml"></object>
		<h1 class="row-title">BADMINTON</h1>
	</div>
	
	<div class="row row3">
		<object data="assets/col/row/row-star.svg" class="row-star-left" type="image/svg+xml"></object>
		<h1 class="row-title">VOLLEY BALL</h1>
	</div>
	
	<div class="row row4">
		<object data="assets/col/row/row-star.svg" class="row-star-left" type="image/svg+xml"></object>
		<h1 class="row-title">CHESS</h1>
	</div>
	
	<div class="row row5">
		<object data="assets/col/row/row-star.svg" class="row-star-left" type="image/svg+xml"></object>
		<h1 class="row-title">RUNNING</h1>
	</div>
	
	<div class="row row6">
		<object data="assets/col/row/row-star.svg" class="row-star-left" type="image/svg+xml"></object>
		<h1 class="row-title">FOOTBALL</h1>
	</div>
</body>

</html>
```

## col2.css

```css
body {
	container: body / inline-size;
	align-items: flex-start;
	gap: 41px;
	font-size: 36px;
	font-family: 'Inter';
	text-align: center;
	background: url(../assets/col/col1.png) center / cover no-repeat;
	padding: 88px 13px 128px 13px;
	border-radius: 65px;
}



/* row */

.row {
	margin-left: 52px;
	display: flex;
	align-items: flex-start;
	gap: 35px;
	padding-left: 1px;
}

.row-star-left {
	width: 42px; height: 40px;
	flex-shrink: 0;
}

.row-title {
	margin-right: -3px;
	text-align: left;
}
/* end row*/


.title-sports-day-events {
	align-self: stretch;
	color: #000;
}

.row1 {
	color: #0400ff;
}

.row2 {
	margin-left: 52px; margin-top: 7px;
	gap: 34px;
	color: #0f13ff;
}

.row3 {
	margin-left: -47px; margin-top: 7px;
	align-self: center;
	color: #02f;
}

.row3 .row-title {
	margin-right: -2px;
}

.row4 {
	margin-top: 19px;
	color: #10f;
}

.row5 {
	margin-top: 19px;
	color: #001eff;
}

.row6 {
	margin-top: 19px;
	color: #2802ff;
}

```

## col3.html

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Iceland:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="css/reset.css" />
	<link rel="stylesheet" href="css/global.css" />
	<link rel="stylesheet" href="css/col3.css" />

</head>

<body>
	<div class="rect1"></div>
	<h1 class="title-event title">EVENT REGISTRATION FORM</h1>
	<h1 class="title-fill-the-form title">FILL THE FORM</h1>
	<div class="full-name full-name1">FULL NAME</div>
	
	<div class="column col5">
		<div class="column-rect"></div>
		<h1 class="column-title">
			REGISTER NO<br />
			<br />
			
		</h1>
	</div>
	
	<div class="full-name department">DEPARTMENT</div>
	<button class="btn-mobile-number hover-dark">MOBILE NUMBER</button>
	<div class="full-name">AGE</div>
	
	<div class="column col6">
		<div class="column-rect"></div>
		<h1 class="column-title">
			GENDER<br />
			<br />
			
		</h1>
	</div>
	
	<h1 class="title-email-id title">
		EMAIL ID<br />
		<br />
		
	</h1>
	
	<div class="column col7">
		<div class="column-rect"></div>
		<h1 class="column-title">
			EVENTS TO REGISTER<br />
			<br />
			
		</h1>
	</div>
	
	<div class="col-bottom">
		<div class="rect2"></div>
		<h1 class="title-register">REGISTER</h1>
	</div>
</body>

</html>
```

## col3.css

```css

* {
	--max-screen-size: 590;
}

body {
	position: relative;
	color: #000;
	font-family: 'IM FELL DW Pica SC';
	background: url(../assets/col/col2.png) center / cover no-repeat;
	padding: 23px 15px 10px 15px;
	border-radius: 30px;
}

.full-name {
	margin-left: -27px; margin-top: 31px;
	width: 100%;
	max-width: 387px;
	font-size: 32px;
	background-color: #fff;
	padding: 6px 31px 6px 58px;
}



/* column */

.column {
	position: relative;
	margin-left: -27px;
	width: 100%;
	max-width: 387px;
	display: flex;
	flex-direction: column;
	--min-font-size: 30; --max-font-size: 32; font-size: var(--interpolate);
	padding: 6px 31px 0 58px;
}

.column-rect {
	position: absolute; top: 0; left: 0; right: 0; 
	height: 52px;
	background-color: #fff;
}

.column-title {
	position: relative; z-index: 1;
	margin-bottom: -34px;
}
/* end column*/


.rect1 {
	position: absolute; top: 622px; left: 88px; 
	width: calc(100% - 88px); height: 52px;
	max-width: 387px;
	background-color: #fff;
}

.title-event {
	text-shadow: -1px -1px 0px #000,1px -1px 0px #000,1px 1px 0px #000,-1px 1px 0px #000;
	align-self: stretch;
	color: #f00;
	text-align: center;
}

.title-fill-the-form {
	margin-top: 6px;
	align-self: stretch;
	text-align: center;
}

.full-name1 {
	margin-top: 8px;
}

.col5 {
	margin-top: 34px;
}

.department {
	padding-top: 12px;
	padding-bottom: 0;
}

.btn-mobile-number {
	margin-left: -27px; margin-top: 35px;
	width: 100%;
	max-width: 387px;
	display: flex;
	justify-content: center;
	font-size: 32px;
	font-style: normal;
	letter-spacing: 0px;
	text-align: center;
	background-color: #fff;
	padding: 9px 11px 3px 11px;
}

.col6 {
	margin-top: 31px;
	padding-top: 15px;
}

.col6 .column-title {
	margin-bottom: -43px;
}

.title-email-id {
	position: relative; z-index: 2;
	margin-top: auto; margin-bottom: -3px;
	width: 298px;
}

.col7 {
	margin-bottom: 19px;
	padding-left: 17px;
	padding-right: 0;
}

.col-bottom {
	position: relative;
	margin-left: -27px;
	width: 247px;
	display: flex;
	flex-direction: column;
	--min-font-size: 30; --max-font-size: 32; font-size: var(--interpolate);
	padding: 9px 0 8px 40px;
}

.rect2 {
	position: absolute; top: 0; left: 0; right: 0; 
	filter: blur(2px);
	height: 57px;
	background-color: #ff0004;
}

.title-register {
	position: relative; z-index: 1;
	text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25),-1px -1px 0px #000,1px -1px 0px #000,1px 1px 0px #000,-1px 1px 0px #000;
	margin-right: -91px;
}



/** breakpoints (margin / paddings) **/

@media screen and (max-width: 576px) {
	.full-name {
		padding-inline: var(--margin-sm);
		margin-inline: 0;
	}
	.column {
		padding-inline: 0;
		margin-inline: 0;
	}
	.btn-mobile-number {
		margin-inline: 0;
	}
	.col7 {
		padding-inline: 0;
	}
}

```

## col4.html

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<link href="https://fonts.googleapis.com/css2?family=Inter:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&family=Iceland:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="css/reset.css" />
	<link rel="stylesheet" href="css/global.css" />
	<link rel="stylesheet" href="css/col4.css" />

</head>

<body>
	<img src="assets/img.png" class="img-top" />
	<h1 class="title-thank-you">
		THANK YOU<br />
		<br />
		
	</h1>
	<h2 class="subtitle-we-are-all title">
		WE ARE ALL EAGERLY WAITING FOR YOUR PARTICIPATION IN THE SPORTS<br />
		EVENTS
	</h2>
	
	<footer class="footer">
		<h2 class="footer-subtitle-contact-us title">CONTACT US</h2>
		<h2 class="footer-subtitle-email-saveetha subtitle">EMAIL : SAVEETHA ENGINEERING COLLEGE</h2>
		<h2 class="footer-subtitle-phone-no subtitle">PHONE NO : </h2>
		<h2 class="footer-subtitle-bottom">
			+91 9944203746<br />
			+91 9944345356
		</h2>
	</footer>
</body>

</html>
```

## col4.css

```css

* {
	--max-screen-size: 575;
}

body {
	color: #000;
	font-family: 'IM FELL DW Pica SC';
	text-align: center;
	background: url(../assets/col/col3.png) center / cover no-repeat;
	padding-top: 48px;
	border-radius: 46px;
}

.img-top {
	margin-left: 7px;
	width: calc(100% - 7px);
	max-width: 940px;
	flex-shrink: 0;
}

.title-thank-you {
	text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25),-1px -1px 0px #000,1px -1px 0px #000,1px 1px 0px #000,-1px 1px 0px #000;
	margin: 55px auto 0 auto;
	width: 90%;
	max-width: 326px;
	--min-font-size: 46; --max-font-size: 48; font-size: var(--interpolate);
}

.subtitle-we-are-all {
	margin: -34px 13px 0 41px;
	align-self: stretch;
}

.footer {
	margin-top: auto;
	width: 100%;
	max-width: 950px;
	display: flex;
	flex-direction: column;
	gap: 7px;
	color: #fff;
	background-color: #331e1e;
	padding: 10px 10px 20px 10px;
	border-radius: 37px;
}

.footer-subtitle-contact-us {
	margin: 0 15px;
	color: #0dff00;
	text-align: left;
}

.footer-subtitle-email-saveetha {
	margin-top: 7px;
}

.footer-subtitle-phone-no {
	margin: 12px 10px 0 10px;
	text-align: left;
}

.footer-subtitle-bottom {
	--min-font-size: 34; --max-font-size: 36; font-size: var(--interpolate);
	font-family: 'Iceland';
}

```

## global.css

```css

:root {
	/* responsive margins / paddings */
	--margin-sm: 16px;
	--margin-md: 32px;
}

* {
	--min-screen-size: 430;
	--interpolate-diff: calc(var(--max-font-size) - var(--min-font-size));
	--interpolate: clamp(calc(var(--min-font-size) * 1px), calc((var(--min-font-size) * 1px) + var(--interpolate-diff) * ((100vw - calc(var(--min-screen-size) * 1px)) / (var(--max-screen-size) - var(--min-screen-size)))), calc(var(--max-font-size) * 1px));
}

html {
	height: 100%;
	font-size: 16px;
}

body {
	min-height: 100%;
	display: flex;
	flex-direction: column;
	align-items: center;
	font-weight: 400;
	line-height: normal;
	letter-spacing: 0px;
	background-attachment: fixed;
	overflow: auto;
}



/* text utility classes */

.subtitle {
	--min-font-size: 23; --max-font-size: 24; font-size: var(--interpolate);
}

.title {
	--min-font-size: 30; --max-font-size: 32; font-size: var(--interpolate);
	font-family: 'IM FELL DW Pica SC';
	font-weight: 400;
	line-height: normal;
	letter-spacing: 0px;
}



/* button hover utility classes */

.hover-dark:hover {
	filter: brightness(0.85);
}

.hover-bright:hover {
	filter: brightness(1.2);
}

```

## reset.css

```css

/*
1. Prevent padding and border from affecting element width. (https://github.com/mozdevs/cssremedy/issues/4)
2. Allow adding a border to an element by just adding a border-width. (https://github.com/tailwindcss/tailwindcss/pull/116)
*/

::before,
::after {
  --tw-content: '';
}


html,
:host {
  line-height: 1.5; /* 1 */
  -webkit-text-size-adjust: 100%; /* 2 */
  -moz-tab-size: 4; /* 3 */
  tab-size: 4; /* 3 */
  -webkit-tap-highlight-color: transparent; /* 7 */
}

body {
  margin: 0; /* 1 */
  line-height: inherit; /* 2 */
}

*{
	box-sizing: border-box;
}

hr {
  height: 0; /* 1 */
  color: inherit; /* 2 */
  border-top-width: 1px; /* 3 */
}

abbr:where([title]) {
  text-decoration: underline dotted;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

a {
  color: inherit;
  text-decoration: inherit;
}

b,
strong {
  font-weight: bolder;
}

code,
kbd,
samp,
pre {
  font-size: 1em; /* 4 */
}

small {
  font-size: 80%;
}

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

table {
  text-indent: 0; /* 1 */
  border-color: inherit; /* 2 */
  border-collapse: collapse; /* 3 */
}


button,
input,
optgroup,
select,
textarea {
  font-family: inherit; /* 1 */
  font-feature-settings: inherit; /* 1 */
  font-variation-settings: inherit; /* 1 */
  font-size: 100%; /* 1 */
  font-weight: inherit; /* 1 */
  line-height: inherit; /* 1 */
  color: inherit; /* 1 */
  margin: 0; /* 2 */
  padding: 0; /* 3 */
	border:0;
}

button,
select {
  text-transform: none;
}

button,
[type='button'],
[type='reset'],
[type='submit'] {
  -webkit-appearance: button; /* 1 */
  background-color: transparent; /* 2 */
  background-image: none; /* 2 */
}

:-moz-focusring {
  outline: auto;
}

:-moz-ui-invalid {
  box-shadow: none;
}

progress {
  vertical-align: baseline;
}

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

[type='search'] {
  -webkit-appearance: textfield; /* 1 */
  outline-offset: -2px; /* 2 */
}

::-webkit-search-decoration {
  -webkit-appearance: none;
}

::-webkit-file-upload-button {
  -webkit-appearance: button; /* 1 */
  font: inherit; /* 2 */
}

summary {
  display: list-item;
}

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

dialog {
  padding: 0;
}

textarea {
  resize: vertical;
}


button,
[role="button"] {
  cursor: pointer;
}

:disabled {
  cursor: default;
}

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block; /* 1 */
  vertical-align: middle; /* 2 */
}

img,
video {
	/* disable max-width solves bug img-export/propagation > nested-img-bigger */
	max-width:100%;
  height: auto;
}

[hidden] {
  display: none;
}

*{
	text-underline-offset: 0.134em;
}

```
## OUTPUT:

## page1

<img width="475" height="686" alt="image" src="https://github.com/user-attachments/assets/26a6d747-d640-4fa4-9f4e-ade5e6faee36" />

## page2

<img width="397" height="657" alt="image" src="https://github.com/user-attachments/assets/4218a947-79a9-4012-8d37-87f83357471a" />

## page3

<img width="472" height="659" alt="image" src="https://github.com/user-attachments/assets/57fce774-c326-4169-82ad-6b5296294b04" />

## page4

<img width="452" height="659" alt="image" src="https://github.com/user-attachments/assets/d5f2df7b-b87b-4692-b9bf-7fe24d1a8ea1" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
