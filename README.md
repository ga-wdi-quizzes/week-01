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
Your answer here.
An HTML tag is semantic when it describes the type of content it contains.
 Ex. of a semantic tag: <h1> My Website </h1>
 Ex. of a non-semantic tag: <div> Part 1 </div>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
Your answer here.
The `alt` attribute lets the use know what the image content is by providing alternative text.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
Your answer here.
It identifies the top of the document. The contents inside the <head> tag are not displayed on the page, but affect the page in some way or another.
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
1. Separate CSS stylesheet
2. HTML code between <style></style> tags
3. Directly in a line of HTML code
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
Your answer here.
Fork is when you copy a remote repository to your own github account. Clone is when you copy a remote repository to your local machine.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Your answer here.
`git pull` will `git fetch` any changes from the remote repository and merge them with the local branch.
```
