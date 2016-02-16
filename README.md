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

``If an HTML tag is "semantic", it clearly describes the meaning of whatever the tag is naming.
examples:
semantic: <header></header>, <nav></nav>
<footer>
      <a href='#'>Facebook</a> |
      <a href='#'>Twitter</a> |
      <a href='#'>Instagram</a> |
      <a href='#'>LinkedIn</a>
    </footer>
non-semantic: <div></div> and <span></span>
<div>
   <ul>
     <li><span class="role">General Assembly</span><span class="company"> WDI — 2013</span></li>
     <li><span class="role">Queens College</span><span class="company"> - B.A. 1923</span></li>
     <li><span class="role">Brooklyn Etiquette School For Girls</span> <span class="company"> 1920(Honors)</span></li>
   </ul>
   </div> ****div is not semantic
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```The 'alt' attribute provides "alternate text" to accompany a photo. This can be read by the user if, for example, the photo is unable to load or the user is vision impaired and unable to see the image. The text explains the image and the 'alt' is necessary to include, especially if there are no captions with the photo.  
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```The data included in the 'head' tag is not displayed on the page. It may include a title that appears on the browser tab, links to other pages on the site as well as to css or js code.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_margin__: Defines the distance between an element's border and adjacent      elements' borders.
_border_: Inserts a "wall" around an element.
_padding__: Defines the distance between an element's content and its border.
___: Defines the width of an element.
_outline__: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the     adjacent element.
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
1. external css page that is linked with the html page with the code: <link href='css_file_name' rel="stylesheet"> (most specific)
2. css code on the html page withing the <head></head> section using the tag <style></style>
3. css elements in the html tags using "style= ..." inside the html tags on the code. (least specific)
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
A fork moves a github repository from a parent repository in github to your own account on github-- but the repository stays in github and does not go to your local repo. A clone copies a repository from the remote repo on github to the local repo on the computer.
```

### Question 9

How is `git pull` related to `git fetch`?

```git fetch brings new branches from a remote repo and to a local repo. Git pull also fetches the new branches from a remote repo and brings them to a local repo, but it ALSO merges the new branch and original/current branch together. 
```
