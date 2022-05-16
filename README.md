# Horiseon SEO Refactor

## Table of Contents
1. [Description](#description)
2. [Visuals](#visuals)
3. [Resources](#resources)

## Description

The first thing I did to update the HTML was add a title. After this, I added alt descriptions to all of the images.

I then made an effort to change all of the div tags. Within the header, I changed the div tag to a nav tag; this lead me to remove the subsequent ul and li tags. Because of this change, I had to update the CSS code to reflect this. I then named the following two large sections main and aside in place of the div tags. Within main and aside, I changed the inner div tags to section tags. I then reconciled the CSS with these changes.

I had initially reordered the CSS to be in order, not immediately noticing the duplicate stylings. I consolidated the duplicates. Because I had already made unique main and aside tags, I was able to remove the unnecessary classes from both HTML and CSS. 

After these simplications, I was able to update some of my comments to reflect the changes made. In the stylesheet, I also added a few comments to reflect the sections of the webpage it is styling to make it easier for future changes.

## Visuals
![Horiseon](./assets/images/horiseon-search-engine-optimization1.png)

## Resources
[Live Site](https://vmalie3.github.io/seo-refactor/)

[Repository](https://github.com/vmalie3/seo-refactor)