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
Semantic tags describe its meaning clearly:

SEMANTIC
<head>                                     
<title>Tic Tac Toe</title>
<link rel="stylesheet" href="style.css" />
</head>
<body>
NON_SEMANTIC
<div class="board">
  <div id="a" onclick="playerMove('#a')"></div>
  <div id="b" onclick="playerMove('#b')"></div>
  <div id="c" onclick="playerMove('#c')"></div>
  <div id="d" onclick="playerMove('#d')"></div>
  <div id="e" onclick="playerMove('#e')"></div>
  <div id="f" onclick="playerMove('#f')"></div>
  <div id="g" onclick="playerMove('#g')"></div>
  <div id="h" onclick="playerMove('#h')"></div>
  <div id="i" onclick="playerMove('#i')"></div>
</div>
<p>My mother has <span style="color:blue">blue</span> eyes.</p>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>

```

```text
alt attribute specifies an alternate text for an image, in case the image cannot be displayed
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text

The <head>  tag  element is a container for metadata (data about the HTML document - it is not displayed).
The HTML <head> element provides general information (metadata) about the document, including its title and links to its scripts and style sheets (Elements that can be used inside a <head> element: <title>(REQUIRED), <base>, <link>, <style>, <meta>, <script>, <noscript>)

and </head> head end tag

```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin: Defines the distance between an element's border and adjacent elements' borders.


border: Inserts a "wall" around an element.

padding : Defines the distance between an element's content and its border.

___: Defines the width of an element.

outline: Overlays a "wall" on top of an element.

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


```text in increasing specificity
1. External style sheets
2. Internal style sheets
3. Local styles

1..Type selectors (e.g., h1) and pseudo-elements (e.g., :before)
2.Class selectors (e.g., .example), attributes selectors (e.g., [type="radio"]) and pseudo-classes (e.g., :hover).
3.ID selectors (e.g., #example)
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
Forked project is on your online repository.
Cloned project is on your local machine.

The forked repository exists in order to allow you to publish work for code review purposes. You don't do active development in your forked repository.
The cloned repository is your active repository on your own computer you have the forked repo, so you can push changes to it for others to see and review
Your answer here.
```

### Question 9

How is `git pull` related to `git fetch`?

```text

git pull does a git fetch followed by a git merge.

fetch will download any changes from the remote* branch, updating your repository data, but leaving your local* branch unchanged.

pull will perform a fetch and additionally merge the changes into your local branch

git fetch is the command that says "bring my local copy of the remote repository up to date."
git pull says "bring the changes in the remote repository where the code is kept.

You can do a git fetch at any time to update your remote-tracking branches under refs/remotes/<remote>/. This operation never changes any of your own local branches under refs/heads, and is safe to do without changing your working copy.

A git pull is what you would do to bring a local branch up-to-date with its remote version, while also updating your other remote-tracking branches.


```
