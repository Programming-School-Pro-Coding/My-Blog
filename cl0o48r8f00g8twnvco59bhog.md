## Navbar with flexbox

![Navbar with flexbox](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Funsplash%2FMI9-PY5cyNs%2Fupload%2Fv1642002894210%2FpbXRt9A_L.jpeg%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=3840&q=75)![](https://cdn.hashnode.com/res/hashnode/image/upload/v1647105758633/cKs06Jpmh.json)

Photo by

[Markus Spiske](https://unsplash.com/@markusspiske?utm_source=Hashnode&utm_medium=referral) on [Unsplash](https://unsplash.com/?utm_source=Hashnode&utm_medium=referral)

Navbar with flexbox
===================

[![Programing-School's photo](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1645823553390%2FoHcqD2UHc.png%3Fw%3D200%26h%3D200%26fit%3Dcrop%26crop%3Dfaces%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=640&q=75)](https://hashnode.com/@Programing-School)

[Programing-School](https://hashnode.com/@Programing-School)

·[Jan 12, 2022](https://programming-school.hashnode.dev/navbar-with-flexbox)·2 min read

Subscribe to my newsletter and never miss my upcoming articles

Subscribe

### Table of contents

*   [Hello 👋](https://programming-school.hashnode.dev/#heading-hello)

Hello 👋
========

Today we will create a responsive navigation bar with flexbox

1.  Create Files  
    

Create a new html file for html code  
Create a new CSS File for CSS Code or use style tag `<style></style>` and we but style tag in html file in head tag

1.  Html
    
2.  Default Html Tags
    

There is A Default Html Tags must but it in your html file as follow:

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
    

1.  Header Tag

There is a Header tag `<header></header>` we put all header components to form header in the end

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
    

1.  But All header components

We will put all header components as logo in the left and some links in the right

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
    

1.  But All classes and ids

There are classes and ids to style it only:

    
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
    

1.  Put CSS in the Website
    
2.  Put the flex-container style
    

    .flex-container {
      display: flex;
      flex-wrap: wrap;
      background-color: DodgerBlue;
      height: 70px;
      top: 0;
      margin: 0;
      padding: 0;
    }
    

We change the display `display` to flex to use flexbox and but the other styles as previous

1.  Put Unordered list style
    
        .flex-container ul {
        list-style: none;
        display: flex;
        margin-top: 3px;
        position: relative;
        flex-direction: row;
        margin-left: 700px;
        }
        
    
2.  Put Unordered list item
    
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
        
    
3.  Put logo style
    
        .logo {
         margin: 20px;
         color: #f2f2f2;
         font-size: 25px;
         max-width: 100%;
         height: auto;
         flex-direction: row;
        }
        
    
4.  Put All Hovers
    
        .hoverli:hover {
        background-color: burlywood;
        }
        
    
5.  Put Code who make the navbar responsive (Media Queries)
    
        @media (max-width: 668px) {
        .flex-container ul {
           margin-left: 0px;
        }
        }
        
    

Want to learn [html](https://programing-school.hashnode.dev/learn-html-create-your-first-html-web-page) and [CSS](https://programing-school.hashnode.dev/learn-css-and-its-syntax) Follow the previous links

Like

[](https://programming-school.hashnode.dev/#write-comment)

[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Fnavbar-with-flexbox&text=Navbar%20with%20flexbox%0D%0A%7B%20by%20%40Program39300266%20%7D%20from%20%40hashnode%0D%0A)

Share this[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Fnavbar-with-flexbox&text=%20%40Programing-School)[](http://www.reddit.com/submit?title=Navbar%20with%20flexbox&selftext=true&text=%20https%3A%2F%2Fprogramming-school.hashnode.dev%2Fnavbar-with-flexbox)