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
Semantic tags clear describe the content of the tag.
Examples of semantic tags would be <table></table> which is used to create a table and 
<img> which is used to display an image.
A non-semantic tag such as <div></div> don't describe the content of the tag at all, 
and can be used for generic purposes such as acting as a container for a collection of
elements that need to have a specific style applied.
```
```text
Semantic tag example:
```
```html
<img src="Wendy-Bite.jpg" alt="This is Wendy Bite" />
```
```text
Non-Semantic tag example:
````
```html
<div>What does this container do?  Whithout looking at the css, Who knows!?</div>
````


### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute defines alternate text that will appear in place of an image if the image
cannot be displayed.  For example if the image fails to load or if the user is using a screen
reader, for the visually impaired.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head element container for all head elements which include title of the page, scripts for
the page, style information for the page, meta information, and other information that we haven't
learned about yet.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
`margin`: Defines the distance between an element's border and adjacent elements' borders.
`border`: Inserts a "wall" around an element.
`padding`: Defines the distance between an element's content and its border.
___: Defines the width of an element.
`outline`: Overlays a "wall" on top of an element.
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
1 is most specific
3 is least specific

1. inline style - css written directly inside an element using the style="" attribute.
   This style information applies to the element it is written in.
2. internal style sheet - css written directly in a <style></style> element inside the
   head of the page. The style information only pertains to the html page in which it's 
   written.
3. External style sheet - css written outside of the html document and linked in using
   <link rel="stylesheet" type="text/css" href="STYLE_SHEET_NAME.css"> within the head
   of the html document.  This style sheet can be used on multiple pages.
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
A fork will copy a github repository to a user's git hub repository; this is all performed remotely
on github.  A clone will copy a github repository to a user's local repository; this is the movement
of remote github files to a local machine's git repository.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git pull will fetch down the requested branch/master and automatically merge it with the current 
branch/master your local git repository is working with. Git fetch will bring down the requested
data, but WILL NOT automatically merge it.  In essence git pull is actually performing a fetch AND
merge.  Fetch is just a fetch, nothing more.
```
