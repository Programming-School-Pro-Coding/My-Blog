## How to Make Auto Typing in React or Next JS ?

![How to Make Auto Typing in React or Next JS ?](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1645302937183%2FeZOBbzz9y.png%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=3840&q=75)

How to Make Auto Typing in React or Next JS ?
=============================================

How to Make Auto Typing in JavaScript FrameWorks from start to end
------------------------------------------------------------------

[![Programing-School's photo](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1645823553390%2FoHcqD2UHc.png%3Fw%3D200%26h%3D200%26fit%3Dcrop%26crop%3Dfaces%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=640&q=75)](https://hashnode.com/@Programing-School)

[Programing-School](https://hashnode.com/@Programing-School)

·[Feb 19, 2022](https://programming-school.hashnode.dev/how-to-make-auto-typing-in-react-or-next-js)·2 min read

Subscribe to my newsletter and never miss my upcoming articles

Subscribe

### Table of contents

*   [<h1 id="install">Installing Packages</h1>](https://programming-school.hashnode.dev/#heading-installing-packages)
*   [Writing Code for the auto typing](https://programming-school.hashnode.dev/#heading-writing-code-for-the-auto-typing)
    *   [In Next JS:](https://programming-school.hashnode.dev/#heading-in-next-js)
    *   [In React](https://programming-school.hashnode.dev/#heading-in-react)
    *   [explain the code](https://programming-school.hashnode.dev/#heading-explain-the-code)
        *   [Option one](https://programming-school.hashnode.dev/#heading-option-one)
        *   [Option two](https://programming-school.hashnode.dev/#heading-option-two)
        *   [Option three](https://programming-school.hashnode.dev/#heading-option-three)
        *   [Option Four](https://programming-school.hashnode.dev/#heading-option-four)

Hello Everyone in a new article 👋

In this article we will Make A Auto Typing Effect with A Package called `typewriter-effect`

if you want to start reading, start from [There](https://programming-school.hashnode.dev/#install)

Installing Packages
===================

Go to Your Command Prompt in windows or terminal in mac or termainal in visual studio code and write the following:

    // With NPM
    npm i typewriter-effect
    // With YARN
    yarn add typewriter-effect
    

Writing Code for the auto typing
================================

You can now in your component like about section in portfolio make a new file called `Type.js` and write the following code:

In Next JS:
-----------

    import React from "react";
    import Typewriter from "typewriter-effect";
    
    function Type() {
      return (
        <Typewriter
          options={{
            strings: [
              "Developer",
              "Web Developer",
              "Front-End Developer",
              "Back-End Developer",
              "Full-Stack Developer",
              "UI/UX Designer",
            ],
            autoStart: true,
            loop: true,
            deleteSpeed: 70,
          }}
        />
      );
    }
    
    export default Type;
    

In React
--------

    import React from "react";
    import Typewriter from "typewriter-effect";
    
    const Type = () => {
      return (
        <Typewriter
          options={{
            strings: [
              "Developer",
              "Web Developer",
              "Front-End Developer",
              "Back-End Developer",
              "Full-Stack Developer",
              "UI/UX Designer",
            ],
            autoStart: true,
            loop: true,
            deleteSpeed: 70,
          }}
        />
      );
    }
    
    export default Type;
    

explain the code
----------------

### Option one

option one `strings` have all the words you want to auto typing

### Option two

option two `autoStart` it is a boolean value `true or false` true for auto start the typing while false for don't start

### Option three

option three is `loop` it is a boolean value `true or false` true for loop on the words in option `strings`

### Option Four

option four is `deleteSpeed` it is a number value that set the speed of the delete word

> The lower the number is Faster, the higher the speed is slower

Like

[](https://programming-school.hashnode.dev/#write-comment)

[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Fhow-to-make-auto-typing-in-react-or-next-js&text=How%20to%20Make%20Auto%20Typing%20in%20React%20or%20Next%20JS%20%3F%0D%0A%7B%20by%20%40Program39300266%20%7D%20from%20%40hashnode%0D%0A)

Share this[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Fhow-to-make-auto-typing-in-react-or-next-js&text=%20%40Programing-School)[](http://www.reddit.com/submit?title=How%20to%20Make%20Auto%20Typing%20in%20React%20or%20Next%20JS%20%3F&selftext=true&text=%20https%3A%2F%2Fprogramming-school.hashnode.dev%2Fhow-to-make-auto-typing-in-react-or-next-js)