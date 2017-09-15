# The Focus Assignment

This assignment is designed to get you to produce a large project over a long period of time using everything you learn in this course. You’ll apply semantic HTML to content; employ CSS to style a design comp, and use a grid to translate the comp to a working web page. Before reading any further, take a moment to inspect all the files and folders in this repo.

## Description

You will create a transfer of [this Photoshop PSD](comps/focus.psd), created by Michael Reimer at [`bestpsdfreebies.com`](http://www.bestpsdfreebies.com/), into a web page. (The original is found [here](http://www.bestpsdfreebies.com/freebie/focus-psd-theme/).) A responsive version is not required; only replicate the PSD file at the native dimensions of `1600 × 2494`. The starter CSS, fonts, and assets you’ll need are discussed later in this document.

## CSS

There are two style sheets in `css`: Eric Meyer’s reset CSS (`reset.css`) and `style.css`. Both are included at the top of the style sheet stack in `index.html`. **You’ll do all of your style sheet-related work in `style.css` — do not touch `reset.css`, and do not add any more CSS files to the `css` folder**.

## Fonts

This design uses three typefaces: Pacifico, Raleway, and Helvetica Neue. The regular weight of Pacifico and the regular, light, and semibold versions of Raleway are included in the `fonts` directory. Helvetica Neue, however, isn’t included, since it’s not open source. Try employing Helvetica Neue in the `font-family` property and fall back to Helvetica. The path to each font is listed below.

**Pacifico Regular**: `fonts/Pacifico/Q_Z9mv4hySLTMoMjnk_rCXYhjbSpvc47ee6xR_80Hnw.woff2`

**Raleway Regular**: `fonts/Raleway/QAUlVt1jXOgQavlW5wEfxQLUuEpTyoUstqEm5AMlJo4.woff2`

**Raleway Light**: `fonts/Raleway/-_Ctzj9b56b8RgXW8FAriQzyDMXhdD8sAj6OAJTFsBI.woff2`

**Raleway SemiBold**: `fonts/Raleway/xkvoNo9fC8O2RDydKj12bwzyDMXhdD8sAj6OAJTFsBI.woff2`

## Assets

All the images you need are in the `img` folder and all the fonts you need are in the `fonts` folder. You’ll want to use `comps/focus.jpg` as a background in your page to make sure you’re keeping true to the original design, and you’ll need `comps/focus.psd` to extract color information, font sizing, leading, etc. **You may not alter any of the images in the `img` folder**.

## Grid

You will need [this Chrome extension](https://github.com/code-warrior/the-modular-grid) in order to transfer the page accurately using a web grid.

## Before You Begin

**<u>*Before doing anything at all to this repo, make sure to checkout your personalized branch first.*</u>**

## Rules

* **Work only in the branch with your name**.
* Except for `style.css` and `index.html`, you may not alter, edit, rename, or remove any of the files in this repo.
* You may not add any files to this repo. The only exception is for Sass: you may add a file called `style.scss` and a file called `_reset.scss` in a folder called `sass`, should you decide to use Sass instead of CSS to style this project.
* Use the hash sign (`#`) as the value to the `href` attribute in all anchors.

## Due

This assignment is due by 11:59 PM on Sunday, 3 December 2017 for both sections of my fall 2017 ARTS 214 class. **Your window for submission is between 8:00 AM – 11:59 PM on Sunday, 3 December 2017. *Do not submit outside of this window.***

## Submission

Issue a pull request back into the original repo from your forked repo. Make sure the `base` and `compare` branches are yours. See [these videos](http://code-warrior.github.io/tutorials/git/github/) and read [Submitting Assignments Using GitHub Desktop](https://code-warrior.github.io/tutorials/submitting-assignments-using-github-desktop/).

## Grading

### A Successful Project Includes…

* A near perfect translation of the original comp.
* Valid HTML, via the [HTML validator](https://validator.w3.org/#validate_by_input).
* Valid CSS, via the [CSS validator](https://jigsaw.w3.org/css-validator/#validate_by_input).

### Points Deducted For…

* Not following these directions.
* Removing, adding, and/or altering files, except for `index.html`, `syle.css`, or the Sass-related files mentioned under the **Rules** section above.

### A Grade of 0 Is Earned For…

* Submitting this assignment after the due date.
* Working in the wrong branch.
* Issuing a pull request into the wrong branch.
