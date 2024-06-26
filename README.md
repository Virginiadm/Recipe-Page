# Recipe Page solution | Frontend Mentor
This is a solution to the Recipe Page challenge on Frontend Mentor, with media query and bootstrap available classes. See project [Recipe Page](https://virginiadm.github.io/Recipe-Page/)

## 📝Brief
Your challenge is to build out this recipe page and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

Download the starter code and go through the README.md file. This will provide further details about the project. The style-guide.md file is where you'll find colors, fonts, etc.

## 🗃Assets provided
- JPEG design files for mobile & desktop layouts
- Style guide for fonts, colors, etc.
- Optimized image assets
- README file to help you get started
- HTML file with pre-written content

## Requirements
- Desktop Design (1440px)
- Mobile Design (375px)

## Responsive Web design
![Recipe Page - responsive Web design](/responsive.jpg)

## Built with
 - HTML5
 - CSS3
   - @media
```css
@media (max-width: 1440px) { ... }

@media (max-width: 375px) { ... }
```
- Bootstrap
  - Available classes
  ```html
    <!-- visible xs -->
      <div class="padre_imagen d-block d-sm-none"> ... </div>

   <!-- hidden xs -->
      <div class="padre_imagen d-none d-sm-block"> ... </div>           
  ```
## What challenges did you encounter, and how did you overcome them?
The container div has a padding around it that serves as a separation, when I make the response, in the mobile version that padding only disappears for the image. To solve it, I added the same image outside the container div, now I have two images of the recipe. The first one will be displayed on all screens except the mobile screen and the second one will be displayed exclusively on the mobile view. With bootstrap tags this is done automatically.

## Author
- Website - [Virginia Díaz](https://github.com/Virginiadm)
- Frontend Mentor - [Virginia Díaz](https://www.frontendmentor.io/profile/Virginiadm)
