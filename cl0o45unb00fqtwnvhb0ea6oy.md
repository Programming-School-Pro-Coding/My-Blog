## Build A Blog with Astro

![Build A Blog with Astro](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1645466088168%2FX4WhLmzoF.jpg%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=3840&q=75)

Build A Blog with Astro
=======================

[![Programing-School's photo](/_next/image?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1645823553390%2FoHcqD2UHc.png%3Fw%3D200%26h%3D200%26fit%3Dcrop%26crop%3Dfaces%26auto%3Dcompress%2Cformat%26format%3Dwebp&w=640&q=75)](https://hashnode.com/@Programing-School)

[Programing-School](https://hashnode.com/@Programing-School)

·[Feb 21, 2022](https://programming-school.hashnode.dev/build-a-blog-with-astro)·2 min read

Subscribe to my newsletter and never miss my upcoming articles

Subscribe

### Table of contents

*   [Repository](https://programming-school.hashnode.dev/#heading-repository)
*   [Run the App](https://programming-school.hashnode.dev/#heading-run-the-app)
*   [create a repository](https://programming-school.hashnode.dev/#heading-create-a-repository)
*   [Deploy the app](https://programming-school.hashnode.dev/#heading-deploy-the-app)
    *   [<h2 id="there">Deploy the app to netlify</h2>](https://programming-school.hashnode.dev/#heading-deploy-the-app-to-netlify)

Hello Everyone 👋
=================

Repository
==========

Now Go to [My GitHub Repository](https://github.com/Programing-School/Astro-Blog)

And Go to `src/pages/posts/` and Add Some Your files with end with `[Your Name of the file here].md` and add this structure:

    ---
    setup: |
      import Layout from '../../layouts/BlogPost.astro'
      import Cool from '../../components/Author.astro'
    title: [The title of the post here]
    publishDate: [The data is here]
    name: [The name of the author here]
    value: [The value here]
    description: [Just the description here]
    ---
    

If you want to add a link Add this code:

    <Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />
    

The frontmatter is the value you type it in `name` field

Run the App
===========

1.  Run `npm i`
2.  Run `npm start`
3.  Go to [https://localhost:3000](https://localhost:3000/) And see the website

create a repository
===================

> If you don't what is git and how to create a github account and host your site and upload your files in it [Check out our blog](https://programing-school.hashnode.dev/learn-git-and-github)

1.  go to github and create a new repository and then copy the commands and paste it in the terminal in visual studio code or terminal on mac or command prompt and don't forgot to paste it at your directory you want to upload
2.  Run `git add .` to add the files to commit it in the next line
3.  Run `git commit -m "Deployment"`
4.  Run `git push` to push all the code to github
5.  Now Go to the repository in github and see what is there

If your code is there now Go to deployment

Deploy the app
==============

If you have a netlify account go [there](https://programming-school.hashnode.dev/#there)

1.  Go to [Netlify](https://app.netlify.com/) and Create an account

Deploy the app to netlify
-------------------------

After Creating an account let's create a new Site Then Connect to your GitHub Account and search for the repository you create before (The name of it) Then Keep all the fields and go down and click `Deploy Site`

Wait for minutes and see your site live

If you want to any questions Go down an comment

Like

[](https://programming-school.hashnode.dev/#write-comment)

[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Fbuild-a-blog-with-astro&text=Build%20A%20Blog%20with%20Astro%0D%0A%7B%20by%20%40Program39300266%20%7D%20from%20%40hashnode%0D%0A)

Share this[](https://twitter.com/share?url=https%3A%2F%2Fprogramming-school.hashnode.dev%2Fbuild-a-blog-with-astro&text=%20%40Programing-School)[](http://www.reddit.com/submit?title=Build%20A%20Blog%20with%20Astro&selftext=true&text=%20https%3A%2F%2Fprogramming-school.hashnode.dev%2Fbuild-a-blog-with-astro)