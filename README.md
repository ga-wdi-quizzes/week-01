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
Semantic can be synonymous with 'descriptive'. For example, divs are not semantic because they are not descriptive of the content that they hold. However, <article> tags are semantic because it's more obvious what you put inside them, articles.

Non semantic:
<div class="firstdiv">Div Stuff. What's div stuff? Anything.</div>

Semantic:
<article class="dontNeedThisForThisExampleButWhatever">Article stuff. What's article stuff? Articles.</article>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
alt attributes allow users who have special needs understand/view the content. Mostly used on government sites due to ADA requirements.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The head section holds things that will appear throughout your page, but are not explicit content. For example, links to different fonts, css stylesheets and scripts.
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
[x] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. Most specific
CSS can go inside of an html tag, for example <div style: background-color: red;></div>. This styling only applies to this single div.

2. CSS can be placed within <style></style> tags under the <head></head> section of an html page. This is moderately    specific and only applies to the current html page.

3. Least specific
CSS can be placed on a separate stylesheet, in a .css file and then linked to html pages using the <link> tag in the head section. This is the least specific place to put CSS because it can be used on any other html sheet.
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
Forks are done on github, clones are for Git.

By this I mean that Forks are only used to copy content from one person's Github repo to another person's. Cloning is used to copy Github content to your own local repo, where you can modify the content and make commits to it.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git pull is a combination of git fetch and git merge. Git fetch will get data from a remote repo and place it into your local repo, but will not merge the content into the branch. Once content is fetched a git merge must be performed to merge that content into the local branch. Git pull can be used to do both at once.
```
