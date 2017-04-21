# Writing Code - Dinner Menu

In this exercise we will be creating a digital dinner menu.

## Step 1

Download and install the text editor atom from [atom.io](https://atom.io/)

## Step 2

Create a new file on your computer called "menu.html".

Copy and paste the following code into it.

```
<!DOCTYPE html>
<html>
<head>
  <title>Title</title>
</head>
<body>
  <h1>Hello</h1>
 </body>
</html>
```

## Step 3

In this code there is a `<head>` section and a `<body>` section. 

All html pages require these sections. 

The `<head>` section is data about the webpage, including the title of the page as it should appear in the browser
header, links to the css to style the page with and data for search engines to help them rank your page. 

The `<body>` section is where the content of the page goes - in other words what you see in the browser window.

We are going to change the title of the page.

Find the bit of code inside the `<head>` tag that looks like this:

```
<title>Title</title>
```

Change the 'Title' to say 'Dinner Menu'.

## Step 4

Save your work. Open your browser.

Navigate to your page by putting the file path (location of the file on your machine) precceded by `file://` into the URL bar. 

An example might be:

```
file:///Users/your-name/Documents/mums-in-tech/menu.html
```

When you have done this you should see your new title in the title bar of the browser. 

## Step 5

Now we are going to change the code in the `<body>` to show our dinner menu.

Change the contents of the `<h1>` tag to say "Menu". Save your changes and reload your page.

## Step 6

For each course we are going to need a heading and some text underneath. 

Add the following code on a new line underneath your `<h1>` tag.

```
 <h2>Main Course</h2>
```

As you can see, when the page is rendered on the right hand side, the text you have just added is a little smaller than the text in the `<h1>` tag.

There are 6 different heading tags you can use, from 1 the largest to 6 the smallest. 

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>

## Step 7

We are now going to add the dish to our course. 

Underneath your `<h2>` tag, add the following code:

```
<p>Spaghetti Bolognese</p>
```

This is the `<p>` tag, which stands for paragraph. 

## Step 8

We are now going to add a picture to our menu. 

Underneath your `<p>` tag, add the following code:

```
<img width="500" src="https://upload.wikimedia.org/wikipedia/commons/8/85/22_West_-_dining_table.jpg"/>
```
This should add an image to your menu. 

The image tag, as you can see, is a little different to the other tags we have seen so far. 

Instead of having two corresponding tags with an opening tag and a closing tag, it self closes at the end. 

Inside the tag, you are also setting a width and a source (src). The src is telling the browser the location on the web
of the image you want to appear. Try pasting the address in a new tab to see what happens. 

The width is to let the browser know how large the image to be displayed is. Try changing it (or removing it) to see what happens. 

This image comes from wikimedia commons, which has open source media which is free to use. Visit wikimedia and try finding a 
different (free to use) picture. 

If you are stuck for ideas, here is a list of more tables.

https://commons.wikimedia.org/wiki/Category:Dining_tables

## Step 9

Using what you learned to:

+ Add some more courses to your menu.
+ Add some more images - maybe decorative or one for each course.

Congratulations, you wrote some code!




