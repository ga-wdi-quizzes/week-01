```
completeness 5 out of 5
comfort level 4 out of 5



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
A semantic tag is when the tag clearly defines the content that will be in the tag. It is descriptive so you know that an <img> tag will be an image and a <table> tag will be a table.   Unlike,  non-semantic tags that is ambiguous and doesn't tell you what the content will be. For example, a <div> tag doesn't tell you what it contains.

snippet:
semantic
<header> Farishta Haider </header>

non-semantic
<div>
<p> blah blah blah... words here</p>
</div>
```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```
The alt attribute stands for alternative text. It supplies text describing the image. For example, the image of https://jesse.sh/img/me.jpg is of Jesse Shawl.
The alt attribute is used for a couple of reasons:
1-If the image does not show (due to many possible reasons like link breaks, there is a slow connection or is not supported by the browser) the alt attribute will let the user see what the image was supposed to be.
2-Another purpose of the img Alt attributes is that it is required by law for any user that is unable to see the image due to a handicap.
3- This is helpful for sites with analytics/SEO search. It helps a site organically optimize their site to be found in search engines.

```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```
The <head> tag in HTML is a container on the top of an HTML page that is not visible to the web users. You can includes metadata, the title of the page, stylesheet and more.

```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```
'margin': Defines the distance between an element's border and adjacent elements' borders.
'border'': Inserts a "wall" around an element.
'padding': Defines the distance between an element's content and its border.
___: Defines the width of an element.
'outline': Overlays a "wall" on top of an element.
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

```
1. CSS stylesheet
2. Within the head of each html page with a <style> tag.
3. Inline , for example, within a paragraph tag <p> style="font-size: 12px;"></p>
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

```
To fork a repository is to basically clone the repository under your name. You are able to make changes but it will not affect the original repository unless the owner of the original repository accepts the pull request and merges them. By forking you are still associated to the upstream repository.

A clone is a copy of the repo that lives locally on your computer

The difference is the that the fork lives online and the clone is on your local device.
```

### Question 9

How is `git pull` related to `git fetch`?

```
git fetch only pulls new changes and items that are not on the local device. git pull fetches and merges changes into the current branch.

```
