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

```the use of HTML markup to reinforce the meaning of the information in webpages and web applications rather than merely to define its presentation or look.

Using BLOCKQUOTE to mark up a quotation is right.
Using BLOCKQUOTE to achieve a presentational effect (left indent) is wrong.

Using EM to mark up emphasis is right. Using it to make text italic is wrong.
Using I to italicise is right. Using it to indicate emphasis is wrong.

Using H1 to mark up the document's main heading is right.
Using FONT and B elements (or a DIV with CSS rules) to mark up a heading is wrong.
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```The required alt attribute specifies an alternate text for an image, if the image cannot be displayed.

.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```The <head> element is a container for all the head elements.

The <head> element can include a title for the document, scripts, styles, meta information, and more.

The following elements can go inside the <head> element:

<title> (this element is required in an HTML document)
<style>
<base>
<link>
<meta>
<script>
<noscript>.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
__margin_: Defines the distance between an element's border and adjacent elements' borders.
__border_: Inserts a "wall" around an element.
_padding__: Defines the distance between an element's content and its border.
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
__padding_: Defines the distance between the center of an element and the center of the adjacent element.
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
1.Internal
2.External
3.Inline
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

```A fork is just a request for GitHub to clone the project and registers it under your username; GitHub also keeps track of the relationship between the two repositories, so you can visualize the commits and pulls between the two projects (and other forks).

When you are cloning a GitHub repo on your local workstation, you cannot contribute back to the upstream repo unless you are explicitly declared as "contributor".
So that clone (to your local workstation) isn't a "fork". It is just a clone.


```

### Question 9

How is `git pull` related to `git fetch`?

```git pull pulls from a remote branch and merges it. git fetch pulls down the code from the remote server to your tracking branches in your local repository.
```
