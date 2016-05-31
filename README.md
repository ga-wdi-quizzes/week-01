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
Your answer here.
```
semantic tag's dictate an element's meaning , where as non-semantic tags are general purpose. For example : the element <head></head> is semantic, because the head element is always the head in an html page, where as the tag <div></div> can be used within any point of an html page, and has no direct correlation to the meaning of an element. 
### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
Should your image not work, or be down, it provides context for what should be there. Also for accessibility by the americans with disabilities act. 
### Question #3
```


What is the purpose of the `<head></head>` tag in HTML?

```text
the <head></head> tag dictates what information is displayed in the top of a webpage. It is not visible within the actual html document, only in the description part at the top of the page. 
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
____: Defines the distance between an element's border and adjacent elements' borders.
outline: Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
margin: Defines the width of an element.
border: Overlays a "wall" on top of an element.
_____: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[] Selects all li's which are directly inside a ul of class dropdown (children)
[x] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1.external style sheet
2.internal style sheet
3.inline style sheet
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
a fork copy's data from one git hub repository to another git hub repository (exclusively on git hub), a clone copy's data from a git hub repo to a local repo.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
a git pull is like a git fetch and a git merge in one command.```
