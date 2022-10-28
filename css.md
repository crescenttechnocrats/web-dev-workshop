# CSS

### Colors:

Colors are specified using predefined color names, or RGB, HEX, HSL values.
	
__Example__
```
<h1 style="color: DodgerBlue;">Hello World</h1>
<h1 style="background-color:rgb(255, 99, 71);">Hello World</ h1>
<h1 style="background-color:#ff6347;"> Hello World </h1>
<h1 style="background-color:hsl(9, 100%, 64%);" Hello World </h1>
```

### Width Property :
The width property sets the width of an element.

The width of an element does not include padding, borders, or margins.

The min-width and max-width properties override the width property.
 
__Example__

```
<input type="text" name="search">
<style>
    input[type=text] {width: 100px;}
    input[type=text]:focus {width: 250px;}
</style>
```

### Borders
The CSS border properties allow you to specify the style, width, and color of an element's border.                     

__Example__

```
<p class="border">CSS Border</p>
<style>
p.border {
border-style: double;
border-width: 5px;
border-color: green;
}
</style>
```

### Padding
Padding is used to create space around an element's content, inside of any defined borders.	

__Example__:

```
<div>Hello World</div>
<style>
div {
  border: 1px solid black;
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
}
</style>
```

### Margins
Margins are used to create space around elements, outside of any defined borders.

__Example__:

```
<h2>Hello World</h2>
		<style>
h2 {
 		border: 1px solid black;
  		margin-top: 100px;
  		margin-bottom: 100px;
  		margin-right: 150px;
margin-left: 80px;
}
</style>
```

### Flexbox

Flexbox is a one-dimensional layout method for arranging items in rows or columns.

__Example:__

The flex container properties are:

•	flex-direction \
•	flex-wrap \
•	flex-flow \
•	justify-content \
•	align-items \
•	align-content \


### CSS Forms

__Syntax__:

```
<form action=”url” method=”post”>
</form>
```

__Example__:

```
<!DOCTYPE html>
<html>
<style>
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<body>

<h3>FORMS</h3>

<div>
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname">
    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname">
    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>
    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>
```

### Navigation Bars

A navigation bar needs standard HTML as a base.
A navigation bar is basically a list of links, so using the `<ul>` and `<li>` elements makes perfect sense.

__Example:__

```
<!DOCTYPE html>
<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>
</head>
<body>

<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#about">About</a></li>
</ul>

</body>
</html>
```