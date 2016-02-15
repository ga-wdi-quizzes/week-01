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
An HTML tag is semantic if it adds meaning to words beyond their dictionary definition. For instance, an <img> tag clearly indicates the type of content should be held within to the coder and the browser.

Semantic tag example:
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>

Meanwhile, a non-semantic tag is the opposite in that it does not give any indication of the type of contents held within.

Non-Semantic tag example:
<div>Hello, World<div>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
An alt attribute describes the content that is displayed by the picture labeled in the <img> tag. This is helpful if a certain browser can't read a picture file or for handicap individuals who are accessing the website using a reader.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The `<head></head>` tag is intended for data about the content that is in the HTML content of a website. The information that is in the <head> tag is not displayed  directly on the website.  The following tags are examples of things to be used inbetween the <head> tags:

<title>
<style>
<meta>
<link>
<script>
<base>
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
`margin`: Defines the distance between an element's border and adjacent elements' borders.
`border`: Inserts a "wall" around an element.
`padding`: Defines the distance between an element's content and its border.
___: Defines the width of an element.
`outline`: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[x] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. Inline Style
2. External Style
3. Internal Style
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
A fork makes a copy of a remote repo onto a personal remote repo. A clone will copy a remote repo (from either a personal or non-personal repo) onto one's local repo. 
```

### Question 9

How is `git pull` related to `git fetch`?

```text
A 'git fetch' command will update the branches that are being tracked on the remote repo. This will not affect the work being done on local branches.
a 'git pull' command will update a local branch with the version being tracked on the remote repo AND will update the branches that are being tracked on the remote repo. This is like a fetch and merge request combined.
```
