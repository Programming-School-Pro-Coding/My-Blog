## How to use typescript in React ?

# How to add typescript in our react project

- We normally create react-app project using ```npx create-react-app my-app``` but when we want to add typescript with it, the code is different just slightly The reason for not using npx is there are error that will be encountered as of the time of writing this but using yarn avoids those errors

```
yarn create-react-app my-app --template typescript
```

First of all, it is better to know how to use typescript normally to give plain javascript code before proceeding to using it anywhere else.

The reason it is better to know typescript first is to familiarize yourself with the basics

Typescript can be used with React, to create our plain javascript and even with our backend like node.js

The typescript react project is completed after the happy hacking! displays similar to the completion of just react project.


![zBgdQYiwV.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650322000544/yBP1uLsEb.jfif)

> Fun fact: If we have a folder already made and we want to install react into that folder, we do it this way, first cd into that folder and then
```
cd my-app
npx create-react-app .
```
if you are using yarn
```
cd my-app
yarn create-react-app .
```

To add typescript in existing react project

```
npm install --save typescript @types/node @types/react @types/react-dom @types/jest
```

and for yarn, we use
```
yarn add typescript @types/node @types/react @types/react-dom @types/jest
```

- Typescript is written by declaring data types for each variable like in C, C++, Java and some other strict data type language. So react functions in typescript can be written like this

```ts
import React from 'react'

const home: React.FC = () => {
  return (
    <div>home</div>
  )
}

export default home
```


![L0RMNqLBC.jfif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650322150066/KE3XVgVJO.jfif)

If we were to use to use react hook with typescript, we could have something like this:

```ts
import { useState } from "react"

interface messageType{
    error: String,
    success: String
}

const Home: React.FC = () => {
    const [user, setUser] = useState<messageType>();
```

The interface is a way of declaring the types, we could also do like this:
```ts
const Home: React.FC = () => {
    const [user, setUser] = useState<{
    error: String,
    success: String
}>();
```

or by replacing interface with type

```ts
import { useState } from "react"

type messageType = {
    error: String,
    success: String
}

const Home: React.FC = () => {
    const [user, setUser] = useState<messageType>();
```

We could also set data type of props as well

```ts
const Home: React.FC<{messageCode:Number}> = ({ messageCode }) => {
```

This is just one of the ways of using typescript in react. I really hope this was helpful
