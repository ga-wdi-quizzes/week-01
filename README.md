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
An HTML tag is semantic when it describes the purpose of the words in that element.

<header>This tag is a semantic tag.</header>
<p>This tag is also a semantic tag. The header and paragraph tags describe the purpose of the text
within them.</p>
<div>This is a non-semantic tag. The text within this tag could be used for anything. It is not
specified by the tag.</div>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute gives alternate text for an image if the image cannot be displayed or if
the user is using a screen reader. It should always be included with an image in order to
increase the accessibility of the page.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head tag contains the metadata for the page. This includes data such as
the title, the stylesheets, some scripts, and other information that is needed for
the site to display properly but is not seen by the user.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_margin__: Defines the distance between an element's border and adjacent elements' borders.
_border__: Inserts a "wall" around an element.
_padding__: Defines the distance between an element's content and its border.
___: Defines the width of an element.
_outline__: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[X] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. In the html tag
2. In the style tag in the head of the page
3. In an external stylesheet
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
A fork makes a copy of the project onto your github repository. It allows you
to send changes back to the original source project.

A clone makes a copy of the project onto your local computer. When cloning from a
repository that is not your own, you will not be able to send changes back to the
"upstream" repository.

```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git pull fetches and merges the updates from the remote repository with the local 
repository. Git fetch will download the changes made from the remote but will
not automatically merge.
```
