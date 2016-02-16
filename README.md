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
HTML tags are semantic if they reinforce the meaning of the content in the HTML document.  They provided an additional layer of communication.  For example, if you wanted to display a heading, paragraph, and a quote, you could just use:

<p>My Title</p>
<p>My paragraph consisting of several sentences.</p>
<p>"My quote"</p>

However, using all p tags does not add any semantic value to this HTML.  Instead, you could use:

<header>My Title</header>
<p>My paragraph consisting of several sentences.</p>
<blockquote>"My quote"</blockquote>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute assigns an alternative text to an image if the page cannot be displayed in the browser.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The <head> tag is one of the primary structural elements in an HTML document.  While information within the <head> tag does not appear on the webpage, formatting and styling elements that govern the HTML document are placed in this section.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
__margin__: Defines the distance between an element's border and adjacent elements' borders.
__outline__: Inserts a "wall" around an element.
__padding__: Defines the distance between an element's content and its border.
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
__border__: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[x] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. A separate styles.css file. [external]
2. The <head> section of an HTML document. [embedded]
3. Within the body of the HTML document. [in-line]
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
Forking copies files from one remote repository to another.  Cloning copies files from a remote repository to your local hard drive.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
'Git pull' is the combination of a 'git fetch' and 'git merge', which merge changes to an existing branch of code on a remote repository. 'Git fetch' just updates the local copy of the remote repository.
```
