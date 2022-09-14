![alt text](https://giankpetrov.github.io/TrailWalk/readme/images/mockuppp1.webp?raw=true)



## TRAIL WALK

**Welcome to TRAIL WALK, a website developed to introduce to newbies and veterans a place to find their next adventure, whenever you are looking for a starting point or put your capabilities to the test.**


## Tech Stack

<img height="50" src="https://user-images.githubusercontent.com/25181517/117447535-f00a3a00-af3d-11eb-89bf-45aaf56dbaf1.png"> **HTML5**
<img height="50" src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png"> **CSS3**
<img height="50" src="https://raw.githubusercontent.com/gitpod-io/gitpod/master/components/dashboard/src/icons/gitpod.svg"> **Gitpod**
<img height="50" src="https://user-images.githubusercontent.com/25181517/117364277-fc4eb280-aebd-11eb-8769-a3583c6a2037.png"> **Git**
## UX Design

### Site Structure 

**TrailWalk is a 5 pages website, the home page is loaded by default. The design is clean usign white as background to make more relevant the rest of the content.**

**Information is well display, starting for the navbar that allows to quickly navigate through the 4 main pages. A call to action button is display just after the hero section to encourage the users to register if they are interested.** 

### Color Scheme 

**The first idea to choose the colors was to keep a clean website with low to no distraction for the users. In the same idea the following colors were chosen.**

![color pallete](https://giankpetrov.github.io/TrailWalk/readme/images/pallete.webp?raw=true)

**The results provided by the **[Coolors](https://coolors.co/)** contrast checker were very good with a score of 11.82**

![contrast checker](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/contrastchecker.webp?raw=true)

### Flex Box

**We use Flex Box in the website. The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning.**

![Flex Box](https://giankpetrov.github.io/TrailWalk/readme/images/flexbox.webp?raw=true)

### CSS Grid

**Grid was also used on the website. The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.** 

![Grid](https://giankpetrov.github.io/TrailWalk/readme/images/grid.webp?raw=true)
## Existing Features

### Navbar
**A clean Navbar with white background allows the menu to highlight for a better navigation.**

![Navbar](https://giankpetrov.github.io/TrailWalk/readme/images/navbar.webp?raw=true)

### Footer
**The footer includes the social media links and again the navbar providing comfort to the user to keep navigating.** 

![Footer](https://giankpetrov.github.io/TrailWalk/readme/images/footer.webp?raw=true)

### Checklist

**The Checklist provide insightful information in a form of a list of fundamentals steps to provide a better experience when doing hiking.**

![Checklist](https://giankpetrov.github.io/TrailWalk/readme/images/checklist.webp?raw=true)

### Places display and Map

**The trails page provide more details of the location, acompanied with a photo and the map directions if the user decided to go for a hike.**

![Places display and Map](https://giankpetrov.github.io/TrailWalk/readme/images/placesdisplay.webp?raw=true)

### Registration Form

**This page allows the visitors to register name, last name and email address in a form. It's responsive and it was made with 3 input fields, 2 types text and 1 type email and with a submit button.**

![Registration Form](https://giankpetrov.github.io/TrailWalk/readme/images/registration.webp?raw=true)

### Form Destination page

**This page with a navbar on top and footer at the bottom and only one section to confirm all details have been delivered and provide a link to go back.** 

![Form Destination page](https://giankpetrov.github.io/TrailWalk/readme/images/formdestination.webp?raw=true)
## Running Tests

### Validator Testing

- HTML **[Markup Validator](https://validator.w3.org/)** by The World Wide Web Consortium **[W3C](https://www.w3.org/)**

![HTML Validator Passed](https://giankpetrov.github.io/TrailWalk/readme/images/htmlvalidator.webp?raw=true)

- CSS Validator **[Jigsaw](https://jigsaw.w3.org/css-validator/)** by The World Wide Web Consortium **[W3C](https://www.w3.org/)**
 
![CSS Validator Passed](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/cssvalidator.webp?raw=true)

### Lighthouse

**After running the lighthouse for the first time we were able to achieve the following results**
- Perfomance        73
- Accessibility     96
- Best Practices    92
- SEO               92

![Lighthouse short cache lifetime](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/lighthouseoriginal.webp?raw=true)

**After fixing the problems with Lighthouse recomendations we were able to achieve better results**
- Perfomance        74
- Accessibility     100
- Best Practices    100
- SEO               100

![Lighthouse short cache lifetime](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/lighthousefix.webp?raw=true)

**The constant low Perfomance on the lighthouse test is regarding to short cache lifetime and it can only be resolved from the server side.**

### Fixed Bugs

#### Encode Images

![Fix encode Images](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/fixencodeimages.webp?raw=true)

**Lighthouse collects all the JPEG or BMP images on the page, sets each image's compression level to 85, and then compares the original version with the compressed version. If the potential savings are 4KiB or greater, Lighthouse flags the image as optimizable.**

#### Image elements with explicit width and height

![Fix width and height](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/fixwidthandheight.webp?raw=true)

**All you need to do is add the images native width and height to the image. You can do this with the width and height attributes, defining the sizes in pixels. This then allows the browser calculate an aspect ratio (the ratio of the width to the height) and allocate enough space for the image before it loads.**



#### Properly size images

![Properly size images](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/fixpropersizeimgs.webp?raw=true)

**For each image on the page, Lighthouse compares the size of the rendered image against the size of the actual image. The rendered size also accounts for device pixel ratio. If the rendered size is at least 4KiB smaller than the actual size, then the image fails the audit.**

#### Network Payloads

![Fix Network Payloads](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/fixnetworkpayloads.webp?raw=true)

**Large network payloads are highly correlated with long load times. They also cost users money; for example, users may have to pay for more cellular data. So, reducing the total size of your page's network requests is good for your users' experience on your site and their wallets.**

#### -Serve Images in next-gen formats 

![Serve Images in next-gen formats](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/fiximageswebp.webp?raw=true)

**AVIF and WebP are image formats that have superior compression and quality characteristics compared to their older JPEG and PNG counterparts. Encoding your images in these formats rather than JPEG or PNG means that they will load faster and consume less cellular data.**

#### Favicon

![Fix favicon](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/fixfavicon.webp?raw=true)

**Messages logged in the console come from either the web developers who built the page or the browser itself. All console messages have a severity level: Verbose, Info, Warning, or Error. An Error message means there's a problem on your page that you need to resolve. In this case, was missing the favicon that later was created.**

### Unfixed Bugs

#### Low Perfomance on Lighthouse

![Lighthouse short cache lifetime](https://github.com/giankpetrov/TrailWalk/blob/main/readme/images/longcache.webp?raw=true)

**The low performance is due to inefficient cache policy, Google's lighthouse suggest a year.**
```code
  Cache-Control: max-age=31536000
```
**This couldn't be fixed as this need to be taking care from the server side and not the client side.**

#### Background not fixed when displaying responsive menu

![background moving bug](https://giankpetrov.github.io/TrailWalk/readme/images/backgroundmovingbug.webp?raw=true)

**The background can be scrolled when responsive menu is displayed. One of the solutions is using JavaScript but wanted to keep the project as much possible only HTML and CSS.**

## Deployment

**The site was deployed to GitHub pages. The steps to deploy are as follows:**

- In the **[GitHub repository](https://github.com/giankpetrov/TrailWalk)**, navigate to the Settings tab
- From the source section drop-down menu, select the Main Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

**The live link can be found **[here](https://giankpetrov.github.io/TrailWalk/)****

**The website is hosted using GitHub pages, deployed directly from the master brach.**

### Run Locally

**Clone the project by following the next command on Bash**

```bash
  git clone https://giankpetrov.github.io/TrailWalk/
```
## Credits

### Code

- Starting idea for responsive menu by **[Coding Nepal](https://www.youtube.com/c/CodingNepal)** and Ivy Walobwa @ **[LogRocket](https://blog.logrocket.com/create-responsive-mobile-menu-with-css-no-javascript/)**
- Idea for responsive cards by **[WebIQ](https://www.youtube.com/channel/UCHOsrjb9LdqH7HEHGocm6lQ)**

### Design

- Favincon made with **[Favicon.io](https://favicon.io/)**
- Color palette from **[Coolors](https://coolors.co/)**
- Font from **[Google Fonts](https://fonts.google.com/)**
- Button Design from Cornerstone Ephraim @ **[Uiverse.io](https://uiverse.io/detail/Cornerstone-04/chatty-eel-89)**

### Media

- Images from **[Pexels](https://www.pexels.com/)**


## Acknowledgements

**[Harry Dhillon](https://github.com/Harry-Leepz)** **for being my mentor on this project and provide excellent feedback from real work experience.** 
