# The LonDons

The LonDons website’s core purpose is to connect supporters of Aberdeen Football Club (the ‘Dons’) who live in the Greater London Area. The website provides information on meetups to watch upcoming matches as well as charity events run by the fan club, offering opportunities for supporters, their family and friends to socialise and be part of a football community.  

The website includes an ‘About’ section, which gives information about the purpose of the club and why it was founded, a ‘Join the club’ section, where individuals who are interested in joining the LonDons fan club can submit their email to receive club updates and information about upcoming events, an ‘Upcoming events’ section, which provides the location, time and date of upcoming club events and a ‘Contact’ section, where a form can be filled in to ask a question or make a request of club administrators.

![Responsive Mockup](/media/am-i-responsive-mockup.png)

## Features 

### Existing Features

- __Navigation Bar__

  - The navigation bar is attached to the top of the viewport and contains the site logo, which is a link to the top of the page, and links to the Home, About, Join, Upcoming and Contact sections
  - The menu allows users to easily navigate between the sections, while also providing an instant overview of the site as soon as landing on the page
  - It is fully responsive, collapsing down to a menu icon on smaller screens so as not to be too obtrusive at those sizes; once toggled open, the menu icon becomes a close icon to indicate to users how to get rid of it

This is the navigation bar on a laptop screen.
![Nav Bar](/media/navigation-bar-larger-screen.png)

Here is the navigation bar on a smart phone.
![Nav Bar on iPhone screen](/media/navigation-bar-small-screen-closed.jpeg)

And when toggled open on a smart phone.
![Nav Bar on iPhone screen toggled open](/media/navigation-bar-small-screen-open.jpeg)

- __The landing page image__

  - The landing page has a photograph of Aberdeen fans in Pittodrie (their home stadium) with a colour-gradient overlay and a text overlay; the former to improve the readability of the latter
  - visitors instantly know whose site this is, and target users (Aberdeen fans) will recognise the setting

![Landing Page](/media/full-landing-page-image.png)

- __About Section__

  - The about section is important for letting any prospective new member get a feel for what it might be like to join the club, what types of events the club organises and who can come along
  - This section gives visitors to the site an understanding of how the club came to be, and what sorts of things the club and its members get up to together and lets them know that their family and friends can be included in club events
  
![About section](/media/about-section-top.png)

- __Join the Club section__

  - Here users can submit their email address to the mailing list so that they can be informed of events and goings-on with the club
  - Users would provide their name and their email address
  - The form labels are hidden for a less busy view, but are hidden using code provided by the WAI to maintain accessibility

![Join form](/media/join-form-section.png)

- __Upcoming Events section__

  - This section allows casual users to see what events are upcoming in case they want to dip their toes in the water before committing to joining, or allows joined members a place where they can check what's on - details included are what Aberdeen FC-related event is taking place, when and where
  - The very next event is given prominence so that it can be seen easily and at a glance, but the next few events are also shown for users' information
  - This section will get updated as events pass or are added to the list

![Upcoming Events](/media/upcoming-events-section.png)

- __Contact Form section__

  - This section allows users to ask a question or put a comment to the site admin, possibly about an aspect of the club before they commit to joining it
  - The user will be asked to submit a name, their email address (should they want a response) and their query or comment

![Contact Form](/media/contact-form-section.png)

## Testing 

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

- I tested that this page works in several different browsers: Chrome, Firefox, Opera, Safari
- I confirmed that the site looks good at a range of different sizes and aspects using the DevTools device bar and by viewing the page on multiple devices
- I confirmed that the menu and hero image resized and repositioned themselves as the viewport narrowed and/or shortened; on smaller screens the nav bar is replaced with a menu icon that toggles a drop-down version of the menu open and closed
- I also confirmed that the About, Join, Upcoming and Contact sections all retained good levels of readability, clarity and appearance at various viewport sizes; on smaller screen sizes, the horizontally arranged sections of these sections should wrap neatly
- I have confirmed that both forms work; that the fields are required; only an email address will be accepted in the email fields; and that both submit buttons work and submit the data correctly

### Bugs

#### Solved Bugs

- In early testing I found that my navigation bar links were scrolling the page to the correct section, but that the top of the section was being cut off behind the fixed navigation bar itself.
- I resolved this by setting the scroll-margin-top of all section elements to the height of the navigation bar

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fafcrandy.github.io%2Flon-dons%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fafcrandy.github.io%2Flon-dons%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
  - I confirmed that the site is both performant and accessible by running it through Lighthouse in Chrome DevTools

  ![Lighthouse report](/media/lon-dons-lighthouse-report.png)

### Unfixed Bugs

No unfixed bugs. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page should be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - [The LonDons](https://afcrandy.github.io/lon-dons/)


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The icons for the collapsible navigation menu were taken from [Font Awesome](https://fontawesome.com/)
- The linear-gradient over the landing page image to improve contrast was inspired by the [England Supporters Travel Club page](https://www.englandfootball.com/england/mens-senior-team/England-Supporters-Travel-Club)
- The code to toggle visibility for the collapsible navigation menu on smaller screens was adapted from [this CodeBurst article](https://codeburst.io/how-to-make-a-collapsible-menu-using-only-css-a1cd805b1390)
- The code to hide form labels without impacting accessbility was provided by the [Web Accessibility Initiative](https://www.w3.org/WAI/tutorials/forms/labels/#note-on-hiding-elements)
- Font created by Nick Curtis and hosted at 1001fonts, called [UNderground NF Regular](https://www.1001fonts.com/underground-font.html)
