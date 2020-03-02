# Deface

## Story

You are peacefully developing the science news website, when suddenly.. the marketing department finds out that science is not as popular as fast food,
trending clothes with catchy slogans, etc. 
So "make science sexy again" project is now assigned to you. The former site developers are on holiday,
you have no access to the service, but the management needs a solution to be presented... today.
You need to do a temporary change that can be presented at least, even if you can not go to production
with it, yet.
Seize every opportunity to catch user interest so they click on the news articles!
Flashing-moving objects that was annoying to people 20 years ago, and
clickbaitified titles that are annoying us day by day... but hey, according to the
marketing team, it works, so the users and the management will love it! 

The goal is to create a bookmark button in your browser that changes the science news which is
available at the URL http://science-news.code.cool/.

## What are you going to learn?

You will learn and practice how to do the following things:
- DOM manipulation using Javascript,
- The `setInterval` method: periodically executed scripts
- testing javascript snippets directly in developer toolbar console
- manipulating class lists of nodes via Javascript
- Bookmarklet: a trick with bookmarks
- Minification: compressing your script

## Tasks


1. Include static files in the given html page

    - HTML file includes `deface.js` and `deface.css` as Javascript and CSS file

2. Let's begin all the news titles and descriptions with catchy slogans! Update the article title and description contents so they start with random popular slogans, with a dash separator like this: `{slogan} - {title/description}`.

    - Article titles start with slogans
    - Article descriptions start with slogans
    - Slogans are randomly selected

3. All the images on the page should move repetitively - a bit to the right, then a bit to the left, then all over again.

    - Images are continuously moving
    - All images are moving
    - Images move 5px per step, from 15px left to 15px right, each step takes 0.1 second

4. During the time the user spends on the page, one random article is always blinking. After an article blinked 3 times, another random article will blink 3 times and so on.

    - Article is blinking 3 times
    - Blinking article is randomly picked
    - Blinking is continuously happening: once an article stopped blinking, another one starts

5. Bookmarklet functionality is used correctly

    - All the blinking-moving-sloganifying actions are triggered by clicking on a bookmark


## Hints

- The top 50 slogans are provided in the skeleton code.
- In order to find all the DOM nodes which content has to be changed use
`document.querySelectorAll` function
- As the classnames are not so usable here, use tags instead of classnames in the CSS marker
parameters when selecting nodes.
- Each article is in an `<article tag>`
- Use `setInterval` Javascript function to do something periodically.
- Use `left` CSS attribute to move an image horizontally
- For image move, you can use `element.style`
- In order to make an article blink, add a global css rule via Javascript.
  It defines that visibility should be hidden for a class. Then you can modify node classList parameter
  which makes an article blink. 
- Blinking is basically adding and removing the class from an `article tag`.
- A bookmark button can not only redirect you to a new site but run Javascript on the current one. 
In a nutshell, you can write `javascript:(your_entire_code)();` in it and it will run. See more details
 in the background materials.
- In order to "compress" your script so it will be in a row, use a minifier, for example
 [this](https://javascript-minifier.com/). See more info in background materials.

## General requirements


None

## Starting repository

> **For your information**: Unfortunately, GitHub Classroom has an unstable service regarding repository creation and imports. If your repository fails to create or there are issues with code imports you can do the following steps:
>
> 1. Wait. Sometimes it gets done after 1-2 hours.
> 2. Write to your mentors to do it manually for you.
>
> In the meantime, we are working on an own solution to replace GitHub Classroom. We plan to have it in the first quarter of 2020.


Click here to clone your own Git repository:
https://classroom.github.com/a/wrzXso28

## Background materials

- [How to create bookmarklet](http://www.dev-hq.net/posts/1--create-javascript-bookmarklet)
- [Javascript tutorial](https://javascript.info/)
- [DOM manipulation](https://learn.code.cool/full-stack/#/../pages/javascript/javascript-dom)
- [Javascript minification](https://en.wikipedia.org/wiki/Minification_(programming)
- [Add global CSS rule via Javascript](https://dev.to/karataev/set-css-styles-with-javascript-3nl5)

## Acceptance review

You will need this only at review time, **after** completing the project.
[Use this form](https://forms.gle/8aZCjL4T4S4e4GmQA) to record the review you provide for your peer.