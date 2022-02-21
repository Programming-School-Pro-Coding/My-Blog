## How to Make Auto Typing in React or Next JS ?

Hello Everyone in a new article 👋 

In this article we will Make A Auto Typing Effect with A Package called ```typewriter-effect```

if you want to start reading, start from <a href="#install">There</a>

# <h1 id="install">Installing Packages</h1>
Go to Your Command Prompt in windows or terminal in mac or termainal in visual studio code and write the following:
```bash
// With NPM
npm i typewriter-effect
// With YARN
yarn add typewriter-effect
```

# Writing Code for the auto typing
You can now in your component like about section in portfolio make a new file called ```Type.js``` and write the following code:
## In Next JS:
```js
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
```
## In React
```js
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
```
## explain the code
### Option one
option one ```strings``` have all the words you want to auto typing
### Option two
option two ```autoStart``` it is a boolean value ```true or false``` true for auto start the typing while false for don't start
### Option three
option three is ```loop``` it is a boolean value ```true or false``` true for loop on the words in option ```strings```
### Option Four
option four is ```deleteSpeed``` it is a number value that set the speed of the delete word
> The lower the number is Faster, the higher the speed is slower
