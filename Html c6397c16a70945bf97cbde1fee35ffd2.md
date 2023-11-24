# Html

1. Aside: to display content aside from the content it is placed in.

```html
<aside> 
</aside>
```

1. A clickable button

```html
<button type="button">Click Me</button>
```

1. A description list

```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```

1. Details: you can close and open

```html
<details>
  <summary>Epcot Center</summary>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>
```

1. Fieldset: for a group related elements in a form

```html
<!DOCTYPE html>
<html>
<body>

<h1>The fieldset element</h1>

<form action="/action_page.php">
 <fieldset>
  <legend>Personalia:</legend>
  <label for="fname">First name:</label>
  <input type="text" id="fname" name="fname"><br><br>
  <label for="lname">Last name:</label>
  <input type="text" id="lname" name="lname"><br><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>
  <label for="birthday">Birthday:</label>
  <input type="date" id="birthday" name="birthday"><br><br>
  <input type="submit" value="Submit">
 </fieldset>
</form>

</body>
</html>
```

1. An iframe element: to display a mini version of the website

```html
<!DOCTYPE html>
<html>
<body>

<h1>The iframe element</h1>

<iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials">
</iframe>

</body>
</html>
```

1. Label: defines a label for several elements

```html
<!DOCTYPE html>
<html>
<body>

<h1>The label element</h1>

<p>Click on one of the text labels to toggle the related radio button:</p>

<form action="/action_page.php">
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label><br><br>
  <input type="submit" value="Submit">
</form>

</body>
</html>
```

1. Navigation: to set the navigation links

```html
<nav>
  <a href="/html/">HTML</a> |
  <a href="/css/">CSS</a> |
  <a href="/js/">JavaScript</a> |
  <a href="/python/">Python</a>
</nav>
```

1. Option list: A drop-down list

```html
<!DOCTYPE html>
<html>
<body>

<h1>The option element</h1>

<label for="cars">Choose a car:</label>

<select id="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="opel">Opel</option>
  <option value="audi">Audi</option>
</select>
  
</body>
</html> 
```

1. A div tag

```html
<!DOCTYPE html>
<html>
<head>
<style>
.myDiv {
  border: 5px outset red;
  background-color: lightblue;    
  text-align: center;
}
</style>
</head>
<body>

<h1>The div element</h1>

<div class="myDiv">
  <h2>This is a heading in a div element</h2>
  <p>This is some text in a div element.</p>
</div>

<p>This is some text outside the div element.</p>

</body>
</html>
```

1. Search 

```html
<!DOCTYPE html>
<html>
<body>

<h1>The search Element</h1>

<search>
  <form>
    <input name="fsrch" id="fsrch" placeholder="Search W3Schools">
  </form>
</search>

</body>
</html>
```

1. An input element:

![Screenshot 2023-11-18 104120.png](Html%20c6397c16a70945bf97cbde1fee35ffd2/Screenshot_2023-11-18_104120.png)

1. Checkbox: that can select 1 or more options

```html
<form>

<input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">

<label for="vehicle1"> I have a bike</label><br>

<input type="checkbox" id="vehicle2" name="vehicle2" value="Car">

<label for="vehicle2"> I have a car</label><br>

<input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">

<label for="vehicle3"> I have a boat</label>

</form>
```

1. Template: to hold some content that will be hidden when the page loads.

```html
<!DOCTYPE html>
<html>
<body>

<h1>The template Element</h1>

<p>Click the button below to display the hidden content from the template element.</p>

<button onclick="showContent()">Show hidden content</button>

<template>
  <h2>Flower</h2>
  <img src="img_white_flower.jpg" width="214" height="204">
</template>

<script>
function showContent() {
  let temp = document.getElementsByTagName("template")[0];
  let clon = temp.content.cloneNode(true);
  document.body.appendChild(clon);
}
</script>

</body>
</html>
```

1. The wbr element: a text with word break opportunities

```html
<!DOCTYPE html>
<html>
<body>

<h1>The wbr element</h1>

<p>Try to shrink the browser window, to view how the very long word in 
the paragraph below will break:</p>

<p>This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.</p>

</body>
</html>
```

1.  Class: specifies one or more class-names for an element

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1.intro {
  color: blue;
}

p.important {
  color: green;
}
</style>
</head>
<body>

<h1 class="intro">Header 1</h1>
<p>A paragraph.</p>
<p class="important">Note that this is an important paragraph. :)</p>

</body>
</html>
```