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
A semantic tag is one which relates to its content in plain English. So a <footer> tag denotes a footer, like this:

<footer>
    <p>I can be reached at:
      <ul>
        <li><a href="mailto:jeffreyeaton.dc@gmail.com">jeffreyeaton.dc@gmail.com</a></li>
        <li>(917) 846-3997</li>
      </ul>
    </p>
</footer>

The same thing could be done with a non-semantic tag but the role/placement of the section would not be immediately apparent.

<div>
    <p>I can be reached at:
      <ul>
        <li><a href="mailto:jeffreyeaton.dc@gmail.com">jeffreyeaton.dc@gmail.com</a></li>
        <li>(917) 846-3997</li>
      </ul>
    </p>
</div

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
An alt attribute provides a human-readable description of an image. The main reason this is essential is so the visually impaired can make sense of images, but it's also handy if images cannot be displayed for any other reason.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
The <head> tag contains parts of a webpage that are not part of the content but help to describe (e.g., <title>, <meta>) or style the content.  
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin : Defines the distance between an element's border and adjacent elements' borders.
border: Inserts a "wall" around an element.
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

```text
1.inline (affects the element)
2.in the <head> (affects the page)
3.in an external stylesheet (affects the whole website (presuming every page links to it))
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
Your answer here.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
Your answer here.
```
