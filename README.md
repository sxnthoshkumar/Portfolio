use# Portfolio Project

This project is the beginning of my personal portfolio website built with **HTML**.  


# HTML Study Notes — Portfolio Project

This repository is the starting point of my **personal portfolio website**, built using **HTML**.  
At the same time, it also serves as a guide to understanding the basics of HTML step by step.  

## 1. What is HTML?

**HTML (HyperText Markup Language)** is the standard language used to create webpages.  
It defines the **structure** of a webpage, while **CSS** adds design and **JavaScript** adds interactivity.  

## 2. Key Concepts

### 2.1 Element
An **element** is the basic building block of HTML.  
It usually has an **opening tag**, some **content**, and a **closing tag**.  

Example:  
<p>This is a paragraph.</p>

## 2.2 Tag

A tag is what you write inside angle brackets (< >) to define an element.

Opening tag: <p>

Closing tag: </p>

## 2.3 Attribute

Attributes provide extra information about an element.
They are always written in the opening tag.

Example:

<a href="https://example.com">Visit Example</a>

href = attribute

"https://example.com" = value

## 2.4 Types of Elements

Block-level elements

Start on a new line and take up the full width.

Examples: <div>, <h1>, <p>, <section>


## 2.5 Empty (Self-closing) Elements

Some elements don’t have closing tags.

Examples:

<img src="image.png" alt="Description" />
<br />
<hr />

## 3. Basic Structure of an HTML Document

Every HTML document follows this structure:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is my first portfolio page.</p>
</body>
</html>

Explanation

1. <!DOCTYPE html> → Declares the document type as HTML5.


2. <html> → Root element.


3. <head> → Contains metadata (information about the page).


4. <body> → Contains all visible content.

## 4. Commonly Used Tags

Headings

<h1>Main Heading</h1>
<h2>Sub Heading</h2>

Paragraphs

<p>This is a paragraph of text.</p>

Links

<a href="https://example.com">Click Me</a>

Images

<img src="image.png" alt="Description">

Lists

<!-- Unordered List -->
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>

<!-- Ordered List -->
<ol>
  <li>First</li>
  <li>Second</li>
</ol>

## 5. Semantic HTML

Semantic elements clearly describe their meaning.

<header> → Top section of a page

<nav> → Navigation links

<main> → Main content area

<section> → Group of related content

<article> → Independent piece of content

<footer> → Bottom section


Example:

<header>
  <h1>My Portfolio</h1>
  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
  </nav>
</header>

## 6. Metadata & SEO Basics

Inside <head>, you can add metadata:

<meta charset="UTF-8">
<meta name="description" content="Portfolio of Santhosh Kumar, AI & ML Student">
<meta name="author" content="Santhosh Kumar">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

charset → Encoding (UTF-8 is standard).

description → Short summary (important for SEO).

author → Page author.

viewport → Makes the page responsive on mobile.

## 7. Quick Reference

Element: <p>Hello</p>

Tag: <p> (opening), </p> (closing)

Attribute: <a href="..."> → href is the attribute

Empty tag: <img />

Block elements: <div>, <p>, <h1>

Inline elements: <a>, <span>, <strong>

## 8. Next Steps in Learning

1. Add CSS for styling (colors, layout, fonts).

2. Use Flexbox/Grid for responsive design.

3. Add JavaScript for interactivity.

4. Learn about forms and inputs.

5. Explore accessibility (ARIA, alt text, labels).