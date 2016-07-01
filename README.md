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
Semantic simply means that it is easily defined immediately.  Such as <table> or <img>
Non-semantic would be a tag that you need to define.  Such as <div> or <span>.
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>

```

```text
The alt attribute is for when your image might not show up for whatever reason.  You would then be able to see a name pop up on your screen vs just the broken image photo.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The purpose of the <head></head> tag is primarily to display information on the tab/top above the webpage.  It is also used to include your links that link the html page to js or css etc.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_outline__: Defines the distance between an element's border and adjacent elements' borders.
__border_: Inserts a "wall" around an element.
_padding__: Defines the distance between an element's content and its border.
_margin__: Defines the width of an element.
_border__: Overlays a "wall" on top of an element.
__padding_: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[X] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1.In a CSS file
2.In an html file
3.Not sure where else
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
[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
Fork is making a copy from a remote repo.  Git clone is when you are copying to the local repo.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git pull and git fetch are both remote options.  Git fetch will allow you to see the dates that are made while pull actually updates the files.
```
