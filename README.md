# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### Screenshot

![](./page.png)


### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/reactive-layouts-using-css-flexbox-different-class-declarations-html-Ma2ETAHKVf#comment-6a531278ee1e70c1400ce278)
- Live Site URL: [Add live site URL here](https://navanshu-qwerty.github.io/qr-code-component/)

## My process

I tried approaching the challenge by visualizing the web page as a system of different layers. Main page -> Information card -> Image/Heading/Description

<1> I created a "container" class which treats the main body as a flexbox. This allows me to use and align the information divisions over the whole display. 
<2> By creating a "card" class i can build the white information cards which will display the image and its written contents. I used the height parameter to allow flexibility as the image can then resize itself according to the whole browser display. Moreover, by using a "card" class i can avoid repetetion and develop several cards via the same basic settings.
<3> To give out the final touches i created separate CSS tags for the heading and description to manipulate their font sizes, colors and font types. To allow flexible handling of the images, instead of including them inside the "card" class i created its separate tag as well so that in cases where multiple cards are being displayed, the user can have better managment over all the elements.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

This project helped me in the following ways:
<1> Develop a systematic approach to webpages where i can analyse them as layered elements and avoid a complicated trial-and-error approach.
<2> Use HTML and CSS in a multi file project rather than relying on styling every element individually.
<3> Ability to use classes and avoiding multiple declarations or very narrowed generalizations which can lead to complicated results when the web page grows to multiple elements.
<4> Using flexbox as a means to align and organise multiple elements over a single page and create a reactive web page.

### Useful resources

- [W3Schools]([https://www.example.com](https://www.w3schools.com/css/default.asp)) - W3Schools offer a structured and a very useful course to help build the fundamentals
- [freecodecamp on Youtube]([https://www.example.com](https://www.youtube.com/watch?v=OXGznpKZ_sA)) - The video covers everything that i used in this project and is a very good resource for beginners.

### AI Collaboration

I used ChatGPT as a code reviewer and learning assistant throughout this project.

Rather than asking for the solution, I used it to:
<1> Review my HTML and CSS structure
<2> Understand Flexbox concepts
<3> Improve my approach to webpage planning
<4> Learn why certain CSS properties work instead of simply copying code

All HTML and CSS were written and implemented by me.


## Author

- Frontend Mentor - [@ynavanshu-qwerty](https://www.frontendmentor.io/profile/navanshu-qwerty)


