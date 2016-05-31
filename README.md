# Week 01

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## HTML

### Question #1

What does it mean for an HTML tag to be "semantic"? Give an example of a short snippet of HTML written using semantic tags and non-semantic tags.

```text
A semantic tag describes its function and explains what it does.

Semantic tags make the text easier to understand for developers who have to deal with it after it has been in use (even the developer who originally created it can use this help).  It also makes possible additional automation and SEO options.  

Non-semantic example:
```
```html
<div>
  <div class=...>
  <ul>
    <li>...</li>
    <li>...</li>
  </ul>
</div>
  <div>
    <p>text....<p>
  </div>
  <div>
    <p>text...  <p>  
  </div>
</div>
```
```text
Semantic example:
```
```html
<section>
<nav>
  <ul>
    <li>...</li>
    <li>...</li>
  </ul>
</nav>
  <details>
    <p>text....<p>
  </details>
  <main>
    <p>text...  <p>
  </main>
</section>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute of the <img> tag specifies text for HTML to display if it cannot find the image specified in the src attribute.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The <head> tag contains the elements that are used to describe the document and specify information for the page, including the page title, location of script and css source files, metadata, etc.
```

## CSS
ß
### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin  : Defines the distance between an element's border and adjacent elements' borders.
outline  : Inserts a "wall" around an element.
padding  : Defines the distance between an element's content and its border.
margin  : Overlays a "wall" on top of an element.
margin  : Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1.  Most specific: inline style settings attached to the data elements inside an HTML file.  
2.  Less specific:  styles set in a <style> </style> structure in the HTML file.
3.  Least specific:  styles set in a separate file specified by a <link> statement placed in the <head> section of an HTML file.

A style set in the external file will be overridden by a style set in the internal <style> section, which in turn will be overridden by a style set directly on a display element in a page, e.g.,  <h2 style="color:red; font-weight:bold;">text</h2>
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A fork is a copy of a repository on Github that is stored on Github and remains logically connected to the original repository.  A clone is a copy of a repository that lives on a user's local machine.  
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git pull copies committed files into the current branch and merges them, while git fetch copies them over but does not merge them.  
```
