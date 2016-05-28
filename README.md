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
A semantic tag tells the browser exactly what kind of content is contained within the tags.
A non-semamtic tag does not give a well defined reference to the tags contained content.
Semantic tag example = <img src="hello_world.jpg" height="100px" width="100px">
Non-semamtic tag example = <div style="color:#fff"></div>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute is used as an alternative description of a sources content if that
source content cannot be accessed for some reason. e.g: if https://jesse.sh/img/me.jpg
cannot render on a page, then the text "Jesse Shawl" will take its place. Also used
with screen readers for those with sight impairment.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
Head tags are used as a pages header content container and contains the pages title,
style and script source info, meta info, etc.
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
Outline?: Overlays a "wall" on top of an element.
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
1. Inline
2. Internal
3. External
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
Fork copies from a repo on github to another github repo.
Clone copies from a github repo to a local repo.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git pull "fetches" then merges commits, while fetch just downloads commits without merging.
```
