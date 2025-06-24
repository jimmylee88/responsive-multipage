# Responsive Multi-page project — HTML & CSS week 2 challenge

### Github Pages link:
https://jimmylee88.github.io/responsive-multipage/ 

## Intro
Our assignment this week is to develop upon some basic wireframes we created for a website idea. 
Wireframes PDF: https://github.com/jimmylee88/responsive-multipage/blob/main/wireframe.pdf 

Week 2 was our introduction to flexbox for responsive layouts. The challenge is to incorporate these into our website projects that need to include multiple pages that link between each oher.
It should build upon concepts and elements we learned from the previous week, including use of CSS variables to better organise commonly used styles.

## Background
During the class, I was thinking of creating something for a local artist who wanted someone to re-design their current website.
I started by sketching out a basic wireframe of how the homepage could be laid out. From a UX flow perspective, I wanted to trim down the number of pages the artist currently has. They have a splash page, homepage, about page, project indexes for murals and graphic design, and a contact page. I feel that it could be reduced down to just 3, with the homepage incorporating the information from the about page, and the contact form as they're relatively short. It felt a bit unnecessary for a user to click so much between different pages.

## Approach
I had to get my head around using flexbox for creating responsive layouts that could work across a range of different devices and screen sizes.
Using CSS Variables meant that I could set some global styling and values that could be reused, to ensure consistency of design and build across various elements and pages.
This including the brand colours that I asked Becky about in my initial research, to find out their requirements and needs.

## Reflections & Next Steps
I think I spent way too long wrangling with flexbox on particular parts of the hero image section on the index page. It was just so silly, and I eventually resolved it by stripping out unncessary parameters fromt the CSS making sure it was a lot simpler and cleaner. This meant that flexbox could actually work how it was supposed to, and not give weird, unexpected results. 

I grew to like using flexbox for laying out several parts of the different pages, and it was certainly a lot easier than the week 1 exercise where we didn't use it.
CSS variables was such a handy thing to learn for this project too. It meant I could easily tweak global styles in one place on the css file only, and not have to dig through lines of CSS. I still think I could further streamline my CSS in future though, and not have such a big file with so many lines.

I spent a lot of time testing out the different pages on different screen widths, and on my phone to make sure the layout looked good on each. I definitely found that testing on an actual mobile device is essential, and behaves differently to just resizing a browser window on my laptop.

If I have more time to continue working on it, I would consider using media queries so that on mobile the header nav can collapse down into a compact menu accessed via a burger icon. At the moment, it just uses flexbox to stack the nav items into a column. I would also build out individual project pages that each image on the murals and graphics page could link out to. 
