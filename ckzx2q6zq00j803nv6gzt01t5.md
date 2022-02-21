## Build A Blog with Astro

<h1>Hello Everyone 👋 </h1>

# Repository
Now Go to [My GitHub Repository](https://github.com/Programing-School/Astro-Blog)

And Go to ```src/pages/posts/``` and Add Some Your files with end with ```[Your Name of the file here].md``` and add this structure:
```md
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
```

If you want to add a link Add this code:
```md
<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />
```

The frontmatter is the value you type it in ```name``` field

# Run the App
1. Run ```npm i```
2. Run ```npm start```
3. Go to [https://localhost:3000](https://localhost:3000) And see the website

# create a repository
> If you don't what is git and how to create a github account and host your site and upload your files in it [Check out our blog](https://programing-school.hashnode.dev/learn-git-and-github)

1. go to github and create a new repository and then copy the commands and paste it in the terminal in visual studio code or terminal on mac or command prompt and don't forgot to paste it at your directory you want to upload
2. Run ```git add .``` to add the files to commit it in the next line
3. Run ```git commit -m "Deployment"```
4. Run ```git push``` to push all the code to github
5. Now Go to the repository in github and see what is there

If your code is there now Go to deployment

# Deploy the app
If you have a netlify account go [there](#there)
1. Go to [Netlify](https://app.netlify.com) and Create an account

## <h2 id="there">Deploy the app to netlify</h2>
After Creating an account let's create a new Site
Then Connect to your GitHub Account and search for the repository you create before (The name of it) Then Keep all the fields and go down and click ```Deploy Site```

Wait for minutes and see your site live

If you want to any questions Go down an comment

%%[youtube]

# Thank you for reading 📖 