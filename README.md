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

For HTML tags to be semantic, they must provide information about what kind of content is inside, for example: <nav></nav> and <footer></footer>

Examples of non-semantic tags: <div></div>, <span></span>, which provide no information about the content.


```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```

Alt text (ie 'alternative') is a description of the image and will display on a website if the image, for some reason, does not load. Alt text is also an ADA requirement, as it will be read by a screen reader so that the seeing-impaired can understand what's on the page.

```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```

The head tags contain information important for the website to function, but is not displayed on the actual page. The head should include links to the external CSS and JS sheets, any google fonts, favicons, etc., as well as the title of the page (displayed at the top of the browser page or tab and important for SEO).

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
x: Defines the width of an element.
outline: Overlays a "wall" on top of an element.
x: Defines the distance between the center of an element and the center of the adjacent element.
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
1. Inside specific html tags (most specific)
2. Inside your html page
3. External CSS sheet (best!)
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

```

Fork: forking a repo creates a new repo on the user's account with copies of all files in the forked repo.
Clone: forking a clone downloads the master repo onto the user's local directory.

```

### Question 9

How is `git pull` related to `git fetch`?

```

git pull: pulls up all changes from the local to the remote repository and merges changes in the head branch. Combines git fetch + git merge.
git fetch: downloads any changes that have been made to the remote repository to the local repository. Allows you to see what others have been working on.

```
