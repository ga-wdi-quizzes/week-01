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
Semantic is a clear and precise way to describe something. <img>
While non-semantic... <div> is a divide and allows for more specificty with CSS but it does not give any information about what's inside, because ANYTHING could go inside.  
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute is the name of the image.  If for instance the image would not load, they would see the words "Jesse Shawl".
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head contains information about that page that the viewer cannot see. i.e. <title>, which is the name that appears in the hyperlink. or a link to other formatting pages, such as the CSS and javascript pages.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_X_: Defines the distance between an element's border and adjacent elements' borders.
_X_: Inserts a "wall" around an element.
_X_: Defines the distance between an element's content and its border.
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
_X_: Defines the distance between the center of an element and the center of the adjacent element.
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
1. Internal - which is where you can put in formation on the HTML sheet but not within the code.  It would be located in the <head> *2*
2. Inline - which is located within HTML. Commonly used to specifity in imgages now, but it was originally the primary location for css. *3*
3.External - on style sheet that is linked to the html page. *1. Best use of css*
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[X] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
Fork: duplicates a file within github and adds it to your working directory
Clone: takes that duplicated file and brings its down to your working computer.
Fork STAYS in github. Clone takes the file OUTSIDE of github.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Both commands are used in the CLI to take information/updates from github to your computer.
```
