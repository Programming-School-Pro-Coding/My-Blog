## Learn Html, Create Your First Html Web page

![Learn Html, Create Your First Html Web page](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1641629383999%2F2WfAqDSBu.jpeg%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=3840&q=75)

Learn Html, Create Your First Html Web page
===========================================

[![Programing-School's photo](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1645823553390%2FoHcqD2UHc.png%3Fw%3D200%26h%3D200%26fit%3Dcrop%26crop%3Dfaces%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=640&q=75)](https://hashnode.com/@Programing-School)

[Programing-School](https://hashnode.com/@Programing-School)

·[Jan 8, 2022](https://programming-school.hashnode.dev/learn-html-create-your-first-html-web-page)·5 min read

Subscribe to my newsletter and never miss my upcoming articles

Subscribe

Hello
=====

We will learn About Html
------------------------

HTML (hypertext markup language) is the Building language of the internet. It provides the structure of the webpage and is how you put the content (paragraphs, images, navigation bars, headers, Heading, Subheading, etc...) onto Your website. The web started out as a way of sharing text documents and HTML reflects this. What you end up with often looks like a Microsoft Word document. Later you can add other languages like CSS and JavaScript to add styles , Animations and interactivity to your webpage but if you just want to write some code and see it displayed in your browser then this is the tutorial for you. And it’s a pretty awesome feeling when it works.

When Your Create A Website from the first you should write this code:

    
    <!DOCTYPE HTML>
    <html>
        <head>
            <title></title>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-    width,initial-scale=1">
        </head>
        <body>
        </body>
    </html>
    

Tags
====

Before we get started a quick note on tags. HTML is made up of tags that you can recognize from the pointy brackets (<>). There are 2 types of tags: regular and self-closing tags. A regular tag will start with an HTML tag eg `<body>`, which will then often contain some content, called children, before finishing with a closing tag, which will start with a “/” eg `</body>`. A self-closing tag will just contain one tag and will end with a “/” inside the brackets eg`<meta charset="UTF-8" />`

This is a regular tag

    
    <p>A Regular Paragraph Tag !!!<p>
    

This is a self closing tag

    <img >
    

A closer look
=============

Here we’ll have a closer look at what is in the boilerplate code. If that’s not for you and you want to jump into making stuff happen, then jump ahead to the next section.

let’s have a look at the code line by line and figure out what it’s doing

    <!DOCTYPE html>
    

This tells the browser to expect an HTML document. It’s not an HTML tag but will give the browser information on how to handle our code.

    <html lang="en">
    

Everything we write in HTML will be wrapped in an HTML tag. This is the opening tag and you will find the closing one at the end of the document.

    <head>
    

Everything between the opening and closing head tags is not displayed on the page. This gives the browser extra information about our webpage and how to display it.

    <title></title>
    

Text between these tags is the title of our webpage. Remember that information in the header is not displayed on the webpage. This won’t give you a heading on your webpage but will display the name of the page in the tab at the top of the browser.

    <meta charset="UTF-8" />
    

charset stands for character set and has to do with the way text characters are displayed. Not all languages can be displayed in all character sets. The computer needs to know how to display characters such as “збаша ሰላም”. UTF-8 is used because it’s has a universal character set which allows for writing in many different languages.

    <meta name="viewport" content="width=device-width,initial-scale=1" />
    

This tag is important for viewing content on mobile devices. It essentially tells the browser that the width of the screen should be the full width of the device. That saves you trying to navigate a website on your mobile where you have to scroll around from one side of the page to the other. Some of us who are old enough will remember this being standard in the bad old days of mobile internet.

    
    </head>
    <body>
    </body>
    </html>
    

Here we have a closing of head and html tags that we were opened earlier and between them `body` tag that it have all **All Website Content(Heading, Paragraph, img, etc...)**.

Let's see some content you can add in body tag !!!

Adding Your Content
===================

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1647105768824/nNPWjAjbh.jpeg)

Heading
-------

Let's Add some Heading To Our Web Page Between The Opening Tag and Closing Tag which the two ✌ put in `<body>` and write `<h1>`, Then Add some content then close it with `</h1>` Click Save or Ctrl + s, Then open Your Webpage then refresh and tag a look, Congrats 🎉 You have Add some content! if you have a trouble it should look something like this:

    <body>
        <h1>Programing-School</h1>
    </body>
    

Subtitles
---------

Now let’s create a subtitle. We can use the `<h2></h2>` tags for this. Just add your subtitle between the tags as you did with the heading.

    <body>
        <h2>Programing-School</h2>
    </body>
    

Paragraph
---------

Next, let’s add some text. Below your heading, we’ll add a paragraph tag `<p></p>` and write some text between the tags. Have another look at the webpage (don’t forget to hit refresh). It should be starting to come together now.

Lists
-----

There are 2 types of lists in html, there are ordered list and unordered list, Ordered lists display numbered bullet points and unordered lists contain regular bullet points, Ordered list create as follow `<ol></ol>` tags and unordered list `<ul></ul>`, Inside the elements you can add anything but there are two tags called list item and we create it as follow `<li></li>` tags and you can add any content in it like this:

    <body>
        <ul>
            <li>Programing-School</li>
            <li>Mohamed Ehab</li>
            <li>Yourname@gmail.com</li>
        <ul>
    </body>
    

Title
-----

Finally, let’s change the title. Navigate to the `<title></title>` tags in the head section and write your website title in between the two tags. It should look something like this: `<title>Programing-School</title>`. Your webpage title will now be displayed in your tab at the top of the page.

Putting it all together

![EAGAUQzHW.jpeg](https://cdn.hashnode.com/res/hashnode/image/upload/v1647105770088/SwU_O1G5t.jpeg)

Once you’ve put it all together it should look something like this.

    
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <title>Programing-School</title>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width,initial-scale=1" />
      </head>
      <body>
        <h1>Programing-School</h1>
        <h2>Programing channel for learn all things</h2>
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Consectetur
          quasi ipsum eveniet excepturi odit eaque necessitatibus facilis aperiam
          debitis ullam quas ad, repudiandae beatae culpa nobis alias, eligendi, est
          architecto?
        </p>
        <ul>
            <li>Create An article about html</li>
            <li>Create A video</li>
            <li>Create an app for my freelance</li>
        </ul>
      </body>
    </html>
    

Congratulations you’ve created your first HTML webpage. The best way to learn is by practicing so mix up these different elements and try to create something new. If you get stuck why not send me a tweet and I’ll see if I can help [Twitter](https://twitter.com/Program39300266)

Like

[](https://programming-school.hashnode.dev/#write-comment)

[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Flearn-html-create-your-first-html-web-page&text=Learn%20Html%2C%20Create%20Your%20First%20Html%20Web%20page%0D%0A%7B%20by%20%40Program39300266%20%7D%20from%20%40hashnode%0D%0A)

Share this[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Flearn-html-create-your-first-html-web-page&text=%20%40Programing-School)[](http://www.reddit.com/submit?title=Learn%20Html%2C%20Create%20Your%20First%20Html%20Web%20page&selftext=true&text=%20https%3A%2F%2Fprogramming-school.hashnode.dev%2Flearn-html-create-your-first-html-web-page)