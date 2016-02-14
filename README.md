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
A semantic element is tagged with a tag that means something inherently to both browser and developer. Meaning, a header has
an inherent function, it serves as a header. Another example would be a <nav> tag. It has inherent properties within HTML. This is opposed to a non-semantic tag which
is defined by the developer. This would be something defined as "div" or "container."

<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
  <header> <----- THIS IS SEMANTIC.
  </header>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

  <div>
    <p>blalbhalhblhablhabl</p>       <--------THIS IS NON SEMANTIC.
  </div>
</body>
</html>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
So that if the picture doesnt load, you will get a "stand-in" piece of text, a space filler
so to speak. Generally it should describe the picture or relay some info related it to it.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
Displays info in the top bar of the browser. Usually the title of the page. DOesnt appear on
the page itself.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin: Defines the distance between an element's border and adjacent elements' borders.
borders: Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
___: Defines the width of an element.
outline: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[x] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. Internally on the html sheet itself
2. Externally: A style.css sheet
3. Multiple external style sheets.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[x] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
Fork- copy someones remote repository to your repository
Clone- copy someones remote repository onto your local hard drive.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git pull is basically a git fetch + git merge.
git fetch "fetches" the changes from branches and stores them in your repository, but doesnt merge them with your current local repository. 
```
