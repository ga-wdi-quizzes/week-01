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

```To have a class name making it easier to identify the info in that div.
<header>
<p>cool</p>
</header>

<div class="theskyisblue">
<h1>Hello</h1>
</div>
```


### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

``to identify what this image is in the case of the image not displaying in the
web browser. It is now mandatory to have an alt tag in your code.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```To place all your links to css, javascript and meta tags into your code without it
being displaying in your browser. It also contains the title tag.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
__margin_: Defines the distance between an element's border and adjacent elements' borders.
_outline__: Inserts a "wall" around an element.
__padding_: Defines the distance between an element's content and its border.
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
__border_: Defines the distance between the center of an element and the center of the adjacent element.
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
1. classes
2. style
3. element
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

```A fork is copying the remote repository.
  A clone is copying the repository to your local
```

### Question 9

How is `git pull` related to `git fetch`?

```Git pull is related to git fetch becuase they both grab the
information from the remote repository
Git pull merges changes
Git fetch only shows the the changes but does not merge.
```
