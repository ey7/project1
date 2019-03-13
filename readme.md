# Code Institute Milestone 1 project

## Victoire Market
 Build a website for the Code Institute User Centric module. I have chosen to build a website for a retail shop in Cork, Ireland. 

 ## Design Planning

A planning document for the website can be found here which details the planning of the UX and UI. I used Figma here for the intial website design of the homepage.

  - The website advertises a retail shop, Victoire Market, that sells Afro-Caribbean products (food, hair and beauty).
  - The aim is for an attractive, simple easy to use website that advertises the products available in distinct categories.
  - Contact information is readily available, with well planned navigation and a contact page.

## Website content

The website consists of five pages, including a homepage, three product pages and a contact page.

## Website Style

- One colour theme of blue throughout for visual consistency. 
- A modern sans serif font of Exo 2 throughout.
- An off white background with dark grey text for optimum readability.

## Website Features

- Visually attractive sliding carousel on homepage to advertise products.
- Responsive navigation with "hamburger" drop down menu icon for small screens.
- Contact form where users can contact for further information.

## Technologies used

- CSS Grid and Flexbox for website layout and design.
- Bootstrap for modern styling with responsive navigation, carousel slider and product cards. 
- Google fonts for fast loading on Exo 2 font.
- Font Awesome for social media icons.
- Jquery and Popper Js for Bootstrap functionality.
- Netlify forms for a working form submission with user input validation.
  
## Resources

- Stackoverflow
- MDN Mozilla Docs
- W3 Schools
- Google
  
## Testing

- The website was tested using developer tools throughout the project on multiple browsers - Chrome, Mozilla & Opera etc.
- All links on all pages were tested to ensure everything was working correctly.
- All elements of the form including all input fields and the submit button were tested.
- All breakpoinnts were tested for different screen sizes.

## Deployment

- After some research I decided to use Netlify to deploy the site, which allows for easy integrated deployment from my github account. I purchased a custom domain for use with the site, victoiremarket.com.
- Netlify also provides some nice features such as free HTTPS, as well as a handy form, easy to implement, that will allow your site to receive up to 100 free submissions a month from the website, as well as a recaptcha for the form.
- I tested the website on personal devices such as laptop and mobile phone, in both potrait and landscape orientations.

## Issues

- Once deployed I realised that the images were far too large and were taking too long to load on the pages.
- The contact form was not working correctly and needed to be updated with the netlify code for activation.
- I noticed on further testing that there was a margin on the right hand side of the page, which caused a horizontal scrollbar to appear on the bottom of the page.
- At certain viewport sizes, as the browser window was resized, the height of the cards did not line up exactly with each other.
- There was no margin between the top of the about section.

## Investigation into issues

- I used Photoshop to optimise and compress the images down to a small size, and the page load speed was much improved.
- I added the netlify code as outlined in the docs to get the form working correctly. I also added a netlify recaptcha to combat spam. I tested the form and the messages were being received to my netlify dashboard.
- I realised that a bootstrap row on the cards section was pushing out the right margin and causing the horizontal scrollbar on the bottom. I first used overflow-x hidden to remove the scrollbar, but this did not work on mobile viewport sizes, the margin was still there. I then removed the overflow-x hidden css and added 15px of margin to the right side of the cards section and this resolved the issue.
- For the resizing height issue with the cards, I added a height of 100% which solved the issue.
- I added a margin top to the about section to improve visual impact.

## Image credits

- Carousel images (x3) courtesy of Pexels.com.
- All other images were taken of store products using my mobile phone camera.

## Acknowledgements













