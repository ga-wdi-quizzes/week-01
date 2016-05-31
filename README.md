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



``
Semantic HTML is the use of HTML markup to reinforce the meaning of the information in webpages rather than merely to define its presentation or look. Semantic HTML is processed by traditional web browsers as well as by many other user agents.
<img></img>
<form></form>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute is used in HTML and XHTML documents to specify alternative text (alt text) that is to be rendered when the element to which it is applied cannot be rendered. It is also used by "screen reader" software so that a person who is listening to the content of a webpage (for instance, a person who is blind) can interact with this element.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The HTML <head> element provides general information (metadata) about the document, including its title and links to its scripts and style sheets.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
border_: Defines the distance between an element's border and adjacent elements' borders.
outline_: Inserts a "wall" around an element.
padding_: Defines the distance between an element's content and its border.
___: Defines the width of an element.
___: Overlays a "wall" on top of an element.
margin_: Defines the distance between the center of an element and the center of the adjacent element.
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
1. inline stylesheets
2. internal stylesheets
3. external stylesheets
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
[x] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```
Forked project is on your online repository whereas, a cloned project is on your local machine
```

### Question 9

How is `git pull` related to `git fetch`?

```
git pull does a git fetch followed by a git merge.
Fetch branches and/or tags (collectively, "refs") from one or more other repositories, along with the objects necessary to complete their histories. Remote-tracking branches are updated (see the description of <refspec> below for ways to control this behavior).
Incorporates changes from a remote repository into the current branch. In its default mode, git pull is shorthand for git fetch followed by git merge FETCH_HEAD.

More precisely, git pull runs git fetch with the given parameters and calls git merge to merge the retrieved branch heads into the current branch. With --rebase, it runs git rebase instead of git merge.

```
