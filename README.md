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
There are some semantics that are defined already by HTML5, such as <header></header>, <nav></nav> etc. There are other tags that are not so clearly defined and can be used otherwise such as <div>
<span></span>.
</div>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt feature is a requirement on all government sites for the vision impaired. This alt text will also show if the picture fails to load.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head tag contains title, scripts, fonts. Since HTML reads top to bottom, these load first, so the other contents of the website can load properly. I want to say this is the 'framework' or the underlying properties of the website (aside visual)
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
Padding  : Defines the distance between an element's border and adjacent elements' borders.
Border  : Inserts a "wall" around an element.
Outline : Defines the distance between an element's content and its border.
___: Defines the width of an element.
Margin: Overlays a "wall" on top of an element.
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
1. in the element (worse)
2. in the html (better)
3. in a stylesheet .css file (best)
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[X] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?


```text
A Fork is a github term, and is only on github. It is a copy of the master github repository on your account. A clone is on your system and can be a clone of the fork/branch.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Looks like a git fetch is inside a git pull, a git pull contains a git fetch with a merge. while git fetch never changes your working branch. Git pull always merge into the current branch.
```
