# GitHub Pages Tutorial

## How to make a simple web page on GitHub

* A web page with text and images
* Fully customizable
* Easy to create and easy to update
* No coding exprerience required
* The only language needed is Markown

## Creating your page

1. Create a GitHub account at www.github.io
2. Let's assume you username on GitHub is: `username`
3. So, from now on, wherever it is mentioned `username,` you will just replace it your own GitHub username.
4. Create a new repository with this name (exactly this name): `username.github.io`
5. Give a description to your repository, choose to be public and choose to create a README file. Leave other options as they are.
6. As soon as your new repository is created, go to the top of the page, and click `settings`
7. Under `GitHub Pages`, select `Main Branch`
8. If you want, under 'Theme Choser', select a theme e.d. Cayman
9. Now, you've done everything and your web page is being prepared
10. After a few minutes, your page will be published at `https://username.github.io`

This process, can be repeated for any other repository, using the existing repository's name, and the reslut will be to deploy as a web page the README.md file of any reposipory at this address: `https://username.github.io/repository-name`


## Updating your content

Visiting your new web page, the only thing you will see is the name of your repository and the description you wrote. To include more content in your web page, you can edit the `README.md` file in your repository using a language called `Markdown`.

You can either edit the "README.md" directly on GitHUb, but as this is not so convenient, you could create a file on your computer, edit that file and then upload it to GitHub and it will automatically replace your old README.md file.

Alternatively, keep your `README.md` with information about your repository, and create an `index.md` with the content of your web page.

The `index.md` gets priority over the `README.md` and from now on, your web page will be rendered from your `index.md`, using the same theme you had already selected.

At a later time, if you also add an `index.html` file in your repository, then the existing `index.md`, `README.md`, and the selected theme will be ignored and your web page will appear according to your HTML, CSS and JavaScript code.

---

## GitHub's Markdown Language

The `README.md` or the `index.md` file in your repository, can be customized using the Markdown language. Some exaples appear below.


## Headers

```
# This is a level 1 heading
## This is a level 2 heading
### This is a level 3 heading
#### this is a level 4 heading
##### this is a level 5 heading
###### this is a level 6 heading
```

# This is a level 1 heading
## This is a level 2 heading
### This is a level 3 heading
#### this is a level 4 heading
##### this is a level 5 heading
###### this is a level 6 heading
---

## Font styles

```
**this thext is bold**
_this text is italized_

```
**this thext is bold**
_this text is italized_

```
**combination of _italized text_ inside bold text**
_combination of **bold text** inside italized text_
```
**combination of _italized text_ inside bold text**
_combination of **bold text** inside italized text_

---

## Paragraphs

To start a new paragraph, leave an empty line between the previous and the next paragraph.

```
First paragraph

Seconda paragraph
```
First paragraph

Second paragraph


To start a new line, leave two spaces at the end of a line.
```
First line  <- two spaces at the end of the line
Second line
```
First line
Second line

Note: One enter at the end of a line, does not change the line. Thus, if you write text and siply press enter at the end of each line, that text will appear as a single line. To place the text on a new line, leave two spaces at the end of a line and then press enter. To start a new paragraph, just press enter twice.

---

## Tables:

```
header one | header two | header three
-----------|------------| ------------
first item in #1 | first item in #2 | first item in # 3
second item in # 1 | second item in # 2 | second item in # 3
third item in # 1 | third item in # 2 | third itemm in # 3
```

header one | header two | header three
-----------|------------| ------------
first item in #1 | first item in #2 | first item in # 3
second item in # 1 | second item in # 2 | second item in # 3
third item in # 1 | third item in # 2 | third itemm in # 3

```
items align left | items align center | items align right
:---   |   :---:   |   ---:
item 1a | item 2a | item 3a
item 1b | item 2b | item 3b
item 1c | item 2c | item 3c
```

items align left | items align center | items align right
:---   |   :---:   |   ---:
item 1a | item 2a | item 3a
item 1b | item 2b | item 3b
item 1c | item 2c | item 3c

---

## Unordered Lists:

```
* first item
* second item
* third item
```

* first item
* second item
* third item

```
* first item
* second item
   * second item a
   * second item b
   * second item c
* third item
   * third item a
   * third item b
   * third item c
```

* first item
* second item
   * second item a
   * second item b
   * second item c
* third item
   * third item a
   * third item b
   * third item c

---

## Ordered Lists:

```
1. first item
2. second item
3. third item
```

1. first item
2. second item
3. third item

```
1. first item
2. second item
   1. second item a
   2. second item b
   3. second item c
3. third item
   1. third item a
   2. third item b
   3. third item c
```

1. first item
2. second item
   1. second item a
   2. second item b
   3. second item c
3. third item
   1. third item a
   2. third item b
   3. third item c

---

## Task Lists:

```
* [ ] unchecked item 1
* [x] checked item 2
* [x] checked item 3
```

* [ ] unchecked item 1
* [x] checked item 2
* [x] checked item 3

```
* [ ] unchecked item 1
    * [ ] subitem 1a
    * [ ] subitem 1b
* [x] checked item 2
* [x] checked item 3
    * [x] subitem 3a
```

* [ ] unchecked item 1
    * [ ] subitem 1a
    * [ ] subitem 1b
* [x] checked item 2
* [x] checked item 3
    * [x] subitem 3a

---

## Links:

```
https://www.google.com
```
https://www.google.com

```
[GitHub](http://github.com)
```
[GitHub](http://github.com)

---

## Code:

`` this is an `inline code` example ``

this is an `inline code` example

````
```
This is a longer

code example
```
````

```
This is a longer

code example
```
---

## Code highlighting:

### JavaScript:
````
```javascript
for (i=0; i<10; i++) {
  console.log(i);
}
```
````

```javascript
for (i=0; i<10; i++) {
  console.log(i);
}
```

### HTML:
````
```html
<section class="intro">
   <h1 class="intro-heading">intro heading</h1>
   <p class="intro-text">intro text</p>
</section>
```
````

```html
<section class="intro">
   <h1 class="intro-heading">intro heading</h1>
   <p class="intro-text">intro text</p>
</section>
```

### CSS:
````
```css
.intro {
   margin: 0;
   padding: 0;
   color: #1f3d7a;
   font: Verdana, Arial, sans-serif;
}
```
````

```css
.intro {
   margin: 0;
   padding: 0;
   color: #1f3d7a;
   font: Verdana, Arial, sans-serif;
}
```
---

## Quote:

```
>“We change the world not by what we say or do, but as a consequence of what we have become.”
— David R. Hawkins
```
>“We change the world not by what we say or do, but as a consequence of what we have become.”
— David R. Hawkins

---

## Images:

```
![Merfys, a brown and white dog laying on the floor and looking at the camera](imgs/merfys.jpg)
```

![Merfys, a brown and white dog laying on the floor and looking at the camera](imgs/merfys.jpg)

---

## Clickable Images

First, write the code for the link and the code for the image:

```

Link:
[Merfy's GitHub Page](https://antzm.github.io/)

Image:
![Merfy's the dog looking at the camera](imgs/merfys.jpg)

```

Now, use the code for the link and replace whatever is inside the `[...]` with the full code of the image:

```

Clickable Image:
[![Merfy's the dog looking at the camera](imgs/merfys.jpg)](https://antzm.github.io/)


```

[![Merfy's the dog looking at the camera](imgs/merfys.jpg)](https://www.google.com)

---

## Insert a line

```
---
```

---

## A few tips on Markdown language


## Using Markdown Tables with Text

In the first line, we write the headers separated by |
In the second line we write --- for each header, separated by |
In the following lines, we write our text separated by |
Also, there should be one blank line above and
one blank line below the table:


```
Column 1 | Column 1 | Column 1
---|---|---
Lorem Ipsum | Lorem Ipsum  | Lorem Ipsum
Lorem Ipsum | Lorem Ipsum  | Lorem Ipsum
Lorem Ipsum | Lorem Ipsum  | Lorem Ipsum
```

Column 1 | Column 1 | Column 1
---|---|---
Lorem Ipsum | Lorem Ipsum  | Lorem Ipsum
Lorem Ipsum | Lorem Ipsum  | Lorem Ipsum
Lorem Ipsum | Lorem Ipsum  | Lorem Ipsum


## Using Markdown Tables with Links

Links can be written as
[Google Search](https://www.google.com)
To create a table with links inside, we simply
place the links inside the table like this:

```
Column 1 | Column 1 | Column 1
---|---|---
[Google Search](https://www.google.com) | [Google Search](https://www.google.com) | [Google Search](https://www.google.com)
[Google Search](https://www.google.com) | [Google Search](https://www.google.com) | [Google Search](https://www.google.com)
```

## Creating a table with images

This approach can be used when we would like to place two images next to each other

```
Column 1 | Column 1 | Column 1
---|---|---
![Our story](imgs/story.png) | ![Our story](imgs/story.png) | ![Our story](imgs/story.png)
![Our story](imgs/story.png) | ![Our story](imgs/story.png) | ![Our story](imgs/story.png)
```

Column 1 | Column 1 | Column 1
---|---|---
![Our story](imgs/story.png) | ![Our story](imgs/story.png) | ![Our story](imgs/story.png)
![Our story](imgs/story.png) | ![Our story](imgs/story.png) | ![Our story](imgs/story.png)


## Creating a table with clickable images

This approach can be used when we would like to link, for example, to project pages

```
Column 1 | Column 1 | Column 1
---|---|---
[![Our story](imgs/story.png)](https://www.google.com) | [G![Our story](imgs/story.png)](https://www.google.com) | [![Our story](imgs/story.png)](https://www.google.com)
[![Our story](imgs/story.png)](https://www.google.com) | [G![Our story](imgs/story.png)](https://www.google.com) | [![Our story](imgs/story.png)](https://www.google.com)
```
Column 1 | Column 1 | Column 1
---|---|---
[![Our story](imgs/story.png)](https://www.google.com) | [G![Our story](imgs/story.png)](https://www.google.com) | [![Our story](imgs/story.png)](https://www.google.com)
[![Our story](imgs/story.png)](https://www.google.com) | [G![Our story](imgs/story.png)](https://www.google.com) | [![Our story](imgs/story.png)](https://www.google.com)

## A few notes

When using images, place them in a folder named images or imgs and not directly in your directory. To upload a folder to GitHub (if your are not using GitBash) just click the upload button in your repository and then drag and drop your folder to your repository.

If your images don't appear on your web page, right click on the original images and check if their extension is written as `.jpg .png .gif`  or maybe as `.JPG .PNG .GIF` and then use small or capital letters for the extension, depending on your image.

Some special characters (e.g. a "\*") may not appear correctly in your web page. In such situations, you should place a `\` character before your symbol, like `\*`


> Those who tell the stories rule society - Plato

