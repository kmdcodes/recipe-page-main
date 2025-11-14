# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

This is a Frontend Mentor challenge on HTML and CSS that deals with designing a of a recipe page. It is aimed at testing one's skill on how to create responsive webpages with focus on semantic HTML.

Here I decided to approach this challenge adding my own style of hover and focus effects while also trying my possible best to ensure it replicates the original design. This was accomplished with ease as I made use of Grid Layout and also did a little bit of improvisaation. 

### Screenshot
![Desktop view of the page](./desktop-view.png)
![Mobile View](./mobile_view_page_1.jpg)
![Mobile View continuation](./mobile_view_page_2.jpg)

The screenshot do not show the entire contents of the page as the page span over 1 viewport height.


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learnt how to better style table components as it was the most challenging part of this project. Getting the table to look like a replica of the in the challenge was tough but at the end I eventually learnt that I was applying the styles on the wrong selectors. I made correction to the styles and restyled it to work as expected. To me this was something new becaause I never looked up how  to style tables as I hadly used them in my pages. 

Below is a snippet of the css styles for the table.

```html
 <table>
    <tr>
        <td> Calories </td>
        <td class="qty emph">277kcal </td>
    </tr>
    <tr>
        <td> Carbs </td>
        <td class="qty emph">0g </td>
    </tr>
    <tr>
        <td> Protein </td>
        <td class="qty emph">20g </td>
    </tr>
    <tr>
        <td> Fat </td>
        <td class="qty emph">22g </td>
    </tr>
</table>
```
```css
table{ 
    width: 100%;
    border-collapse : collapse;
    }

td, th{
    width : 50%;
    border-bottom : 1px solid color-mix(in srgb, var(--text-grey-black) 30%, transparent);
    padding : 0.8rem 0.5rem;
    
}

tr:last-child td{
    border-bottom : none;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
