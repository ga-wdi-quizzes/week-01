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
1. semantic tags describe the function of the tag to the user and browser. ex: <p> describes the tells the user and browser that this is a pragraph.

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
2. the "alt" attribute is used to describe photos in metadata, used primarily to describe photos on web pages to the blind.

```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
3. the <head> tag describes the section of the web page the user cannot see e.g. behind the scenes operation.

```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
_margin __: Defines the distance between an element's border and adjacent elements' borders.
_border__: Inserts a "wall" around an element.
_Padding__: Defines the distance between an element's content and its border.
: Defines the width of an element.
__outline_: Overlays a "wall" on top of an element.
: Defines the distance between the center of an element and the center of the adjacent element.
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
1. head as an href link
2. head as <style>
3. body (not prefered)
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
8. a clone pulls the contents of a parent repository directly on your computer and it is linked to the repo it came from. if you clone a master repo you do not have access to, you will not be able to make any changes to it. a fork makes a copy of a repository (usually the master) on git hub so that you can safely make modifications without compromising the master.


```

### Question 9

How is `git pull` related to `git fetch`?

```
git fetch downloads updated information to your local repo, while git pull downloads it AND merges changes as well.
```
