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
Semantic HTML is html tags that give some description of what is inside the tags.

Semantic html = <header></header>

non-semantic html = <div class="header"></div>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute shows text when the image does not load.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The <head></head> section is where we put all of the links, title and other
metadata.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin : Defines the distance between an element's border and adjacent elements' borders.

border : Inserts a "wall" around an element.
padding : Defines the distance between an element's content and its border.
___: Defines the width of an element.
outline : Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[x] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. MOST SPECIFICITY - inside an html elements tag e.g. <p styel="color:blue;">Example</p>

2. CAN BE SPECIFIC - between style tags in the html file e.g. <style>p{color:blue;}</style>

3. CAN BE SPECIFIC - link to a separate file e.g. <link rel="stylesheet" href="style.css"/>
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[x] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A fork is done on github. It makes a copy of a repo into your account.

A clone makes a copy of a repo onto your local machine
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git pull does a git fetch and then a git merge. So, git fetch is safer.
```
