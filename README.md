# Frontend Mentor - Social proof section

![Design preview for the Social proof section coding challenge](./design/desktop-preview.jpg)

## Welcome! 👋

Thanks for checking out this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help you improve your coding skills by building realistic projects.

## The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![Screenshot](./design/solution-screenshot.png)

### Links

- Solution URL: (hhttps://github.com/giseleschaves/social-proof-section-master)
- Live Site URL: (https://giseleschaves.github.io/social-proof-section-master/)

## My process

- 1. check the difference between mobile and desktop to create the hmtl structure
- 2. upload fonts, identify colors and where they should be aplied
- 2. implemented the profile card
- 3. in another html tested solutions positioning of the card with the background images
- 4. integrated the solution into the index.html

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Positioning and Background images

### What I learned

I review one fundamental conceps that I got stuck during the challenge:

- positioning relative and absolute

Basically I have to review better the difference between these two options of positioning and how they work togheter. The better approach was to develop a solution using simple divs to learn first and reproduce the effect that was required.

If the background divs are inside of the card container, z-index doesn't work and the background always appear over the card.
If the background divs are after or before the card container, their position will flow related to the page and change how the size increase or decrease.
The solution was to create another container to englobe the tree elements the card and the two background divs and positioning them using absolute to keep them at the same poisition no matter the size of the page.

### Continued development

Understand more about positioning because when the orientation is landscape the soliution to put the main container on the center doesn't work well.

### Useful resources

Thanks Kyle for this amazing tutorial about positioning

- Kyle from Web Dev Simplified - Learn Positioning (https://youtu.be/jx5jmI0UlXU)

## Author

- Frontend Mentor - @giseleschaves(https://www.frontendmentor.io/profile/giseleschaves)
- Twitter - @gisele_s_chaves(https://www.twitter.com/gisele_s_chaves)
