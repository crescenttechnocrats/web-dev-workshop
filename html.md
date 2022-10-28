# HTML

### Basic Tags:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

### Headings : 
HTML headings are defined with the `<h1>` to `<h6>` tags.
`<h1>` defines the most important heading. `<h6>` defines the least important heading: 

__Example:__
```
    <h1>This is heading 1</h1>
    <h2>This is heading 2</h2>
    <h3>This is heading 3</h3>
```

__Paragraphs:__

HTML paragraphs are defined with the <p> tag:

Example:
```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

__Links :__

The link's destination is specified in the href attribute. 

Example:

```
<a href="https://www.w3schools.com">This is a link</a>
```
__Images :__

HTML images are defined with the <img> tag.
The source file (src), alternative text (alt), width, and height are provided as attributes


Example:
```
<img src="image.jpg" alt="images.com" width="104" height="142">
```

__HTML Elements__

The HTML element is everything from the start tag to the end tag:
```
<tagname>Content goes here...</tagname>
```

__HTML Attributes__

•	All HTML elements can have attributes \
•	Attributes provide additional information about elements\
•	Attributes are always specified in the start tag\
•	Attributes usually come in name/value pairs like: name="value"

__HTML Tables:__

Each table cell is defined by a `<td>` and a `</td>` tag.
td stands for table data

Each table row starts with a `<tr> `and ends with a `</tr>` tag.
tr stands for table row.

Sometimes you want your cells to be table header cells. In those cases use the `<th>`tag instead of the `<td>`

tag:
th stands for table header.

```
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>

Lists :
	Unordered List:
<ul>
       <li>Coffee</li>
       <li>Tea</li>
       <li>Milk</li> 
</ul>
	Ordered List:
<ol>
       <li>Coffee</li>
       <li>Tea</li>
       <li>Milk</li> 
</ol>

```

__Iframes:__

An inline frame is used to embed another document within the current HTML document.

```
	<iframe src="url" title="description"></iframe>
```