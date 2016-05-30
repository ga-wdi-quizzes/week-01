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
Semantic HTML provides meaning beyond simply presentation on a webpage.  It provides information that is easily read by both computers and developers.
Ex:
Using

<strong>
</strong>

Vs using

<b>
</b>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
The alt attribute provides and alternate text for an image if for some reason the image cannot be displayed.  If for some reason a user cannot see the image, they will still be able to understand the content based on the alt attribute.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
The '<head></head>' tag is used to contain general information about a document, such as the page title, metadate, or links to stylesheets.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin: Defines the distance between an element's border and adjacent elements' borders.
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
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```
From least to most specific
1. Inline styles (located in the HTML markup of a particular element)
2. Internal styles (located in the <head> tag)
3. External styles (located on an external stylesheet)
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

```
A fork copies a repository under you Github user ID, while a clone is a proper copy of the repository that is downloaded locally to your machine.
```

### Question 9

How is `git pull` related to `git fetch`?

```
'git pull' is essentially a 'git fetch' followed by a 'git merge'.  'git pull' keeps a local branch up to date with its remote repository, while 'git fetch' can be used without altering your current working copy.
```
