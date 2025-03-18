# The Aberystwyth Beach Cleanup Website

![Am I responsive screenshot](/assets/images/amiresponsive-beach.png)

[Visit the live website here](https://ccrd1711.github.io/aber-cleanup/index.html)

# Contents

* [Introduction](#introduction)

* [User Experience and Stories](#user-experience)

* [Manual Testing](#manual-testing)

* [Design](#design)

* [Wireframes](#wireframes)

* [Features](#website-features)

* [Languages](#languages-used)

* [External programs used](#external-programs-used)

* [Bugs](#known-bugs)

* [Acknowledgements](#content-and-acknowledgements)

* [Deployment](#deployment-and-accessing-code-workspace)

## Introduction

With this website, I wanted to create a simple and appealing web-based introduction to a technically 'fake' charity. 
The 'charity', "Aberystwyth Beach Cleanup Charity", is based off of real-life activity that does happen here in mid-Wales and obviously world wide.
I myself have been part of a few beach cleans since my arrival here in 2016. However the only 'organisation' that currently exists for these is a Facebook group. 

My thought process going into this project was that I must try and think of something to 'sell', but I didn't want it to be too generic, or TOO much like any of the sample projects in the run-up modules. I also didn't want it to be a hard 'product' as such - this is just personal preference. So I thought about charities, which lead me down this route. And as much as Facebook groups in general do work well, I thought, well, "Why isn't there more organisation or action to do these cleanups?" I frequent the beach here regularly all year and there are times when it can be seen that a get-together is needed. 

My thought process progressed to: "Is the reasoning behind this purely just a time or motivation issue? Or could it be linked to something a bit deeper?" So, I thought, let's create this charity narrative for this - a charity always needs both more hands and finances to be able to propel the work. This gave me a sufficient basis for one or multiple CTA's, and also allowed me to be a bit more personal in my appearance of the site as I could source my own images. 

# User Experience

## User Stories 

| Goal | How was it achieved? | Pass or Fail |
| --- | :---: | ---: |
| As a visitor, I want to quickly understand the purpose of the Aberystwyth Beach Cleanup charity/project so that I can decide if I want to get involved. | Clearly stated navigational items lead the visitor to the appropriate page, also there's guidance to the fact there IS an 'About Us' page directly under the main image | Pass 
| As a potential volunteer, I want to see upcoming cleanup events so that I can plan to participate | Events blocks on the main page stating upcoming events, and again a signifier for the visitor to 'keep up to date' with the team via the support us page | Pass
| As a first-time visitor, I want to know where this takes place whether I am joining a clean or not | The Google Maps implant on the About Us page allows for this with Aberystwyth Beach showing in the snippet. It also has a highlighting heading. | Pass 
| As a donor, or someone who isn't local to Aberystwyth, I want an easy way to contribute financially so that I can support the cleanup efforts. | The registration page allows for this with a fully functioning form, needing all fields to be filled in. | Pass 
| As a mobile-only user, I want to navigate the site easily using the responsive dropdown menu so that I can access information on any device similar in size. | The nav bar is responsive and will allow full navigation as on larger devices too | Pass 
| As a social media user, I want to find the charity's social links so that I can follow and share their initiatives. | All pages have a high contrasting (see Contrast Checker section) footer bar with interactive links to social media sites. | Pass 

# Manual Testing 

## Testing the User Stories 

| Story | Function | Footage | 
| --- | :---: | ---: | 
| User Story 1 | Landing page navigation to the About Us page. The user can navigate to the About Us page on desktop by clicking the button shown in the gif, or navigating the dropdown on smaller devices (see below). This should open in the same tab. | ![gif of navigation](/assets/images/recordings/user%201.gif)
| User Story 2 | Landing page navigation to Events. The user can navigate to the Events section by simply scrolling on the main page. These are simple informational elements with no user interactivity. | ![gif of navigation to events](/assets/images/recordings/user%202.gif)
| User Story 3 | Landing page navigation to Map. The user can access the map by scrolling on the About Us page as evidenced in the gif here. Its thumbnail centres on Aberystwyth Beach. | ![gif of map navigation from landing](/assets/images/recordings/user%203.gif)
| User Story 4 | Donation form demonstration showing needed fields. The user is expected to fill in both fields and a warning will show if one is missed, as evidenced in the gif here.  | ![gif of form submission](/assets/images/recordings/user%204.gif)
| User Story 5 | Navigation testing on mobile with nav bar usage. The user is expected to have this nav bar dropdown when clicking the + icon on any smaller screen device as evidenced here. The links for the site will all show underlined and will open in the same tab. | ![gif showing nav bar mobile usage](/assets/images/recordings/user%205.gif)
| User Story 6 | Social media buttons opening on click with Facebook example. The user is expected to be brought to the applicable social media page in a new tab when clicking on any of the icons shown as evidenced here with Facebook as the example. All icons are operating.  | ![gif showing social media links opening](/assets/images/recordings/user%206.gif)



### Further manual testing completed 

* Testing conducted on multiple browsers, devices and OS'.
* iPhones, Macbooks, Windows laptops, Android tablets, and Android phones all running site responsively for the most part (see Bugs section). Tested on Safari, Edge and Chrome browsers. 

# Automated Testing 

## Validators 

[W3C](https://validator.w3.org/) was used to validate the three HTML files and the CSS file. 

* All index.html, about.html & register.html passed with no errors found. 

* CSS file style.css passed with no errors found. 

## Lighthouse 

I used Lighthouse in Chrome developer tools to test Performance, Accessibility, Best Practices, and the SEO of the website.

![Lighthouse Score](/assets/images/lighthousepc-score.png)


# Design

## Wireframes

![Landing Page Wireframe](/assets/images/cleanuplandingpage.jpg) ![About Page Wireframe](/assets/images/aboutpage.jpg) ![Register Page Wireframe](/assets/images/registerpage.jpg)

## Notes on design changes, and final design

* The images you see in the above Wireframes are for each page of the website. Images 1.1, 1.2 and 1.3 for the Landing/Home page, running from big screens to mobile left to right. It's the same pattern below that for the About page and the Register/Support page. 

* On the Home page you'll notice I had two bars below the Hero image. At that point the plan was to have one bar for an introductive text (which I moved to within the Hero image itself), and one as like a heading for the images. This was done for two reasons: 

    1) I felt like it was taking up unnecessary room on the page, and taking influence from the styling on the 'Love Running' project I felt like this was more impactful and just better design.
    
    2) I felt that an overarching title telling people visiting the site that the next thing they would see is some images, was needless. I wanted it to flow better than that and I feel like the finished product is better than the plan on Balsamiq. 

* I wanted there to be some form of 'narrative' on the first page which I think looks good with the 3 images I took. It shows the act of finding rubbish, collecting it, and then showing a sample of a clean beach. Luckily when I went to take my photos a dog had just run by so I got the footprint in there as well to emphasise the nature impact. 

* On the same day I took my photos, someone had left a beer bottle in the sand. The registration page features this image now, symbolising a "message in a bottle." This metaphor reflects the outreach and community building aspects of the beach clean initiative, where each registration or donation is like sending a message of hope and commitment to the cause. 

* I had used color picker and based the colors off of what was given to me in the grid, however in the end I just chose what I thought was best and visually appealing. You can see below in the contrast checkers that they pass on both styles I have throughout the website assisting with best practice.

## Contrast Checker 

![White on Blue Contrast Pass](/assets/images/contrast-checker.png) ![Blue on Orange Contrast Pass](/assets/images/contrast-checker2.png)

## Website Features 

* Responsive design on phones, tablets and large screens. Further media query required for height as well as width., please see 'Bugs'. 
* Calls to Action on interactive buttons - "Sign Up" & "Donate". 
* Social Media Integration on every page. 
* SEO Optimisation.
* Accessibility. 

## Languages used 

* HTML5
* CSS3

## External Programs Used 

* [Bootstrap v5.3](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com)
* [Google Fonts](https://fonts.google.com/)
* [GitHub](https://github.com)
* [Image Color Picker](https://imagecolorpicker.com/)
* [Balsamiq](https://balsamiq.com)

## Known Bugs

* There is currently, as far as I'm aware, only one true bug on the site. Nearing the end of my coding whilst I was creating media queries for responsiveness, there was a bug on specific mobiles (with smaller-in-height screens) that pushed the footer icons up in to the area where the donate button is and it overlapped. There is a gap above the sign up form on other media queries, which allows you to see the background more before entering data in the form. To overcome this on mobile I reduced that gap to push everything up and keep the footer in place. All devices that had the issue (iPhone 12 and Samsung S21) have now no longer got this issue. **However** through my testing by sending the website to family and friends, one device - a Samsung S10 - still does this. The media query should include that devices specs so I have not been able to overcome this. 

## Other Bugs noted that were fixed 

* I noticed very late on in the project that I had applied my nav bar almost in reverse. Instead of styling it as a nav bar with menu icons, but to then be a dropdown on smaller screen sizes, I created it with an icon for all screens. I tried a few fixes to 'undo' and just bring it back to a standard menu and re-style from there but I wasn't having any luck. Due to the time pressure I also didn't note any attempted coding attempts at this time. I then remembered that during the 'Love Running' challenge we had to follow, that's where that idea of the nav icon was first taught, so I used that code as a starting point/template to build mine from scratch and get it working. This will be noted in 'Acknowledgements'. 

* Further to this, when I had got my navbar to what I wanted it to be it started to mess with my image on 'register.html' and push it down, likely to do with the styling I had in place before hand. Changing this from position:fixed to position:relative fixed this issue. 

* There were other little issues along my journey (mostly with CSS in the design and positioning areas) creating this website but most fixes were completed by playing around with the CSS syntax or a Google search. For example at one point early on in the journey I couldn't quite get why an area on my home page wasn't moving but it was because I was using 'padding' to move something outside of an element rather than 'margin'. 

## Content and Acknowledgements 

* All content was written by the developer.
* All images in the project are my own.
* [Google](https://www.google.com) 
* [ChatGPT](https://chatgpt.com/)
* [Love Running project - my version](https://github.com/ccrd1711/love-sprinting) This provided me with valuable reference points in re-starting my nav bar after I realised the large screen issue mentioned previously, and gave me inspiration (and again a design starting point) with the translucent text section on the hero image, also in the Love Running modules. Used code as is in Love Running and adapted for my own site.
* [Code Institute 5-Step Coding Challenge](https://learn.codeinstitute.net/ci_program/fivestepcodingchallenge) This provided me with a reminder and reference point in embedding Google Maps into the website. Used code as is in the Challenge preview window and adapted for my own site.
* My friends and family who continuously tested bits of the website for me at various stages of development. 

## Deployment and Accessing Code Workspace 

* [Go to the GitHub repository](https://github.com/ccrd1711/aber-cleanup) and click on the Github Logo with 'Open' to access the workspace. 

* [Go to the GitHub repository](https://github.com/ccrd1711/aber-cleanup) and click on 'Deployments' on the right hand side, then click the site URL which is placed under the last deployment timestamp.

## My Own Deployment

* I deployed my site quite early in the development process as I was aware from the course teaching that the preview site doesn't give a true reflection of the finished project, or at least it's liable to errors or displaying differently. 

* To deploy my site initially, here were the steps taken:

   I went to [my repository homepage](https://github.com/ccrd1711/aber-cleanup).

   I clicked on 'Settings' along the top toolbar within the page, then I clicked on 'Pages'.

   In 'Branch', I clicked the dropdown and changed it from 'None' to 'Main'. In the new box that appeared I ensured that the folder was set to '/(root)', and then I pressed 'Save'.

   I then pressed '<> Code' in the top left to bring me back to the repo homepage and waited for 2-3 minutes while the site deployed.

   I refreshed the page. If the site has deployed properly, a section appears called 'Deployments' down the right hand side (referenced above under 'Deployment and Accessing Code Workspace'). Within this section I seen my deployed site's URL. 

   Note: It was in here I could obtain the link to the site to also share with friends and family for testing at various stages along the project. 