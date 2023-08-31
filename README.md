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

5. Lists
   1. Unordered Lists `<ul>`
   2. Ordered Lists `<ol>`
      
6. Tables
   1. Creating Tables `<table>`
   2. Table Rows `<tr>`
   3. Table Headers `<th>`
   4. Table Data `<td>`

7. Forms
   1. Form Structure `<form>`
   2. Text Input `<input type="text">`
   3. Password Input `<input type="password">`
   4. Radio Buttons `<input type="radio">`
   5. Checkboxes `<input type="checkbox">`
   6. Dropdown Menus `<select>`
   7. Textareas `<textarea>`
   8. Submit Buttons `<input type="submit">`

8. Divisions and Spans
   1. Divisions `<div>`
   2. Spans `<span>`

9. Semantic Elements
   1. Headers `<header>`
   2. Navigation `<nav>`
   3. Main Content `<main>`
   4. Articles `<article>`
   5. Sections `<section>`
   6. Asides `<aside>`
   7. Footers `<footer>`

10. Comments
    1. Adding Comments `<!-- -->`

11. How to make everything more beautiful
    1. Style
12. Ways to give style
    1. Style attribute
    2. Style tag`<style>`
    3. Link `<link>`
   
      
# 1. Introduction to HTML
# What is HTML ??

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

## 2.HTML Elements and tags

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
## 4.Adding images
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

## 5.Lists

### unordered lists

```html
<ul>
    <li>List item1<li>
    <li>List item2<li>
    <li>List item3<li>
    <li>List item4<li>
    <li>List item5<li>
    <li>List item6<li>
</ul>
```

### Ordered lists

```html
<ol>
    <li>List item1<li>
    <li>List item2<li>
    <li>List item3<li>
    <li>List item4<li>
    <li>List item5<li>
    <li>List item6<li>
</ol>
```

# 6.Tabels

<img src="https://www.codewithfaraz.com/img/Mastering%20the%20Table%20Tag%20in%20HTML%20A%20Comprehensive%20Guide.jpg">

# 11.What is style:
you can give style to elements of html with css to make them more beautiful.
For example for a `<p>` you can change the Font size, Font family , Font weight and etc.

# 12.Ways to give style:

## style attribute:

```html
<p style= our style></p>
```

## style tag `<style>`

you must use this tag in head.

### Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My page title</title>

    <style>

      the style that we want

    </style>
</head>
<body>
     <!-- Content -->
</body>
</html>
```

## stylesheet link

### Example:

```html
<!DOCTYPE html>
<html>
<head>
    <title>My page title</title>
    <link rel="stylesheet" href="filename.css" type=""text/css>
    
</head>
<body>
     <!-- Content -->
</body>
</html>

```

Don't worry if i don't mention something in this readme because you can find them in HTMLcheatsheet.html

If you wanna khow more about CSS, 
you can visit my another repository
(CSS for begginers)






