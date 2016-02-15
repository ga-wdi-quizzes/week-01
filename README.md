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
Semantic means it defines its meaning to the developer and browser, such as <header>, <article>, <footer>, <img>, <table>.
Non-semantic does not give a clue of the meaning such as <div> and <span>.
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute is for alternative text to be used when HTML elements can't be
displayed. They are also used for screen readers for the blind or others who
'listen' to webpages.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
Stuff in between the <head> tags are used to give information about the document.
Such as the <title> of the page, <link> so you can link to other pages like your .css file, and metadata <meta> to give information like the author, keywords, and description. None of this information is displayed directly on the page.  
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_margin__: Defines the distance between an element's border and adjacent elements' borders.
__border_: Inserts a "wall" around an element.
__padding_: Defines the distance between an element's content and its border.
___: Defines the width of an element.
_outline__: Overlays a "wall" on top of an element.
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
1.inline
2.internal
3.external
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
You need to fork to do a pull request and have your changes submitted/merged into the original. You must then clone it to your local computer to make changes. You can clone any repository and make changes, but you cannot submit a pull request.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Your answer here.
git fetch allow you to gather any commits from remote repository and store them on your local repo on the current branch. You must then run git merge to merge any changes. Git pull is like running git fetch and git merge at the same time. Git pull does not let you review commit before they are merged and thus may cause conflicts. 
```
