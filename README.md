# cube-art-blog

An attempt at the CUBE methodology favouring custom properties over utility
classes

## Notes

This is based on Andy Bell's
[CUBE methodology art blog example](https://www.youtube.com/watch?v=KE8MdPD9yac&list=WL&index=5).
The original uses a SASS utility, [gorko](https://github.com/hankchizljaw/gorko)
and creates a number of utility classes. I wanted to try the methodology out but
really dislike the idea of filling my HTML with tons of classes so I
compromised, creating CSS custom properties for the most of the utility classes
and applying them directly in the CSS. I also altered the scaling method used.
As I've been working on Frontend Mentor Challenges, where the sizing is in
pixels, I've gotten used to using a 'rem' scale based on pixels as it makes it
easier to convert from Figma design to code. The utilities I did retain as
utility classes are directly related to the layout or can be used for visual
effect by multiple elements.

I've used SASS but strictly to take advantage of the Live SASS Compiler in
VSCode. It allowed me to modularize and minify the code while continuing to
write purely in CSS (no SASS variables, mixins, or other features are used).
This is an idiosyncrasy on my part and has nothing to do with the value of CUBE
or SASS.

I managed to get fairly close to Andy Bell's
[full example page](https://art.example.cube.fyi/) but
[my final result](https://janegca.github.io/cube-art-blog/index.html) is not a
100% match.

I do really like CUBE's whole approach to coding, it was fairly simple for me to
figure out most of the tweaks I needed to match the original design and code.

## Files

- \_base: contains the Custom Properties and any element resets
- \_global: general 'tag' (body, h1-h6, a, etc.) styling

- \_ender: class, styles the coloured, skewed, blocks
- \_gallery: class, styles the images in the skewed blocks
- \_hero: class, styles the hero image and caption found at the end of the page
