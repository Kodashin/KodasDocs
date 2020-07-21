<h1 align="center">KodasDocs</h1>
<h2 align="center">

[![](https://awesome.re/mentioned-badge.svg)](https://github.com/Kodashin/KodasDocs)

</h2>

<p align="center">
  

<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/kodashin/kodasdocs/total">

<img src="https://img.shields.io/badge/made%20by-kodashin-blue" >

<img src="https://img.shields.io/badge/UE4-4.25-green">

<img src="https://img.shields.io/github/stars/kodashin/kodasdocs?style=flat">

<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/kodashin/kodasdocs">

<img alt="GitHub issues" src="https://img.shields.io/github/issues/kodashin/kodasdocs">

</p>

<img src="" width="100%">

<h2 align="center"><a  href="">Live Demo</a></h2>

### [Contributions are Welcome]()

## Description

**NOW WITH DRAG AND DROP**

<p align="center">
<img src="https://giphy.com/gifs/HP5dest4oOHf2" width="80%"></p>

Solitaire implemented by scratch on vue.js. It contains 3 types of solitaire namely spider(which was made famous by microsoft back when I was a kid) ,spider 4 suit and klondike. I've learned web development myself without any course or coaching so don't expect too much from the source code xD.

**This project is inspired by [SabreDartStudios](http://www.sabredartstudios.com/) Go check out his original documentation [Here](http://www.sabredartstudios.com/Docs)** .

## How to play

### Drag and Drop [__Chrome,Opera__]:-

- **Drag** the card or the card pile you want to move.
- **Drop** the dragged card pile on the target and if the move is legal card will move
- Note:- Drag and Drop doesn't work for properly for **firefox** due to their lack of support to html Drag and drop API - https://bugzilla.mozilla.org/show_bug.cgi?id=505521 .

### Click edition [__Mobile,Firefox,Chrome,Safari,Opera__]-

- **Click** on the card or card pile you want to move .The pile turns to **blue**.
- **Click** on the
  destination card and if the move is legal the cards will
  stack below the target.

## About the project.

### Drag and Drop

- Drag and drop is implemented with native html5 drag and drop api with @drag, @dragend, @dragenter eventlisteners on the Card.vue component.
- Libraries like Vue.draggable were not used as i had to write most of the drag and drop logic according to the solitaire game type and I also had to **MOVE** the stack of cards.
- Ghost image in drag is removed instead the **whole stack** of card moves with cursor change.

### CSS

- Each and every card is 100% css except the SVG of the suit in the center of the card,which is made by illustrator tool.

  <p align="center"><img  src="./readme_assets/4.png" width="30%"></p>

### 3 mode menu

Choose from 3 variants of solitaire form the main menu

<p align="center"><img  src="./readme_assets/menu.png" width="70%"></p>

# Variants

## **Klondike**

<p align="center">
<img  src="./readme_assets/3.png" width="80%">
</p>
<!-- <img src="./readme_assets/3.png" width="50%"> -->

## **Spider 4 Suit**

<p align="center">
<img  src="./readme_assets/5.png" width="80%">
</p>

## **Spider 1 Suit**

<p align="center">
<img  src="./readme_assets/1.png" width="80%">
</p>

## Project setup

```
npm install
npm run serve
```

## Future scope

- Add winning animation.

## Support on Beerpay

Hey dude! Help me out for a couple of :beers:!

[![Beerpay](https://beerpay.io/silent-lad/VueSolitaire/badge.svg?style=beer-square)](https://beerpay.io/silent-lad/VueSolitaire) [![Beerpay](https://beerpay.io/silent-lad/VueSolitaire/make-wish.svg?style=flat-square)](https://beerpay.io/silent-lad/VueSolitaire?focus=wish)





## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Kodashin/KodasDocs/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Kodashin/KodasDocs/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
