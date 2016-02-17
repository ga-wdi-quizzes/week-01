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

Semantic HTML are tags clearly states what kind of content it is and non-semantic are general, not specific to any one type of content.

Example:
Semantic <header><title><h1><nav><section>
non-semantic <div> <span> <body>

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

A text description for images required for those who are impaired and can also serve as a placeholder when an image is not visible.

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

Within the head tag are the elements that are related to the website but are not part of the actual body of the website. Within the <head> tag, you may find the <title> tag, favaicon, a reference to the style sheet, and <script>.

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin : Defines the distance between an element's border and adjacent elements' borders.
outline: Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
___: Defines the width of an element.
border: Overlays a "wall" on top of an element.
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
1.External Style Sheet (external .css file used for entire site)
2.Internal Style Sheet (<style> in HTML <head> tag can be used for specific page)
3.Inline Style (to be used to style a single element)
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

```a fork allows us to connect back to the original repository so that we may make pull requests. A clone does not allow us to submit pull requests back to the original repository
```

### Question 9

How is `git pull` related to `git fetch`?

Git pull merges changes from its remote branch a git fetch pulls the info down from the remote branch but does not merge them. Rather it stores a copy on the repository. 
