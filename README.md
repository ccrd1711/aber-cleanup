# The Aberystwyth Beach Cleanup Website

[Visit the live website here](https://ccrd1711.github.io/aber-cleanup/index.html)

With this website, I wanted to create a simple and appealing web-based introduction to a technically 'fake' charity. 
The 'charity', "Aberystwyth Beach Cleanup Charity", is based off of real-life activity that does happen here in mid-Wales and obviously world wide.
I myself have been part of a few beach cleans since my arrival here in 2016. However the only 'organisation' that currently exists for these is a Facebook group. 

My thought process going into this project was that I must try and think of something to 'sell', but I didn't want it to be too generic, or TOO much like any of the sample projects in the run-up modules. I also didn't want it to be a hard 'product' as such - this is just personal preference. So I thought about charities, which lead me down this route. And as much as Facebook groups in general do work well, I thought, well, "Why isn't there more organisation or action to do these cleanups?" I frequent the beach here regularly all year and there are times when it can be seen that a get-together is needed. 

My thought process progressed to: "Is the reasoning behind this purely just a time or motivation issue? Or could it be linked to something a bit deeper?" So, I thought, let's create this charity narrative for this - a charity always needs both more hands and finances to be able to propel the work. This gave me a sufficient basis for one or multiple CTA's, and also allowed me to be a bit more personal in my appearance of the site as I could source my own images. 

As you may be able to tell by the tone of this introduction so far, it has been written post-project. At the time of currently writing this ReadMe, all but two images on the website are my own. This section will be updated if I can source those myself before submission. 

## User Experience

### User Stories (Also documented within 'Projects' tab before Project inception)

#### 1. As a visitor to the website, I want to easily navigate through information about the cause's mission, upcoming clean-up events, and volunteer sign-up options, so that I can get involved and support the cause effectively.

* Acceptance Criteria:

    The website is fully responsive across various devices and screen sizes.
    Site layout and navigation are intuitive, allowing easy access to different sections.

* Tasks

    Apply responsive design principles using Bootstrap OR CSS (at early stage of project, unsure which path I'm following) to ensure the website is accessible on various devices.
    Arrange the site layout and navigation based on best practices, ensuring all key sections and pages are easily accessible.

#### 2. As a visitor to the website, I want to view images and descriptions of past beach clean-up events, so that I can see the impact of the charity's work and feel inspired to participate.

* Acceptance criteria:

    I want the hero image to be related but directly to actual work being done, image should be of Aber beach in its best way. Images of volunteers cleaning up, possibly before and after shots
    Do this in a clean and professional way

* Tasks

    Source images of past clean-ups and cite these in the credits.
    Use own image (potentially) for the hero image as I have one in mind.
    Use either CSS/Bootstrap to achieve layout.

#### 3. As a community member interested in keeping Aberystwyth beaches clean, I want to visit the causes website to learn about upcoming events and volunteer opportunities, so that I can contribute to environmental conservation efforts

* Acceptance Criteria:

    Website has a dedicated banner or page for all upcoming planned cleans.
    Call to action to 'register' for events unplanned as of yet that would be forthcoming.

* Tasks

    Design with CSS or Bootstrap an area or page with upcoming cleans with locations and times.
    Potentially add in to the same place, or elsewhere, a list of stuff to bring and stuff that will already be provided by the group leaders.
    Investigate whether the CTA should be visible in same place on all pages or a different layout.

#### 4. As someone who may not be able to get to every event as I do not live locally, I would like to keep up to date with events that I have missed or others that the cause post about from elsewhere.

* Acceptance criteria

    The homepage will have links to social media where the group regularly update all their followers about cleans and share other content on social media related to their cause.
    Doesn't take up too much room on the page as to detract from main focus (content and pictures).
    Has an interactive map for first-time visitors.

* Tasks

    Add social media logos with links in the footer or elsewhere in a minimalist way.
    Embed Google maps.

#### 5. As someone who is unable to help in a physical manner, I'd like to contribute to the cause through donations

* Acceptance Criteria

    Donation button or other form of contribution (TBC) on the homepage or the register page - unsure if wanted on every page.
    Clean design.

* Tasks

    Incorporate this button in to the existing design minimally but with enough attention so as it's not easily overlooked.

#### 6. As someone who wants to get involved I'd like to know that the people running the group can be counted on and that the cause is worthwhile from other people in that community, and how much good the cleanups are doing before I commit

* Acceptance Criteria

    Potentially have a testimonials section with 5 (as standard) comments from people who have done the Aber clean, or others.
    
* Tasks

    Integrate this either on the homepage or secondary page, potentially scrolling (roulette) so it's not taking up too much space on the page.

## Website Features 

* Responsive design on phones, tablets and large screens. Further media query required for height as well as width., please see 'Bugs'. 
* Calls to Action on interactive buttons - "Sign Up" & "Donate". 
* Social Media Integration on every page. 
* CONSIDER REMOVING THIS: SEO Optimisation.
* CONSIDER REMOVING THIS: Accessibility. 

## Languages used 

* HTML5
* CSS3

## External Programs Used 

* [Bootstrap v5.3](https://getbootstrap.com/)
* [Font Awesome](https://fontawesome.com)
* [Google Fonts](https://fonts.google.com/)
* [GitHub](https://github.com)
* [Image Color Picker](https://imagecolorpicker.com/)

## Testing Carried Out

* [HTML Validator](https://validator.w3.org/#validate_by_input)

![HTML Validation](/assets/images/htmlvalidation.png)

*Important to note: I got full validation on index.html and register html. It initally picked up a couple of duplicate IDs I mistakenly made, these have been rectified.

On about.html however I have 3 warnings: 

* One is for a UL element being the child of another UL. I have attempted to rectify this but I'm very happy with the current layout and any fixes I try at this late stage of the project are making it unappealing for the viewer. 
* The second is for not having a heading on the map. I personally think it is unnecessary as it's clearly focused on the area around Aberystwyth where the charity work takes place. Adding a hidden heading in here creates more unnecessary code.
* The third is because the validator is not expecting a % icon in the width class on the map. However it's allowing the map to fit the page responsively as it is so I'm leaving it as it is. 




* [CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

![CSS Validation](/assets/images/cssvalidation.png)

* Testing conducted on multiple browsers, devices and OS'.
* iPhones, Macbooks, Windows laptops, Android tablets, and Android phones all running site responsively for the most part (see Bugs section). Tested on Safari, Edge and Chrome browsers. 
* Navigation buttons working including secondary hyperlinked button to 'Donations' (takes you to support us) in the events section, social media links working, and calls to fill in the fields on the CTA forms working. 

## Known Bugs

* There is currently, as far as I'm aware, only one true bug on the site. Nearing the end of my coding whilst I was creating media queries for responsiveness, there was a bug on specific mobiles (with smaller-in-height screens) that pushed the footer icons up in to the area where the donate button is and it overlapped. There is a gap above the sign up form on other media queries, which allows you to see the background more before entering data in the form. To overcome this on mobile I reduced that gap to push everything up and keep the footer in place. All devices that had the issue (iPhone 12 and Samsung S21) have now no longer got this issue. **However** through my testing by sending the website to family and friends, one device - a Samsung S10 - still does this. The media query should include that devices specs so I have not been able to overcome this. 

## Other Bugs noted that were fixed 

* One of the stock images I used was smaller than the others so it didn't accommodate the larger screens as well during responsive tests. The fix was adding a min-height of 100% so it filled it's container and looked uniform.

* I noticed very late on in the project that I had applied my nav bar almost in reverse. Instead of styling it as a nav bar with menu icons, but to then be a dropdown on smaller screen sizes, I created it with an icon for all screens. I tried a few fixes to 'undo' and just bring it back to a standard menu and re-style from there but I wasn't having any luck. Due to the time pressure I also didn't note any attempted coding attempts at this time. I then remembered that during the 'Love Running' challenge we had to follow, that's where that idea of the nav icon was first taught, so I used that code as a starting point/template to build mine from scratch and get it working. This will be noted in 'Acknowledgements'. 

* Further to this, when I had got my navbar to what I wanted it to be it started to mess with my image on 'register.html' and push it down, likely to do with the styling I had in place before hand. Changing this from position:fixed to position:relative fixed this issue. 

* There were other little issues along my journey (mostly with CSS in the design and positioning areas) creating this website but most fixes were completed by playing around with the CSS syntax or a Google search. For example at one point early on in the journey I couldn't quite get why an area on my home page wasn't moving but it was because I was using 'padding' to move something outside of an element rather than 'margin'. 

## Acknowledgements 

* All images in the project are my own
* [Google](https://www.google.com)
* [ChatGPT](https://chatgpt.com/)
* [Love Running project - my version](https://github.com/ccrd1711/love-sprinting)
* [Code Institute 5-Step Coding Challenge](https://learn.codeinstitute.net/ci_program/fivestepcodingchallenge)
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