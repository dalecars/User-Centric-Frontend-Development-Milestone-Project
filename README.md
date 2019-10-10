# Kingdom Massage 
### Project: User-Centric Frontend Development
___
This is a website for Kingdom Massage located in Edinburgh and owned by Laura Gemmell. The website highlights the health and sports injury treatments that Kingdom Massage offers, including the background history for each massage therapist and contact details to arrange a treatment.  

___
### UX
The design goal for the website was to make a contemporary spacious page that had a clear clutter free layout to display the information easily to vistors. The website colour scheme of purple hues for the text headings and section breakpoints links with the Kingdom Massage logo that represents a thistle.

An introduction section was used to highlight what is massage therpay treatment, identify potential clients and the benefits to them.  It was then important to detail the large number of treatments that Kingdom Massage offers in the following section. Each treatment had to be described but had to be shown in a clear user friendly layout that was achieved with an accordian layout design, that only displays the information for the treatment selected.

The about section highlights the background history of owner Laura Gemmell, showing the origins from her sporting career to becoming a working mother and the training undertaken to become a massage therapist. A brief history was also included for each massage therapist at kingdom massage with a potrait image to show a more personal touch.

It was a requirement to provide contact details for Kingdom Massage and also the opportunity to allow clients to send a message for further information or to arrange a treatment. Social media links were also provided at the footer of the page encouraging clients to follow Kingdom Massage on Facebook and Twitter.  

___
### Technologies

1. HTML
2. CSS
3. Bootstrap (v4.3)
4. Javascript  

___
### Features

This site uses a fixed top Bootstrap 4 navbar with a brand logo on the left and collapse menu on the right that is responsive to media size. An accordion is used for the treatments section as it was ideal to toggle between hiding and showing large amount of content. For the about profile of each massage therapist only some porfile content was provided allowing the user to expanded this for further reading. Javascript is used to enable the collapse features of the navbar, the accordion treatments section, as well as hinding the about profile content.

#### Features to Implement
In the future, I would like to add further javascript to the Navbar while using phone/tablet media when the navbar is epanded that it collapses the menu when a link is clicked. I would also like to add further javascript to the about content section is that the toggle button for each profile changes from "read more..." to "read less..." depending on what has been selected.

An input form has been created in the contact section to allow potential clients to send Kingdom Massage a message with the senders details. The front end of the form has only been created, but the backend coding using PHP to send the message has to be developed.  

A price section to the website will also added to allow the user the option to buy gift certificates.  

___
### Testing

The navbar for the site was to be fixed to top of screen and i wanted to minimse its screen space when viewed on mobile and tablet devices. To achieve this a toggle was used to hide the nav menu on these smaller screen sizes. This feature was tested and the fixed top navbar allowed quick and easy access to these nav links at all times with the user moving to the desired section when selected.

It was neccessary to list all the treatments that Kingdom Massage offers. An accordian feature was succesfully used to hide the detail description with an image for each treatment until a user choose to view the treatment. For phone users the treatment image was deemed 
unnecessary and added clutter, this was hidden when viewed at this screen size. This accordion design was tested at each screen size succesfully.

For the about section a grid design was used to display the therapist image in one column and the profile history in another. For desktop and tablet display the two columns were displayed side by side. However for phone users both columns were to be spread to the screen width and below each other. It was then neccessary to ensure that the profile image was centered on the phone display. The profile history content was to be partial hidden to limit screen space and only fully displayed when the user clicked on "read more..." button. All features for this section were succesfully tested to the various screen sizes.

The Contact section included address details for Kingdom Massage and a user form to allow a message to be sent for further details or to arrange an appointment. A nested grid layout was used to display at tablet and desktop screen sizes this information side by side in two columns, but at smaller phone sizes it was best to only display each col at the full screen view. This was tested and clearly displayed the info as intended at the differet screen sizes.

The user form was tested to ensure that all fields were completed and displayed an error message if not. The form was tested to ensure that the user can only enter numbers and symbols for the phone field and must enter a valid email address before the user can submit the input otherwise an error message will be displayed. 

Social media links were included in the footer this was tested to ensure that a new tab was opened and user directed to the correct page. The links also changed background colour when user hoovered over the link this was tested and showed a gradual transition as expected.  

___
### Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://dalecars.github.io/User-Centric-Frontend-Development-Milestone-Project/  

___
### Credits

#### Content

All content on the "Massage Therapy", "Treatment" and "About" sections in this site were written by Laura Gemmell.

#### Media
All photos were taken from shutterstock, a stock image library, with the exception of the profile photo of the massage therapists and the logo that was created.

#### Acknowledgements

The scrollSpy delay JavaScript function was found through this tutorial here.

