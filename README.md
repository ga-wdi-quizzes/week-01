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
Semantics in HTML refers to a word in a tag that is descriptive of the function of the tag as opposed to a description that could be true, but vague.
<footer> This goes in the footer </footer> = semantic
<img src='blahblah.jpg' alt='description of image'/> = also semantic. Image is = picture goes here.

<i>This is some random stuff in italics but why? What is it?</i> = not semantic.
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
You have to provide an alternate attribute to any image link to assist in the event of a failed load, unsupported content, and for the page reader technology used by the visually disabled. It will be read in lieu of the image being scene so keep it short but descriptive.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
This is where you will keep all of the relevant content that the viewer does not directly SEE on the page. Your metadata, style references, links, script tags etc go here. Oh, and the title, which is yes, visible but only on the tab.
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
__: Defines the width of an element.
Outline: Overlays a "wall" on top of an element. (I found this sentence confusing. Top seems to denote only the top, rather than "over the element as a whole")
__: Defines the distance between the center of an element and the center of the adjacent element.
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
1. Inside of a Style.css file (most specific)
2.  Inside of <style> tags in an HTML file (not horrible but could be more specific)
3.Inline (least specific. Don't do this.)
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[Yes!] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[No. Clone your fork, not the OP master] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[No. Missing Fork] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[No. "Git pull" is what the OP uses to merge a PR. it can't come before a Pull Request and isn't available for the proposal contributor] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
You are "forking" a copy of the master to your github repository only. "cloning" that fork will put it on your LOCAL computer for editing purposes.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
"git fetch" "FETCHES" any changes that have been made in the REMOTE repo that you DO NOT have in your LOCAL repo.
"git pull" will execute a "git fetch" and then "merge" all changes from the remote repo to whatever branch you are currently in on your local.
```
