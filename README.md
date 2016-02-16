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
Tags should be grouped by what they do (<footer><p></p></footer>) as opposed by how the programmer feels (<wallaby's store bottom><how to contact wallaby></wallaby's store bottom></how to contact wallaby>).
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
If a user can't see the image for whatever reason, they can still get a sense of what was supposed to be there. The text contained in alt displays a short description of the image.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head tag contains the background information about the page including the title, image links, script links, etc.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_margin__: Defines the distance between an element's border and adjacent elements' borders.
_border__: Inserts a "wall" around an element.
__padding_: Defines the distance between an element's content and its border.
___: Defines the width of an element.
_outline__: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[XXX] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. inline
2. in the head tag as an internal stylesheet
3. in an eternal stylesheet
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[XXX] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A fork copies the desired repo onto the requester's remote repo or personal github account. With this, they can clone or copy it down into their local repo or computer.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git pull allows a local repo to be updated with it's remote changes. git fetch gets the differing information from the remote repo but doesn't change the local repo.
```
