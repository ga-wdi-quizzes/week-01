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
A Semantic element in an HTML tag clrealy defines it's content.
For e.g., <form>, <table>, <img>, etc. A non-semantic element tells nothing of it's content. For e.g., <div>, <span>, etc.
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The purpose of the 'alt' attribute is to serve as an alternative text to be displayed if the element cannot be rendered.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The '<head></head>' tag contains some pertinent information about the site such as the Title, Metadata, Link to stylesheets, etc.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
Margin : Defines the distance between an element's border and adjacent elements' borders.
Outline: Inserts a "wall" around an element.
Padding: Defines the distance between an element's content and its border.
_______: Defines the width of an element.
Border : Overlays a "wall" on top of an element.
_______: Defines the distance between the center of an element    and the   center of the adjacent element.
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
1. A stylesheet
2. In the '<head></head>' of the html page within a  '<style></style>' tag.
3. Within the body as a scoped attribute and only intended for just the subtree of the parent element as opposed to the whole document.
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
A 'Fork' is a method utilized to make a copy of a master file created/maintained by someone else, into our own repository hub.
A 'Clone' is the action we perform on the 'Forked' file to make a copy of it to our local system.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git Fetch will fetch any changes made to the master file on git hub after initially pulling the file to the local and add the changes. Git Pull would pull a new file with the changes and create a new directory.
```
