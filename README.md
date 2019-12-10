# Code-2

## Startseite   

```css
html {
    color: white;	
}
header {
	background-color: white;
	margin-left: 20px;
}
h1 {
	float: left;
	color: black;
}
body {
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
nav {
	background-color: grey;
}
section {
	background-color: green;
	float: left;
	width: 63%;
	margin: 0 1,5%;
	clear: left;
}
aside {
	background-color: red;
	float: right;
	margin: 0 1,5%;
	width: 34%;
}
footer {
	background-color: white;
	clear: both;
	margin-left: 0;
	margin-right: 0;
	color: black;
	float: left;
	width: 100%;
}
small {
	float: right;
	background-color: grey;
	width: 100%;
}
a {
	color: black;
}
.navigation {
	float: right;
	width: 40%;
	margin-top: 67px;
}
.Name {
	float: left;
}
```
## Registrierung 

```css
html{
    color: white; 
}
header{
  background-color: white;
  margin-left: 20px;
}
h1{
  color: black;
  height: 41px;
}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
section{
  background-color: green;
  float: left;
  width: 15%;
  height: 394px
}
nav{
  background-color: grey;
}
footer{
  background-color: white;
  clear: both;
  margin-left: 0;
  margin-right: 0;
  color: black;
  float: left;
  width: 100%;
}
small{
  float: right;
  background-color: grey;
  width: 100%;
}
a{
  color: black;
}
* {box-sizing: border-box}

input[type=text], input[type=password] {
  width: 100%;
  padding: 0px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}
input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}
button:hover {
  opacity:1;
}
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}
.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}
.container {
  padding: 16px;
}
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}
@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
    width: 100%;
  }
}
.navigation {
  float: right;
  width: 40%;
  margin-top: 67px;
}
.Name{
  float: left;
}
.solve{
    clear: left;
    background-color: grey;
}
.middle{
  width: 70%;
}
.sides{
  background-color: grey;
}
```

## Login
```css
html{
    color: white;	
}
header{
	background-color: white;
	margin-left: 20px;
}
h1{
	color: black;
	height: 41px;
}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
section{
	background-color: green;
	float: left;
	width: 15%;
	height: 394px
}
nav{
	background-color: grey;
}
footer{
	background-color: white;
	clear: both;
	margin-left: 0;
	margin-right: 0;
	color: black;
	float: left;
	width: 100%;
}
small{
	float: right;
	background-color: grey;
	width: 100%;
}
a{
	color: black;
}
form {
  border: 3px solid #f1f1f1;
}
input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}
button:hover {
  opacity: 0.8;
}
.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}
.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}
.container {
  padding: 16px;
}
span.psw {
  float: right;
  padding-top: 16px;
}
@media screen and (max-width: 300px) {
  span.psw {
    display: block;
    float: none;
  }
  .cancelbtn {
    width: 100%;
  }
 }
.navigation {
	float: right;
	width: 40%;
	margin-top: 67px;
}
.Name{
	float: left;
}
.solve{
    clear: left;
    background-color: grey;
}
.middle{
	width: 70%;
}
.sides{
	background-color: grey;
}
```

## Kontaktformular
```csss
html{
    color: white;	
}
header{
	background-color: white;
	margin-left: 20px;
}
h1{
	color: black;
	height: 41px;
}
body{
   background-color: white;
   margin-left: 0;
   margin-right: 0;
   font-size: 17px;
}
section{
	background-color: green;
	float: left;
	width: 15%;
	height: 394px
}
nav{
	background-color: grey;
}
footer{
	background-color: white;
	clear: both;
	margin-left: 0;
	margin-right: 0;
	color: black;
	float: left;
	width: 100%;
}
small{
	float: right;
	background-color: grey;
	width: 100%;
}
a{
	color: black;
}
input[type=text]{
	width: 30%;
	border: 1px solid #ccc
	border-radius: 4px;
	box-sizing: border-box;
	margin-top: 6px;
	margin-bottom: 16px;	
}
input[type=submit]{
	background-color: #4CAF50
	color: white;
	padding: 12px 20px;
	border: none;
	border-radius: 4px
	cursor: pointer;
}
input[type=submit]:hover {
  background-color: grey;
}
textarea{
	width: 85%;
}
.navigation {
	float: right;
	width: 40%;
	margin-top: 67px;
}
.Name{
	float: left;
}
.solve{
    clear: left;
    background-color: grey;
}
.middle{
	width: 70%;
}
.sides{
	background-color: grey;
}
```
