# Aurora Borealis 

![Am I responsive image](readme-assets/am-i-responsive.jpg)

<hr>

With this site, I want to give users who are interested a brief overview of this natural phenomenon. The user will find the scientific explanation of how it arises, some fun facts and a contact page should they wish to get more information about the phenomenon. The live site can be found [here](https://carinaaj.github.io/ms1-aurora-borealis/).

# Table of contents
1. [Design](#design)
2. [Features](#features)
    1. [Existing Features](#existing-features)
        1. [Navigation Bar](#navigation-bar)
        2. [Landing Page Banner](#landing-page-aurora-banner)
        3. [Landing Page](#landing-page)
        4. [Footer](#footer)
        5. [Fun Facts](#fun-facts-second-page)
        6. [Contact Page](#contact-third-page)
            1. [Thank You Page](#thank-you)
        7. [Future Features](#future-features)
3. [Testing](#testing)
4. [Credits](#credits)

# Design

**Text & Background color**

Despite the Aurora Borealis being a very visual topic I decided to only implement hero banners as visuals to catch the users interest from the moment they enter the 
site. To soften the contrast but still highlight the colorful hero banners I chose a light grey color as background color. Apart from the logo and navigation menu
the text color is black. As black was a bit too harsh as header I decided to go for a very dark blue color instead.

![Background color](readme-assets/background-color.jpg) ![Menu color before hover](readme-assets/menu-color.jpg)

**Hover/Input Border Color**

As the most common colour for the Aurora is green I decided to color pick a light turquoise from the first hero banner and use it as hover color for all links together
with an appropriate transition duration.

This color can also be found as the border around the input fields on the contact page.

![Hover color](readme-assets/aurora-color.jpg)

# Features

## Existing Features:

### Navigation Bar

To provide the user with easy navigation across all three pages, the header includes the navigation bar at the top right hand corner and the logo ‘Aurora Borealis’ in the top left corner, which creates some space in between both, as well as making it clear on first sight what the site is about and where the navigation can be found. The navigation bar is made out of the Home, Fun Fact and Contact page. 

![Navigation bar and logo](readme-assets/navigation.jpg)

### Landing Page Aurora Banner

Each page consists of a different hero banner to show the variety of the Aurora and keep the interest of the user rather than using the same image across all pages. In addition it should also intrigue the user to learn more about it and to go through all three pages. 

![First hero banner](readme-assets/first-aurora-banner.jpg)

### Landing Page 

**Main Section**

This page provides a brief explanation about 1) What the Aurora Borealis is 2) Where the best places are to see it and 3) When the best time to see it is

Whilst the explanations are relatively brief, there is still a paragraph break in each section to make it easier to read. Every question (and answer) has been separated with its own textbox for easy reading and without overwhelming the user with one large paragraph of text. 

![What is the Aurora?](readme-assets/what-is-aurora.jpg)

After the first question there is a short Youtube video of 4 min also answering the question ‘What is an aurora’ to provide the user not only with textual content but also with a visual. 

![Youtube explanation](readme-assets/what-is-aurora-video1.jpg)

The second section follows the same scheme. First a brief explanation, followed by a Youtube video for some visuals.

Despite being one of the more common questions regarding the Aurora ("When is the best time to see it?"), the last section is only a paragraph in length with no supporting YouTube video. However, to make it clearer at first glance what the question is about I decided to add a little calendar icon next to the question, which offers quicker visual context.

![Best time to see Aurora](readme-assets/best-time-aurora.jpg)

### Footer

The footer section features links to four social media sites and upon clicking, a new tab will open.

![Social Media Links](readme-assets/social-links.jpg)

---

## Fun Facts (second page)

![Second hero banner](readme-assets/second-aurora-banner.jpg)

To provide some less scientific and more fun information to the use I decided to add some fun facts about the Aurora on this page. 

**Introduction:**

As this page does not contain any visuals I decided to add some calmin, subject-appropriate music instead, whilst reading more about the Aurora. The Track is called ‘Northern Lights’ and has been written specifically for this project.

![Sound cloud audio](readme-assets/sound-cloud.jpg)

**Main Fun Fact Section**

To follow the same style in layout as the main page, I separated each fun fact in it’s own textbox and also used paragraph breaks where necessary to make it easier to read.

![Fun fact section](readme-assets/fun-facts.jpg)

The last textbox makes the user aware that there are live cam links available where the Aurora can be seen from the comfort of their own home. Three links have been provided which all open in a new tab. To keep the same colour scheme the hover colour is the same as the social media links.

![Live cam link section](readme-assets/live-cams.jpg)

## Contact (third page)

This page allows the user to leave some details, should they wish to receive a monthly newsletter about the Aurora Borealis. All input fields have a border around which is the same turquoise colour which has been used for the social media links hover. The submit button has also been supplied with the same background colour when hovering over it.

![Contact form](readme-assets/contact-form.jpg)

### Thank you

Upon submitting the form the user will be redirected to a new page, which will thank him for signing up and if he left a comment someone will respond in 48 hrs.

![Thank you page](readme-assets/thank-you.jpg)

## Future Features

- Gallery page
- Hover effect to reveal fun facts

# Testing

The site has been tested by friends and family on a variety of mobile devices as well as different web browsers (Chrome, Firefox, Safari) and all links, videos, audio and the contact form functioned as it should. All input fields of my contact form work and require the requested input fields before submitting. 

I, myself tested the site extensively with dev tools to ensure the site works responsively not only on mobile devices but also on medium to larger screens.

One of the biggest problems I encountered from the beginning was aligning my logo together with the navigation menu. I initally looked at the Love Running site for guidance but despite applying the same code structue it didn't work for my site. After checking with the Slack community and my Mentor I started looking into flexbox as it seems to be the easiest solution. I knew I could have used this across other parts for the website but because I was running out of time I looked only at the basics to make it work for my purposes. 

So after applying display:flex to my logo and the navigation bar and giving my logo an appropriate line-height it finally ligned up.

Applying media queries however has been the biggest challenge during this project. 

The first issue I faced was after applying the first rules to my media queries and I didn't notice that on smaller devices was a horizontal scrollbar. All styles I applied before had to be checked again after this discovery. But before this I had to find out how to eliminate the scrollbar in the first place. The website which provided me with the solution has been credited in the credits section.

One of my main problems after this was to center the Youtube videos and Sound Cloud audio. This took a lot of trial and error. Depending on the device the solution was either changing the width or adjusting the margin.

## Validator Testing

**HTML**

No errors were returned when passing through the official W3C validator

![W3C Validator](readme-assets/w3c-validator.jpg)

**CSS**

No errors were found when passing through the official (Jigsaw) validator

![W3C CSS Validator](readme-assets/w3c-css-validator.jpg)

**Lighthouse**

The page achieved great performance on mobile and desktop

Mobile:

![Lighthouse mobile report](readme-assets/lighthouse-mobile-report.jpg)

Desktop:

![Lighthouse desktop report](readme-assets/lighthouse-desktop-report.jpg)


### Unfixed Bugs

I noticed that on larger screens (1800px and up) when zooming out (90%) that my second hero banner does not stretch through the entirety on the screen anymore. This is due to the fact that the width of the image is only 1950px. For the main and contact section I used images with over 2000px in width. It took me a long time to find a suitable banner and adjust it for my purposes so I decided to not swap the banner at the last minute for this very specific scenario. Although I'd like to address this in the future.

I would have liked to implement a 'back to top' button as the site contains a lot of text. During my research it seemed that I could have worked around it with the 'a' tag the best solution seems to be javascript which is outside this first module. So I decided to leave it out completely.

### Libraries & Programs used:

- Github, to store my repositry
- Gitpod, to create my html and css files
- Google Fonts, for my font family 'Roboto Flex'
- Font Awesome, for my social media icons as well as the calendar icon on the main page and TV screen icon on the fun fact page
- Balsamiq, to create my wireframe
- [Bulk Resize Photos](https://bulkresizephotos.com/en), to compress images
- [NCH Software](https://www.nchsoftware.com/photoeditor/index.html), to edit my hero banners
- Am I Responsive?, to ensure the site looked good across different devices


## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab.

On the left-hand side under ‘Code and automation’, select ‘Pages’ and from the source section drop-down menu, select the Master Branch.

Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - 
https://carinaaj.github.io/ms1-aurora-borealis/

# Credits

I faced many challenges during this project and before I go into further details I wanted to thank the Slack community for all their great support and my Mentor Martina for her amazing support and helpful tips to take this project off the ground. 😃

As a starting point I looked at the Love Running project and took inspiration for the header, hero banner and footer.

**For further HTML and CSS issues I encountered these sites have been used for reference:**

- Code has been taken and adapted from [Codepen](https://codepen.io/ConStambo/pen/WxRQVq) to help me reversing the list order of my navigation bar
- To set space between my list items for the navigation bar I followed the explanation from [GeeksforGeeks](https://www.geeksforgeeks.org/how-to-set-vertical-space-between-the-list-of-items-using-css/)
- To display text with equaly long sentences I looked at [Stackoverflow](https://stackoverflow.com/questions/28733950/display-multiple-text-lines-of-equal-length) for guidance
- To embed Youtube videos I followed a fellow student [Alexa Hendry](https://github.com/AlexaH88) and her Horizon Gamepedia project, which I saw as post on my LinkedIn feed
- How to embed audio from Sound Cloud I looked at [this](https://www.create.net/support/can-i-have-a-soundcloud-track-on-my-site) site
- To center my contact form I adapted code taken from [Stackoverflow](https://stackoverflow.com/questions/8097744/how-do-i-center-this-form-in-css)
- For my textarea to have the same input length as my input fields I found help on [W3 docs](https://www.w3docs.com/snippets/html/how-to-set-the-size-of-the-textarea-element.html)
- As a starting point for the breaking points of my media queries I took advice from [W3 Schools](https://www.w3schools.com/howto/howto_css_media_query_breakpoints.asp)
- To eliminate the horizontal scrollbar on smaller devices I looked at [Hubspot](https://blog.hubspot.com/website/hide-scrollbar-css) for help
- How to add a table of content for my README file I used code from [Stackoverflow](https://stackoverflow.com/questions/11948245/markdown-to-create-pages-and-table-of-contents)

### Content

1. What is the Aurora Borealis?, text taken from [here](https://www.rmg.co.uk/stories/topics/what-causes-northern-lights-aurora-borealis-explained#:~:text=The%20lights%20we%20see%20in,eventually%20collide%20with%20the%20Earth.), 

2. Where are the best places to see the Aurora?, text taken from [here](https://www.northernlightscentre.ca/northernlights.html)

3. When is the best time to see the Aurora?, taken from [here](https://www.discover-the-world.com/northern-lights/)

4. Fun Facts have been taken from [this](https://www.thetimes.co.uk/travel/experiences/nature-and-gardens/11-things-you-didnt-know-about-the-northern-lights) and [this](https://www.lifeinnorway.net/northern-lights-facts/) site

5. You can watch the Aurora from your sofa, text written by me

### Media

All hero banners have been taken from Shutterstuck:

- First hero banner (Stock Photo ID: 1291999282), Photo Contributor: [Therato](https://www.shutterstock.com/g/Therato)
- Second hero banner (Stock Photo ID: 604599662), Photo Contributor: [Weston](https://www.shutterstock.com/g/Weston)
- Third hero banner (Stock Photo ID: 771042802), Photo Contributor: [muratart](https://www.shutterstock.com/g/muratart)
- Fourth hero banner (Stock Photo ID: 1319416262), Photo Contributor: [Krivosheev Vitaly](https://www.shutterstock.com/g/dary)

The videos have been taken from Youtube:

- [What Is an Aurora?](https://www.youtube.com/watch?v=czMh3BnHFHQ)
- [5 Best Places to See the Northern Lights](https://www.youtube.com/watch?v=oquBCkQ_eI4)

The Audio has been written specifically for this project by my fiancé:

[Northern Lights](https://soundcloud.com/davebrowningmusic/northern-lights)

Live Cam links:

- [Aurora Live](https://aurora.live/camera/)
- [See The Aurora](https://seetheaurora.com/webcams)
- [Explore](https://explore.org/livecams/zen-den/northern-lights-cam)

Lastly, I wanted to thank my fiancé, Dave Browning, not only for the beautiful song he composed for my project but also for his endless patience (and tantrums) during the creation of this project. 


