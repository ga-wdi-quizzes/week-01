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
Tags that can be understood by a browser while still allowing the developer to also understand what is going on within the code.  For a non-semantic I want to say div or ul or I think a p tag as well.  While a semantic one is like table or header tags like h1-h6.
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
To facilitate understanding for those who are blind.  So if I am blind the website it able to know the picture that is being displayed on the screen/ web page.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
To facilitate the collection or storage of meta-data.
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
___: Defines the width of an element.
Outline: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
FYI, Took everything I had to not try and find why these questions are here but not to answer them.
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

```I think this is what is being asked:
1.Inline coding i.e. <style></style> within the HTML Doc
2.Separate CSS file linked to the HTML Doc.
3.Element Names
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
Fork: Makes an exact current (at time of fork) copy of the source files available on github by making your own changable repo.
Clone: Does exactly the same thing however it places the "data" on your remote/local machine for changes to be made before "pushing" the information back to your fork.
```

### Question 9

How is `git pull` related to `git fetch`?

```
Fetch allows you to update your "personal" clone without merging while pull allows for the same but adds in the merge automatically.
```
