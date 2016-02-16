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

Semantic HTML tag means that the tag defines it's purpose or the function it provides. For example, <head></head>, <form></form> and <title></title> are semantic tags, they explain what those tags are for, unlike non semantic tags such as <div> and <span> which does not explain it's function on it's own but can be given a meaningful class/id to it, for example, <div class="warning">Do not enter your SSN</div>


```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
Alt attribute gives a short description of an image so that if the image does not load, the description can be displayed on its place so that user can tell what the image is about. It also helps those who are visually impared so their machine can read the descrition of the image for them.

```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text

Purpose of <head> tag is to provide space for tags such as <title>, <meta> information, <style>, <script>, etc. 

```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
Margin__: Defines the distance between an element's border and adjacent elements' borders.
Border_: Inserts a "wall" around an element.
Padding__: Defines the distance between an element's content and its border.
___: Defines the width of an element.
Outline__: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
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
1.In its own stylesheet file
2.In the head area of the index file within <style> </style>
3.In the html code itself such as <p> <strong> this is a paragraph. </strong> </p>
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

Forking creats a copy of file from the source and brings it into my github account and i can clone down (download) that copy into my local machine where i can make edits.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git fetch lets you see all of the branches from the repo. fetching lets you see the changes on another developer's commits without merging the file into my repo. but git pull looks for the copy of remote and merges into my local repo.

```
