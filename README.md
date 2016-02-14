# Week 01

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## HTML

<!--### Question #1

What does it mean for an HTML tag to be "semantic"? Give an example of a short snippet of HTML written using semantic tags and non-semantic tags.

Semantic tags are HTML tags whose names clearly describe their content.  These tags help the developer separate content structure from styling.  For example, the <footer> tag defines footer content:

	<footer>This content goes in the footer.</footer>

Non-semantic tags do not describe their content and sometimes focus on content styling.  An example is the <b> tag, which is used to create the bold text:

	<footer><b>This footer content is now bold.</b></footer>

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

The 'alt' attribute provides alternative text in the event the associated image cannot load in the page.  In the above example, "Jesse Shawl" would display in place of the image.

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

The <head> tag is used to define page content that is not displayed, necessarily, but used to provide information about the document (metadata, for example).  It should be placed before the <body> tag and will contain other tags such as <title>; <link> to reference an external stylesheet (or <style> for internal styling); and/or <script> to call javascript functions, for example.

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

MARGIN: Defines the distance between an element's border and adjacent elements' borders.
BORDER: Inserts a "wall" around an element.
PADDING: Defines the distance between an element's content and its border.
___: Defines the width of an element.
OUTLINE: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:

[] Selects all li's which are directly inside a ul of class dropdown (children)
[X] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

1. Inline
2. Internal
3. External

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:

[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request

### Question 8

What is the difference between a fork and a clone?

In Git, a fork is a repository copy that is stored in one's remote repository.  A clone is a repository copy that is stored in one's local repository.

### Question 9

How is `git pull` related to `git fetch`?

Git 'pull' and git 'fetch' both grab current copies of a remote branch's repository and store them locally.  However, git 'pull' goes one step further and merges changes made to the current branch into the local copy.
