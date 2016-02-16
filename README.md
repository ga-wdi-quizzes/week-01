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
A semantic tag describes the content's meaning and structure to the browser.

Semantic tag: <h1> or <p>
Non-semantic tag: <br> or <i>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The 'alt' attribute describes an image in case it displays broken. It can also work with disability compliance for those who cannot see the page and need it to be read aloud (508 compliance, etc.)
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The <head></head> tag in HTML contains the metadata for the page, which provides information on the content of the page to search engines and can help with SEO optimization. It also typically holds links to external style sheets, fonts, etc.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
Margin: Defines the distance between an element's border and adjacent elements' borders.
Border: Inserts a "wall" around an element.
Padding: Defines the distance between an element's content and its border.
___: Defines the width of an element.
Outline: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[ x ] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. Inline styles (Don't use!)
2. Embedded styles
3. External style sheets
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[ x ] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A fork creates a copy of the repository in your own personal GitHub account where you can track your changes separately from the main repository. In order to make any changes to that repository on your local, you need to clone it down to your computer and make changes from there.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
'git pull' does a 'git fetch' followed by a 'git merge'.
```
