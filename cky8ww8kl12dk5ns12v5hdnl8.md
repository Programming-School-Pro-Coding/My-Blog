## Learn CSS and its Syntax

# Hello All 👋 

## Today We will learn CSS Syntax

### CSS Definition
<strong>C</strong>ascading <strong>S</strong>tyle <strong>S</strong>heets, fondly referred to as CSS, is a simple design language intended to simplify the process of making web pages presentable.


### CSS Uses
CSS handles the look and feel part of a web page. Using CSS, you can control the color of the text, the style of fonts, the spacing between paragraphs, how columns are sized and laid out, what background images or colors are used, layout designs, variations in display for different devices and screen sizes as well as a variety of other effects.

CSS is easy to learn and understand but it provides powerful control over the presentation of an HTML document. Most commonly, CSS is combined with the markup languages HTML or XHTML.

### CSS Syntax

CSS Syntax as follow: 

```css

selection {

}

```

> This is not CSS Code this is CSS Syntax

### CSS Selectors
 There are many Selectors as {body: mention the body tag, *: this mention all the tags, html: mention the html tag, h1: mention h1 tag, etc...}

### Mention one or two or three tags
There are two ✌ words in html and we mention it in css and this words is {id, class}
We write . to mention the class
We write # to mention the id

Id is for one tag but Class is for any number of tags

we write id and class in code as follow:
Html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Learn CSS</title>
</head>
<body>
          <h1 class="logo">Programing-School</h1>
          <h2 id="sublogo">Learn CSS</h2>
          <ul class="main-links">
                    <li>CSS Definition</li>
                    <li>CSS Uses</li>
                    <li>CSS Syntax</li>
          </ul>
</body>
</html>
```
CSS:
```css
.logo {
    font-size: 20px;
    color: black;
}

.sublogo {
    font-size: 15px;
    color: blue;
}

.main-links {
    list-style: none;
}
```


### How to write CSS and style Html
1. Create Your html file like ```index.html```
2. Create Your CSS File like ```style.css```
3. Create Some Html code like this:
```html
<!DOCTYPE html>
<html lang="en">
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Learn CSS</title>
</head>
<body>
          <h1>Programing-School</h1>
          <h2>Learn CSS</h2>
          <ul>
                    <li>CSS Definition</li>
                    <li>CSS Uses</li>
                    <li>CSS Syntax</li>
          </ul>
</body>
</html>
```
4. As we learn about css syntax but we will learn css arguments as follow:
```css
body {
    background: black;
    color: white;
}
```

Congratulations 🎊 you write CSS Code

Please Don't forgot to follow me and like the post(article) to support me !!!