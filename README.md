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

```
A semantic tag provides information about its content. For instance,

<p>This is a paragraph tag, so the browser and the developer (or at least can assume) the contents is a paragraph.</p>
<div>This, though, is a div tag. While its contents is effectively a paragraph,
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
To provide text to be displayed in text-only browsers, such as those for the blind, or when the image cannot be downloaded due to an error in the src attribute or a slow connection. It does not provide the hovertext/tooltip; that comes from the title attribute. (I thought it did, and was slightly surprised it did not.)
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
It contains information about the document. Important examples include title, a link to a style sheet, and style information for that file.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin: Defines the distance between an element's border and adjacent elements' borders.
outline: Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
border: Defines the width of an element.
___: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
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

```
1. Into a separate file. This is the least specific; it applies to every html file that "calls" it.
2. Within the header block of an HTML file, in a <style> tag. This is in the middle of specificity, covering everything in that file.
3. Within a given tag. That is the most specific, applying only to the contents of that tag.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
I think it's the third one, since if you're working in a non-master branch, a fork isn't needed.

[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[x] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```
A fork is not a git "thing"; it's a github "thing". It takes a repository owned by someone else, and copies it to your github account (or an account you contribute to.)

A clone copies a git repository from "somewhere else" (maybe but not necessarily github) and brings it to the local machine.

Perhaps the simplest way to look at it is I might fork a repository on github then clone the fork down to my laptop. Just like I did for this quiz.
```

### Question 9

How is `git pull` related to `git fetch`?

```
  `git pull` gets the changes, and then merges in the changes as automatically as it can.

  `git fetch` only gets the changes and leaves it to the user to perform the merge.
```
