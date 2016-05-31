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
semantic tags are ones that have meaning to the developer and the browser.
semantic tags examples: <img>, <header>  :these tags define their content
non-semantic tags: <div>, <span>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
if the image doesn't load or if there is an issue, it will read whatever is under alt.
also, there are implications for those who are blind.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
you put everything that is important but that does not necessarily show up on your webpage inside the <head> tag, such as the <title>. you can also link the css style sheet here.
provides general information about the webpage.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
___: Defines the distance between an element's border and adjacent elements' borders.
margin
___: Inserts a "wall" around an element.
border
___: Defines the distance between an element's content and its border.
padding
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
outline
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
1.inline styles
2.internal styles
3. external styles
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[x] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```
fork copies a rep to github. clone takes a repo and copies it onto your computer.
```

### Question 9

How is `git pull` related to `git fetch`?

```
git pull: fetching changes and merging them into the current branch
git fetch: downloading the set of changes (commits) from a remote repository
```
