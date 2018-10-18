# Black Sabbath

![alt text](https://github.com/colmcallan/milestone-project1/blob/master/html/images/bandlive.jpg "Header Picture on the Homepage")

>I built this website to showcase the talents of one of the greatest metal/rock bands of all time, Black Sabbath.It displays many different albums, has a sign up page for updates on the band, a bookings page for users to book the band for special occasions and also has a little taster of some their songs so you can listen to them on top of that, there is also a future touring page to book them in one of their bigger venues. I have designed this website in such a way that is user friendly and easy on the eye but also a little bit different as you can see with the choice of background, I felt this makes it stand out better than any other band page.

## UX

The purpose of this project is to create a static **(front-end only)** website for a 1960’s rock band who have around 50 years experience of performing live at numerous events around the world. The target audiences for this website are fans of Black Sabbath and potential fans who would like to use the site to see and hear clips from their back catalog, and any new material as it becomes available.

**In order for the target audience to achieve these things when visiting my website, I incorporated the following:**
- Audio clips for visitors to listen to some of the bands songs
- Video files so the visitors can view the band performing
- A sign up page for the user to register to receive information on new music releases, tours, ticket releases etc.
- Information about the band and it's members, to give the user an overview of their lives
- A news page so users can book the band for various upcoming events 
- Social media links for users to follow to stay up to date with any news the band may have

>I have matched the design of the webpage to suit the bands image and brand presence and also included logos and pictures throughout, to give a good overall user experience.

 ### Wireframe Mockups
 
 These can be found at the following links below:



## Features

### [Home Page](https://github.com/colmcallan/milestone-project1/blob/master/html/index.html)
- transparent header. I used this feature to make the text stand out against the "busy" background so none of the text would get lost in translation. 
- within the header, there's a call to action booking button for anyone who wishes to book the band after they listen to their song snippets. 
- there is also a sign up news letter button (hidden in nav bar on mobile) for any potential new fans to sign up to the latest news and information.

### [Band Page](https://github.com/colmcallan/milestone-project1/blob/master/html/band.html)
- Modal - this feature will allow a user to click on the picture of each band member to get a closer view and also has a nice caption added at the bottom
- Blockquote - I removed the default blockqoute border as against the transparent div, it wasn't appealing to the design and border radius of the transparent box, so I applied a simple border to the transparent box with the same radius to ensure it cleanly wrapped into each section.
- Read More - this feature allows the user to choose whether or not they want to read more about each band member and also prevents the users experience from being a bad one as this information takes up quite a lot of the screen especially on a mobile device where information layout and efficiency is vital.

### [Videos Page](https://github.com/colmcallan/milestone-project1/blob/master/html/videos.html)
- In this section, the user can view three extrememly popular and well known singles from the band. 
- Originally the layout for this was just a basic iframe encoding, however through further research into bootstraps capabilites i came across a carousel property for iframe videos and linked them to the videos. this is the only carousel property on the website that isn't hidden from mobile as with some minor media query adjustments it looks quite well on a mobile device.
- Again we have a booking call to action option for the user as this is the second time they will have listened to the band on the website and it's to re-inforce the home page message of booking the band for whatever their booking is for. 

### [Albums Page](https://github.com/colmcallan/milestone-project1/blob/master/html/albums.html)
- This is where the user can see all albums of the original band members and each album artwork is linked directly to purchase the album on itunes.

### All Pages
- Back to Top Button - this allows a user to navigate straight back to the top of the page if they would like to visit another section. It comes in extremely useful on a long section on a mobile device and saves accidental clicking on items on webpages and ease of use.
- Social Media Links - this feature allows users to follow the band on Facebook, Twitter and Youtube for all the latest news 
- Sign up - this allows users to sign up with their email address and register to receive information on new music releases, tours, ticket releases etc.

## Technologies Used

- **HTML5** - This was used as the layout to fully build the website
- **CSS** - This was used to style the website 
- **[Bootstrap](https://getbootstrap.com/docs/4.1/getting-started/introduction/)** - This was used to get the layout up and running quickly and also use grids to help with the responsive design
- **[JavaScript](https://www.javascript.com/)** - This was used to add picture modals for each of the band members
- **[JQuery](https://jquery.com/)** - This was used to add read more buttons within some of the pages and also used for the back to top button to add a smooth scroll and fade aswell as the bootstrap video carousel

## Testing

I have thoroughly tested this website and worked out any small design bugs that have occured best to my knowledge. I have also tried to submit blank contact forms and forms with incorrect email addresses which gave me an error message on each field to show that the required attribute within my form is working as it should, it also won't allow the user to submit without their name. 

**Devices Used:**
- Samsung Galaxy S8 – Android 8.0
-	Samsung Galaxy S7 - Android 8.0
- Samsung Galaxy S6 – Android  7.0
-	iPhone 8 – iOS 12.4
-	HP Laptop 15-bs0xx – Windows 10
-	iPad Air 2 – iOS 12
-	macbook pro 13"- macOS Mojave

**Browsers Used:**
-	Chrome 
-	Firefox
-	Microsoft Edge
-	Safari

### Issues/Bugs
I had a major issue with a fixed background on iOS devices. I had images set up on my home page that were fixed when I scroll up and down and they looked good on every device except for iOS. It was like the image was zoomed in so far and stretched on both iPhones and iPads. I did a lot of research to try and fix this but to no avail. I found a couple of posts with suggestions for a fix, but it only worked for the whole background of the page and not just a section of the page.

I also had an issue with text-shadow on Samsung Galaxy S6 devices. When a user clicked on a certain page e.g. Home; the Home text would display with a shadow effect like a spotlight was shining on the words. It looked well on iPhones and Samsung Galaxy S8 but was quite distorted on the Galaxy S6, which is why I removed it from mobile devices. It is still set up for tablets, laptops and desktops.

### Validation
All files passed validation testing at https://validator.w3.org/nu/#textarea

## Deployment
My website is currently deployed on Github Pages - https://jtuck15.github.io/milestone-project-1/

I was able to deploy the website here by going to my repository in which all the files are saved, clicking on settings at the top and scrolling down to the heading GitHub Pages. Underneath the heading there is a source and I chose master branch from the dropdown which allows you to host the website on GitHub Pages.

## Credits

### Content
The text for the section "Band" was taken from the Wikipedia article [The Rolling Stones](https://en.wikipedia.org/wiki/The_Rolling_Stones)

The text for the section "Mick Jagger" was taken from the Wikipedia article [Mick Jagger](https://en.wikipedia.org/wiki/Mick_Jagger)

The text for the section "Keith Richards" was taken from the Wikipedia article [Keith Richards](https://en.wikipedia.org/wiki/Keith_Richards)

The text for the section "Charlie Watts" was taken from the Wikipedia article [Charlie Watts](https://en.wikipedia.org/wiki/Charlie_Watts)

The text for the section "Ronnie Wood" was taken from the Wikipedia article [Ronnie Wood](https://en.wikipedia.org/wiki/Ronnie_Wood)

### Media Content
The photos used on this site were obtained from various sources and the references can be found [here](https://github.com/jtuck15/milestone-project-1/blob/master/references.txt)

The videos used on this site were taken from the [The Rolling Stones official Youtube channel](https://www.youtube.com/channel/UCB_Z6rBg3WW3NL4-QimhC2A)

### Acknowledgements
- [Code Institute](https://www.codeinstitute.net/)
- Rohan Hapani - His smooth scroll design using JQuery on [Codepen](https://codepen.io/desirecode/pen/MJPJqV/) really helped me with my back to top button as I felt without the use of JQuery, it didn't look too appealing when you click the button and it jumps straight back to the top.
- Legendary - I took inspiration from this read more/read less button using JQuery on [Codepen](https://codepen.io/legendaryPower/pen/dvJQvB) as I felt that the sections on the band members page were very long on a mobile. This helped shorten the length and give the user the option to read more and also read less.
- [W3schools.com](https://www.w3schools.com/howto/howto_css_modal_images.asp) - I used their modal description to add modal images to each of the band members pictures on the Band page.
- [Bootstrap](https://getbootstrap.com/docs/3.3/javascript/#carousel) - I used the carousel example on Bootstrap to set up my carousel of pictures on the Home page.

### References
Further references can be found [here](https://github.com/jtuck15/milestone-project-1/blob/master/references.txt)