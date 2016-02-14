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

Semantic HTML tag means that the tag clearly describes the meaning of the elements for both the browser and developer. For example
Semantic:
<figure>
  <img src> ="img_Max_Photo.png" alt="Max's Face"
</figure>

Non-semantic:
<div>- This tag is not semantic because its primary function is solely a container for other tags and content

For example:
<div>
  <h1> “My page” </h1>
</div>


### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

The alt attribute is important for when you have an image that is not displayed and you would like to provide additional information about the image. The alt attribute essentially specifies alternate text for a given image when the image cannot be displayed.

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

The HTML <head> element is a container for collection of metadata, such as links, stylesheets, and other scripts. Nothing that goes in the <head> tag is seen by the user , but the content within the tag is used for information and changing content that is processed by the browser.

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
Outline: Defines the distance between an element's border and adjacent elements' borders.
Border: Inserts a "wall" around an element.
Padding: Defines the distance between an element's content and its border.
___: Defines the width of an element.
Margin: Overlays a "wall" on top of an element.
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

1. Inline styles
2. Internal style sheets
3. External style sheets


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

```
A fork creates an editable copy of the entire repository.  It creates a copy of the project hosted on my GitHub account.
A clone downloads the source code and all of the version history using Git software on my computer.

```

### Question 9

How is `git pull` related to `git fetch`?

```
A fetch downloads changes from the remote branch, then updates data in the repository, but leaves the local branch unchanged.
A pull makes a fetch and then merges the changes in a local branch. It updates you local branch with changes from the pulled branch.

```
