# lsCoolJ.github.io

This repository was made in order to set up web pages in markdown very easily which will then be translated into html by github.
After making the website in this repository, the html is just transferred over to my github pages repository.

# Creating a new web page
### The long method
There are a few ways to create a new webpage using github pages. The first is to create a whole new repository labeled whatevever you want the file extension to be. For example, if you wanted the webpage to be named lsCoolJ.github.io/newpage, then you would name the repository newpage.

After this, you would type in a few commands in the terminal:
```
$ mkdir /path/to/source-code
$ cd /path/to/source-code
$ git clone https://github.com/lsCoolJ/projectName.git
$ cd projectName
$ git checkout -b gh-pages
$ echo "Hello, World" > index.html
$ git add index.html
$ git commit index.html -m "initial commit"
$ git push origin gh-pages
```

In order to make the page look fancy and shit, go to the repository on github.com and click Settings, and then Automatic Page Generator. This is will take you to an editor where you can input markdown code and then pick a basic layout for your page to have and then you publish it and it's done. Otherwise, you will have to know HTML or other languages to make your page look good.

### The short method
When you make an initial home page for your website, you are able to use the editor to make it look fancy in markdown and you are given options for what you want your website to look like. If you click on any of these, then github will automatically add all the necessary files and images to your website repository. From here, you can just create an HTML file with the name of the extension you want and place it in the same repository as your index.html file. For example, if you want to create a page named lscoolj.github.io/math then you would make an HTML file called math.html and include it in the repository.

You can edit the html file to include the theme in this html file and it will have the same design as your home page.

### The short-ish method

You can also create a new repository, name it anything you want, alter it using the page editor so that you can make the webpage in markdown and follow the themes provided by github, then when you publish it, just copy the html code that is generated and place it into the website repository as specified in the last method.

From here, you can do whatever you want with the new repository you made and your whole website will still be under one private repository rather than having a bunch of unprotected repositories.
This is the method that I am using this repository for.

## Learn stuff
If you need help with markdown: https://guides.github.com/features/mastering-markdown/

If you want to learn a different website scripting language such as html: http://www.w3schools.com/html/


