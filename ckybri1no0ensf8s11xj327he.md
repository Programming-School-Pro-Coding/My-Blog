## Navbar with flexbox

# Hello 👋

<p>Today we will create a responsive navigation bar with flexbox</p>

1. Create Files <br>

Create a new html file for html code <br>
Create a new CSS File for CSS Code or use style tag ```<style></style>``` and we but style tag in html file in head tag

2. Html 

1. Default Html Tags

There is A Default Html Tags must but it in your html file as follow:

```html
<!DOCTYPE html>
<html>
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Navigation bar with Flexbox</title>
</head>
<body>
          
</body>
</html>
```

2. Header Tag

There is a Header tag ```<header></header>``` we put all header components to form header in the end

```html
<!DOCTYPE html>
<html>
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Navigation bar with Flexbox</title>
</head>
<body>
          <header>
                    
          </header>
</body>
</html>
```

3. But All header components

We will put all header components as logo in the left and some links in the right

```html
<!DOCTYPE html>
<html>
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Navigation bar with Flexbox</title>
</head>
<body>
          <header>
                    <h1> Programing-School </h1>
                    <br>
                    <ul>
  	                      <li><h4>Home</h4></li>
                          <li><h4>About</h4></li>
                          <li><h4>Products</h4></li>
                    </ul>
          </header>
</body>
</html>
```

4. But All classes and ids

There are classes and ids to style it only:

```html

<!DOCTYPE html>
<html>
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Navigation bar with Flexbox</title>
</head>
<body>

    <header class="flex-container">
       <h1 class="logo"> Programing-School </h1>
       <br>
       <ul>
  	      <li class="hoverli"><h4>Home</h4></li>
          <li class="hoverli"><h4>About</h4></li>
          <li class="hoverli"><h4>Products</h4></li>
       </ul>
     </header>
</body>
</html>
```


3. Put CSS in the Website

1. Put the flex-container style

```css
.flex-container {
  display: flex;
  flex-wrap: wrap;
  background-color: DodgerBlue;
  height: 70px;
  top: 0;
  margin: 0;
  padding: 0;
}
```

We change the display ```display ``` to flex to use flexbox and but the other styles as previous

2. Put Unordered list style
```css
.flex-container ul {
  list-style: none;
  display: flex;
  margin-top: 3px;
  position: relative;
  flex-direction: row;
  margin-left: 700px;
}
```

3. Put Unordered list item
```css
.flex-container > ul li {
  cursor: pointer;
  height: 50px;
  background-color: #f1f1f1;
  width: 75px;
  margin: 10px 20px;
  text-align: center;
  font-size:  15px;
  flex-direction: row;
  float: left;
  transition: 1s;
  list-style: none;
}
```

4. Put logo style
```css
.logo {
	margin: 20px;
    color: #f2f2f2;
    font-size: 25px;
    max-width: 100%;
	height: auto;
    flex-direction: row;
}
```

5. Put All Hovers
```css
.hoverli:hover {
  background-color: burlywood;
}
```

6. Put Code who make the navbar responsive (Media Queries)
```css
@media (max-width: 668px) {
  .flex-container ul {
  	margin-left: 0px;
  }
}
```


Want to learn [html](https://programing-school.hashnode.dev/learn-html-create-your-first-html-web-page) and [CSS](https://programing-school.hashnode.dev/learn-css-and-its-syntax) Follow the previous links

