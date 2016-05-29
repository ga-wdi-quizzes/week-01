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

#### Answer

A semantic HTML tag describes its meaning in a webpage; on the other hand, a non-semantic HTML tag merely defines how it looks.

Examples of semantic tags:

```html
<header>
  Masatoshi's blog
</header>
<main>
  <section>
    This is an awesome section.
  </section>
</main>
<aside>
  This can be a sidebar.
</aside>
<footer>
  Copyright 2016 Masatoshi
</footer>
```

Examples of non-semantic tags:

```html
<div>Kono <i>tagu</i> wa <b>nan no imi mo motanai</b></div>
<span>This is just a span without any semantic value.</span>
```

#### Reference
- [http://www.w3schools.com/html/html5_semantic_elements.asp](http://www.w3schools.com/html/html5_semantic_elements.asp)


### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

#### Answer

The alt attribute provides alternative information for an image in case that a user for some reason cannot view it.

Also it is used by screen readers, which visually impaired people use to hear what is on the image.

For example, if internet connection is slow and the image has not been loaded, the alternative text "Jesse Shawl" will be displayed instead. If the user uses a screen reader, the screen reader will read aloud the alternative text.

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

#### Answer

The `<head>` element is a container for metadata.

HTML metadata is *data about the HTML document*, which is not displayed in the webpage.

Metadata typically defines:
- document title
- styles
- links
- scripts
- other meta information

The tags that describe metadata:

```
<title>, <style>, <meta>, <link>, <script> and <base>
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
___: Defines the distance between an element's border and adjacent elements' borders.
___: Inserts a "wall" around an element.
___: Defines the distance between an element's content and its border.
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1.
2.
3.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
Your answer here.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Your answer here.
```
