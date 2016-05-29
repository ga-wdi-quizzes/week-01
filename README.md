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

#### Answer

A semantic HTML tag describes its meaning in a webpage; on the other hand, a non-semantic HTML tag merely defines how it looks.

Examples of semantic tags:

```html
<header>
  Masatoshi's blog
</header>
<main>
  <section>
    This is an awesome section.
  </section>
</main>
<aside>
  This can be a sidebar.
</aside>
<footer>
  Copyright 2016 Masatoshi
</footer>
```

Examples of non-semantic tags:

```html
<div>Kono <i>tagu</i> wa <b>nan no imi mo motanai</b></div>
<span>This is just a span without any semantic value.</span>
```

[http://www.w3schools.com/html/html5_semantic_elements.asp](http://www.w3schools.com/html/html5_semantic_elements.asp)


### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

#### Answer

The alt attribute provides alternative information for an image in case that a user for some reason cannot view it.

Also it is used by screen readers, which visually impaired people use to hear what is on the image.

For example, if internet connection is slow and the image has not been loaded, the alternative text "Jesse Shawl" will be displayed instead. If the user uses a screen reader, the screen reader will read aloud the alternative text.

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

#### Answer

The `<head>` element is a container for metadata.

HTML metadata is *data about the HTML document*, which is not displayed in the webpage.

Metadata typically defines:
- document title
- styles
- links
- scripts
- other meta information

The tags that describe metadata:

```
<title>, <style>, <meta>, <link>, <script> and <base>
```

[http://www.w3schools.com/html/html_head.asp](http://www.w3schools.com/html/html_head.asp)


## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

#### Answer:

```yml
margin:  Defines the distance between an element's border and adjacent elements' borders.
border:  Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
___:     Defines the width of an element.
outline: Overlays a "wall" on top of an element.
___:     Defines the distance between the center of an element and the center of the adjacent element.
```

#### CSS `outline` property (as opposed to `border`)

- It won't effect the position of the element or adjacent elements.
- It is not a part of the element's dimensions.
- It always goes around all the sides, you can't specify particular sides.
- It doesn't respect border-radius.
- It supports offset with the property `outline-offset`.

[https://css-tricks.com/almanac/properties/o/outline/](https://css-tricks.com/almanac/properties/o/outline/)
[http://stackoverflow.com/questions/1158515/difference-between-outline-and-border](http://stackoverflow.com/questions/1158515/difference-between-outline-and-border)


### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select one:
```
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[ ] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[ ] Selects all ul's of class dropdown, as well as the children elements that are li's
[ ] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

1. The `style` attribute of a HTML element (Inline CSS)
2. The `<style>` element within the HTML document (Internal CSS)
3. An external stylesheet that is linked to by a `<link>` element within the HTML document  (External CSS)

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select one:
```
[X] fork on github;
    git clone <fork_url>;
    git checkout -b <charlie_solution>;
    git add <files>;
    git commit;
    git push;
    create pull request
[ ] fork on github;
    git clone <ga_dc_url>;  # WRONG
    git checkout -b <charlie_solution>;
    git add <files>;
    git commit;
    git push;
    create pull request
[ ] git clone <ga_dc_url>;  # WRONG
    git branch <charlie_solution>;
    git add <files>;
    git commit;
    git push;
    create pull request
[ ] fork on github;
    git clone <fork_url>;
    git checkout -b <charlie_solution>;
    git add <files>;
    git commit;
    git pull;  # WRONG
    create pull request
```

### Question 8

What is the difference between a fork and a clone?

#### Answer

##### `git clone`

- It clones a repository into a newly created directory.
- It creates remote-tracking branches for each branch in the cloned repository (visible using `git branch -r`).
- It creates and checks out an initial branch that is forked from **the cloned repository’s currently active branch**.

[https://git-scm.com/docs/git-clone](https://git-scm.com/docs/git-clone)

##### `git fork`
- It only allows `clone` on the server side.
- Most commonly, forks are used to either:
  + **propose changes to someone else's project** or
  + **use someone else's project as a starting point for your own idea**

- [https://help.github.com/articles/fork-a-repo/](https://help.github.com/articles/fork-a-repo/)
- [http://stackoverflow.com/a/6286877/3837223](http://stackoverflow.com/a/6286877/3837223)

### Question 9

How is `git pull` related to `git fetch`?

```text
Your answer here.
```

[http://stackoverflow.com/a/6286877/3837223](http://stackoverflow.com/a/6286877/3837223)
