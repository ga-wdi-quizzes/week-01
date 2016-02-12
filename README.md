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
This means it tells you about the FUNCTION of the words inside it, rather than their FORM -- that is, what they should look like.

<section> 
  <h2>This is semantic</h2>
  <p>Isn't that neat?</p>
</section>

<b><big><center>This is not</center></big></b>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
This text is displayed or read to the user if they are unable to view the image: for instance, if the image link is broken, or they are blind and/or using a screen reader.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
To contain any "rules", meta data, and other information that affects the webpage but does not directly show up on the webpage itself.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin: Defines the distance between an element's border and adjacent elements' borders.
border: Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
___: Defines the width of an element.
outline: Overlays a "wall" on top of an element.
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
1. The `style=` HTML attribute
2. `<style>` tags in the `<head>`
3. External stylesheets
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
A clone is a version of someone else's repository downloaded to your computer. A fork is a copy of someone else's repository, not necessarily downloaded to your computer. You can clone a fork; you can't fork a clone.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
`git fetch` checks for any commits that have been added to a remote repository that you don't have in your local repository. `git pull` runs `git fetch`, and then merges those commits into the current branch of your local repository.
```
