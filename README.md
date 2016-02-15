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

```
A semantic html tag uses a word that describes what it does.  
<header></header	//semantic
<nav><nav>		    //semantic
<div></div>			  //non-semantic
<span></span>	  	//non-semantic
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
If an image can’t be displayed, the alt attribute text describes what the image would have been.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
The head element contains information relevant to the page that does render on the actual page itself, such as the title, scripts, styles, and meta information.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```
margin  : Defines the distance between an element's border and adjacent elements' borders.
border  : Inserts a "wall" around an element.
padding : Defines the distance between an element's content and its border.
___     : Defines the width of an element.
outline : Overlays a "wall" on top of an element.
___     : Defines the distance between the center of an element and the center of the adjacent element.
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
1. Directly inside the html element
2. The <head> of the html document
3. Separate style sheet
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

```
A fork copies the repository to your Github account and a clone downloads the repository to your computer.
```

### Question 9

How is `git pull` related to `git fetch`?

```
Git fetch brings the changes made to a remote repository to your local machine.
Git pull executes a git fetch and then automatically merges those changes.
```
