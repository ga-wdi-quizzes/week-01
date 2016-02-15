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

*Answer*
Semantic means "indicating or signifying meaning beyond a simple dictionary definition." For an HTML tag to be semantic, it must indicate the function within the webpage of the content contained within the tag. Non-semantic HTML may indicate appearance, positioning, or other similar aspects of the content without indicating anything about its function; accordingly, it would be better to include as CSS in a separate stylesheet. The following HTML snippet includes semantic tags:
`<h1>This is the heading of my page</h1>` – This tag indicates that this is the most important heading on the page.
The following HTML snippet includes non-semantic tags:
`<i>This text is italicized</i>` – The tag only indicates that the text should be in italics, but it shows nothing of its function within the page. The `<em>` tag is semantic and is usually used to italicize text, because it indicates that its content is being emphasized on the page.

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

*Answer*
The alt attribute is included to ensure that if an image does not display properly, the alt text will still display, thereby allowing the user to know what content was supposed to be where the broken image is. This is particular important for Section 508 compliance, as the alt attribute would allow visual impaired people to use screen readers and still have a relatively complete experience of a given webpage.

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

*Answer*
The `<head></head>` tag includes the title of the page as contained in `<title></title>`; it may also include links to external stylesheets (i.e., CSS for the page) and external JavaScript files (e.g., a script.js file). Additionally, the `<head></head>` tag may include metadata about the page (e.g., keywords or page description). It should be noted that the `<title></title>` tag is required within the `<head></head>` tag.

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```
margin : Defines the distance between an element's border and adjacent elements' borders.
border : Inserts a "wall" around an element.
padding : Defines the distance between an element's content and its border.
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

*Answer*
1. inline
2. internal stylesheet,files
 within `<head></head>` tags of the document
3. external stylesheet, linked using the `<link />` tag within the `<head></head>` tags

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

*Answer*
"Fork" is a GitHub-specific term that indicates copying another person's or organization's repository to your own GitHub account. "Clone" is a Git term for downloading a remote repository to your local machine. You can `git clone` a repository without first forking it, but you will need to fork a repository in order to make a pull request on GitHub.

### Question 9

How is `git pull` related to `git fetch`?

*Answer*
The `git pull` command is a combination of the `git fetch` and `git merge` commands (it fetches first and then merges). The `git fetch` command imports commits from a remote repository to the local repo, while the `git merge` command combines the two repositories.
