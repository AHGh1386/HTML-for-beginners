# HTML for beginners

## HTML Documentation for Beginner Web Developers

1. Introduction to HTML
   1. What is HTML?
   2. Basic Structure of an HTML Document
   3. HTML Elements and Tags

2. Text and Headings
   1. Paragraphs `<p>`
   2. Headings `<h1>` to `<h6>`
   3. Line Breaks `<br>`
   4. Horizontal Rules `<hr>`

3. Links
   1. Anchor Tags `<a>`


4. Images
   1. Adding Images `<img>`
   2. Image Attributes (Width, Height, Alt)


# 1. Introduction to HTML
# What is HTML

HTML stands for HyperText Markup Language. It is a standard markup language for web page creation. It allows the creation and structure of sections, paragraphs, and links using HTML elements (the building blocks of a web page) such as tags and attributes. 


## Basic Structure of an HTML Document
```html
<!DOCTYPE html>
<html>
<head>
    <title>My page title</title>
</head>
<body>
    <!-- Content -->
</body>
</html>
```

## HTML Elements and tags

<img src="https://www.scmgalaxy.com/tutorials/wp-content/uploads/2021/05/html-elements.png" alt="html">
<img src="https://images.slideplayer.com/29/9492814/slides/slide_2.jpg">


## Text and Headings

### Headings h1 to h6

<img src="https://www.schudio.com/wp-content/uploads/2016/10/html-headings.png?x50398">

### Paragraphs `<p>` 

```html
    <p> THis is a paragragh </p>
    <p> This is another paragragh </p>
```

### Line Breaks `<br>` <br>
Headings define the hierarchy of the text on the page.
```html
<p>This is the first line.<br>This is the second line.</p>

```
### Horizontal Rules `<hr>`
Horizontal rules create a visual break between content.
```html
<p>This is some content.</p>
<hr>
<p>This is more content.</p>

```

## 3. Links
### Anchor Tags `<a>`
Anchor tags are used to create hyperlinks that allow users to navigate between web pages.
```html
<a href="https://www.google.com">Visit google</a>
```
You can alson make an image to a link:

```html
<a href = "https://www.google.com"><img src="Link of an image"></a>
```
### Adding image
You can add images from the internet or you can add images from your files.

```html
<img src="Link of the image">
<img src="NameOftheFolder/image.jpg>
```

### Image Attributes (Width, Height, Alt)

width and height are clear. 
alt is for when your image has some problems in uploading:
```html
<img src="linkOfaImage" alt="hello">
```
In this code if your image does not upload, it will write something to say that what this image is about.


