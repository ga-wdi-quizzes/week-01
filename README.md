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
When an element is semantic it gives structure to webpage so that the browser and the developer understands it purpose.
Example of non-semantic element: <div>
<div>
<p> There is a full moon</p>
</div>
Example of semantic element :<img>
<img src='http://science.nasa.gov/media/medialibrary/2009/01/08/08jan_bigmoon2009_resources/Ron-Hodges1.jpg' alt='Full Moon'/>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
alt is used to show alternative image/information if the image in img src can not be seen.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
the purpose of the head tag is where data about the HTML document is held.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin: Defines the distance between an element's      border and adjacent elements' borders.

___: Inserts a "wall" around an element.

padding: Defines the distance between an element's content and its border.

_border__: Defines the width of an element.

outline: Overlays a "wall" on top of an element.

___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `?

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
1.inline styles
2.IDs
3.Classes
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
Fork is when you copy a repository on to your github account . cloning is copying repository on to your computer
```

### Question 9

How is `git pull` related to `git fetch`?

```text
they are used to download new data from remote repository.
git fetch downloads new data from remote repository but does not update data into working files.
git pull is used to update head branch with updated changes made from the remote server


```
