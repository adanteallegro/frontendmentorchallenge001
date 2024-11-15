# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Links

- Solution URL: [Solution Page](https://www.frontendmentor.io/solutions/qr-card-component-with-html-and-css-impjsinyXg)
- Live Site URL: [Live Site](https://adanteallegro.github.io/frontendmentorchallenge001/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- A singular Flexbox, somehow

### What I learned

- Always ALWAYS add alt text! Always!! The alt text does not need to say that it is an image, screen readers will already assume that.
- Size your text with 'rem', not with 'px'. I really need to look up why specifically, but with different solution revisions, I saw that this was a common mistake.
On the topice of 'rem', from what I understand, if you make any text have a rem of '2', the size of the text will double. I feel like there's more to this that I'm not understanding yet.
- Check spelling in the code. For the longest time, I thought I had coded the favicon line wrong, when it turned out I wrote down 'ref' instead of 'rel'. D'oh.

```css
margin: auto;
```

I learned about margin: auto while making this. The margin: auto; command will center a block element horizontally, which is what I needed to do.
I did eventually take this out, as I used a flexbox instead, but I'm still going to leave this here in case I need to look back on it.

```css
text-align: center;
```

In order to make the text aligned in the middle of the div box, I used text-align to ensure that that's possible.

```css
border-radius: 25px;
```

The border radius command will make the corners rounded, I've found out.

- The standard line weight for paragraph texts is 400, so there's no need to declare that.

### Continued development

THINGS I WANT TO LOOK UP:
- What's WCAG? What even is that? It sounds important.
- Why do I need to size everything with rem instead of px? Should be easy to look up.
- There has to be a better way to resize images instead of just relying on pixels. What's a good way to resize images in a way that it will work on any resolution? (It looks like the answer is to set the max-width to 100% on the image, that should shrink down the image!)
- What all does a CSS reset sheet do? To answer that, I just need to actually read through the CSS reset article that was provided to me.


THINGS I WANT TO PRACTICE:
- I should continue to put into practice what I already know by continuing to make simple cards like this one.
- So it turns out that, in order to properly center a card or a box on a browser, a flexbox or a grid will do the trick. I was told the code to make a flexbox, but now's a good time to really learn both.
- Once I find out how to resize images in a way that it'll work on any resolution, I gotta put that into practice, obviously. So...I could make different boxes of different sizes and try making the images have a max-width of 100% and seeing what happens? Sure, why not!

### Useful resources

- [w3schools](https://www.w3schools.com) - I'm still a total baby when it comes to coding, so I'll need to rely on sites like this just so I know what kind of things I can do with HTML/CSS. I'm fully expecting that I'll need to rely on this for a while until I gain the muscle memory for what I can do with just HTML and CSS.
- [A (more) Modern CSS Reset] (https://piccalil.li/blog/a-more-modern-css-reset/) - This is the CSS reset sheet that was provided to me while working on revisions. There's not much else to say about it - it sure did reset the CSS! It did that very well!


## Author

- Frontend Mentor - [@adanteallegro](https://www.frontendmentor.io/profile/adanteallegro)


## Acknowledgments

I was able to get this far in this project thanks to looking at other users' solutions, as well as feedback that was given there. If it wasn't for looking up how other users did the code, I wouldn't have known to add alt text or to use rem sizing instead of px siding. 
There's still a lot I need to learn, and I know that this isn't exactly perfect, but you know what? Finished is better than perfect, I've done what I can, the rest I think I just need some extra help with from others.

As far as revisions go, I do want to thank Øystein Håberg for his very clear and helpful feedback on my first draft! He explained everything in a way that I understand, and I feel like I have a better grasp on coding, especially in CSS!
