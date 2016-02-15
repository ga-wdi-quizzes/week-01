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
To be semantic is to provide meaning.  In terms of an HTML tag have semantic value, it is in direct contrast
with providing style.  Semantic HTML tags provide meaning to the page and the structure of the the page.

      <body>
        <div class="header">
          <h1>Title Here</h1>
        </div>
      </body>

The <body> and <h1> tags are providing semantic value, while the <div> tags are not.

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
In case the actual image can't or doesn't render, it still provides semantic clarity to what the image was.  
Alt tag provides text alternative for screen readers and older browsers.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head tag is the metadata for that page and isn't actually displayed as content.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_margin_: Defines the distance between an element's border and adjacent elements' borders.
_border_: Inserts a "wall" around an element.
_padding_: Defines the distance between an element's content and its border.
___: Defines the width of an element.
_outline_: Overlays a "wall" on top of an element.
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
1. in-line
2. embedding in the html file in style tags
3. style sheet
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
Fork creates a copy of a repo on your remote repo (github).  Clone creates a copy of a repo on your local.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Git pull is essentially a git fetch + git merge.  git fetch is a 'pull' with no merge.
```
