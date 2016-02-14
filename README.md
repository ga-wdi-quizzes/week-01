# Week 01 `Christine Movius Answers`

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
"Semantic" is defined as "the function of words beyond their dictionary definition." So the HTML tag itself (e.g. header, p,) has a specific function within HTML beyond its dictionary definition.

HTML Semantic Tags: <div class = "biography"></div> (you could even shorten this to bio)

HTML Non-Semantic Tags: <div class = "blue"></div>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
Websites are not just seen with the eyes. They are also read with text-readers. So if someone who is blind is visiting your website, the text reader would say "Jesse Shawl" instead of reciting the image link. Hearing "Jesse Shawl" would make more sense than hearing a URL. If the image link is broken, then the page will display the alt text instead of the broken image symbol. Also, alt tags can be useful for SEO purposes.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head is where markups that are not "seen" on the page, but still affect the page, go. For example, you link you CSS and JS files to your HTML file in the <head></head>.
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
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. `style =` HTML attribute (e.g. <body style="background-color:blue;">)
2. <style></style> tags inside the <head></head>
3. External stylesheet that is linked to the HTML file.
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A fork occurs when you make a copy of another user's remote repository onto your REMOTE repository. A clone occurs when you copy of any remote repository (yours or someone else's) onto your LOCAL repository. It is recommended that your fork another user's repo and clone it down to your local repo rather than directly clone another user's remote repo.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
'git fetch' checks for any new commits that have occurred in the remote repo that are not present in your local repo, but does not merge these new commits. 'git pull' performs a 'git fetch' AND merges the new commits from the remote repo into your local repo. So 'git fetch' is a component of the 'git pull' command.
```
