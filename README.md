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
A semantic HTML tag clearly describes its meaning to the browser and developers, like <nav></nav> or <article></article>

Example of HTML using semantic tags and non-semantic tags:

<body>
  <nav>
  <a href="#">Example Nav Link</a>
  </nav>
  <main>
    <div class="feature-image"></div>
    <div class="intro-text"></div>
    <article></article>
  </main>
  <aside>Contact info</aside>
</body>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
alt attribute, or alternate text for an image, is used in instances when the image can't be displayed or if a user uses a screen reader. They also help make images more searchable for search engines.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head tag is used to contain head elements for HTML pages, which include meta information, the document title, and linking to external style sheets.
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
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. Inline styles (i.e. style="" added to an HTML element)
2. Internal style sheets (inside the head of the HTML document)
3. External style sheets
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
A fork is when you make a copy of someone else's existing repo. A clone is when you copy an existing repo locally.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git pull is when you pull any updates or changes from a repo and merge them with the version you're working on locally. Git fetch only pulls updates.
```
