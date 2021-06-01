Free Day Event For Allotment Beginners

Project Screenshots - /workspace/allotment-day-event/project.screenshots.docx
Project Testing Info - /workspace/allotment-day-event/validator-testing.docx
Project Wireframes - /workspace/allotment-day-event/wireframes-allotment-event.bmpr


Having recently taken on an allotment I know first-hand how daunting it is. The internet provides an overwhelming 
amount of information and although advice from other allotment holders is welcome it can be difficult to know
just how to get started and plan for that first year. My site advertises a day event for allotment beginners
addressing what I have found to be the crucial elements of starting up: planning, preparing, starting small and
maintenance. It is aimed at people who may have just taken on an allotment or who are currently on a waiting list 
for one. The site may also attract people interested in applying for an allotment and those with a general 
interest in growing fruit and vegetables.

Existing Features

- Navigation Bar - Features on all four pages of the site, is fully responsive and provides links to the Home,
Speakers, Register and Find Us pages. It is exactly placed with identical styling on each page for ease of
navigation without having to use forward and back buttons. With added text decoration, the user can easily see 
what page they are currenty viewing (underlined). Underline is also displayed when you mouse over a page link to 
enhance UI.

- The site/page title - This is visually distinct from other headings and text being styled with a background colour. It
provides a link to the home page evident with the classic blue underline and pointer cursor on hover.

- Introductory Paragraph - This clearly and concisely states when and where the event is being held, who the 
event is aimed at and what the event offers. Hyperlinks are included to take the user to the 'Find Us' page should
they require location and/or travel assistance and also to the 'Speakers' page in order for the user to gain insight
into who will be speaking at the event. Both these links encourage the user to interact with the site enhancing UX.

- Click to register button - The button is positioned near the main features and header area, users don't need to
look for it when visiting the site. The button provides a link to the registration page and can be recognised as
so with a shaded green colour on hover together with a cursor pointer when moused over. The button text reminds
and entices the user bu including - it's free! 

- Schedule of Events - Information is clearly presented, providing the user with insight into the day's event.
The user can easily ascertain stating/finishing times, together with break and lunch times. 

- YouTube Videos - The videos offer some entertainment to the user, allowing them to visit the site for longer.
The videos are applicable to the event and speakers. They have been styled not to play on page downlaod and
they can be controlled by the user in their own time. If the videos do not load a message will appear 'Your browser 
doesn't support HTML5 video.'

- Footer - The footer is of consistent design and seen on all pages of the site. The media links entice the user
to look at other events being held at the venue. As the event is free, the footer acts as a way to advertise the
center holding the event. The social media links provide direct links to Facebook, Twitter and Instagram with
a cursor pointer upon hover.

- Speaker Images - They provide visual appeal to the user. The images are appropriate in terms of capturing the 
essence of the event being advertised. They are presented in contrasting size to the speaker information, are
appropriately spaced and non-intrusive. The speaker images allow the user to be familiar with the speakers of the 
event. They are all set with alt text for the visually impaired using screen readers to better understand the
image. Alt text will also display if an mage cannot load for any reason.

- Speaker Information - Although brief, the speaker information engages the user with the speaker allowing for 
some informality. All text is relevant and allows the user to get to know the speakers prior to the event.

- Registration Form - The form is split into 4 fieldsets, not too overwhelming for the user. The form has been
styled to fit in with the sites colour scheme other than the checkboxes and radio inputs. I have used radio 
buttons to ensure the user can only select one selection. I have included validations on text input areas to 
the form won't submit prior to completion. Although it doesn't function on submit, the core structure and basis
are there for a functional feature. The input text fields highlight on input aiding the user.

- Find Us Map - The page includes an embedded google map with both a clickable link to google directions and
a seperate link below. I have also included a direct link to tfl.journey planner in order for the user to have
a ready link to explore travel options for the event. The map also displays local eating establishments.

Travel Options - For those users more local I have included various travel options to include various modes
of transport.

Accessibility - For those users disabled or hard of hearing/deaf the site includes the venue's allowances for
that. 

- Features to Implement
1. Include information/links for places to eat lunch
2. Include contact details of who to contact for more information
3. Add privacy policy to registration form
4. Include automatic transition between input boxes on registration form
5. Use js/jquery to enforce at least one of the checkboxes is ticked in fieldset 2, 3 and 4 of form
6. Use js to include 'read more' buttons instead of overview column in table, drop down could include more details
7. Ensure registration shuts off and shows as full when capacity of venue is reached
8. Style radio and checkboxes in line with page style i.e. remove automatic blue
9. Make the registration form workable, currently doesn't work as a submittable form
10. Charge for future events, include payment facility using js/stripe

Testing - Validator Testing (see validator-testing.docx)
Code validated using: https://validator.w3.org/ and https://validator.w3.org/

- index.html
1. Error: The element button must not appear as a descendant of the a element. Fix: placed button outside of 
attribute and amended CSS styling element id's.

2. Error: th start tag in table body. Fix: placed th inside tr tags.

3. Error: Attribute not allowed on element at this point. Fix: placed button outside of attribute and amended 
CSS styling element id's.

4. Error: Text not allowed in element iframe in this context. Fix: Not required as per 
https://github.com/wp-media/wp-rocket/issues/2312 and Code Institute turor - code ok, just validator not up to
date yet.

Re-validated : 
Errors (23)  - see above error 4
Attribute not allowed on element at this point. (6) 
Attribute controls not allowed on element iframe at this point. (2)
Attribute autoplay not allowed on element iframe at this point. (2)
Attribute muted not allowed on element iframe at this point. (2)
Text not allowed in element iframe in this context. (17)

- speakers.html
Document checking completed. No errors or warnings to show.

Re-validated: Document checking completed. No errors or warnings to show.

- Register.html
1. Error: Duplicate ID (5). Fix: Change id's to classes x3. 2 errors remaining, code correct, duplicate codes
been repeated for responsive elements - see lines 50 and 81, 62 and 86.

2. Error: Attribute select not allowed on element option at this point. Fix: placed value in correct "".

3. Error: Stray end tag p. Fix: Stray end tag p removed.

4. Error: Duplicate attribute type. Fix: type="reset"removed.

5. Error: The value of the for attribute of the label element must be the ID of a non-hidden form control.
Fix: Labelled in error, changed to p.

1. Warning: The first occurrence of ID was here. (5) Fix: See error 1. fixed.

Re-validated: 
Errors (2) - Explained above, see error 1
Duplicate ID . (2) · Hide all · Show all
Duplicate ID email.
Duplicate ID telephone.

- Find-us.html
1. Error: Text not allowed in element iframe in this context. (4) Fix: Fix: Not required as per 
https://github.com/wp-media/wp-rocket/issues/2312 and Code Institute turor - code ok, just validator not up to
date yet.

2. Error: No p element in scope but a p end tag seen. Fix: rogue id removed from p opening tag.

3. Error: Duplicate ID icon. Fix: Id's replaced with class.

Re-validated:
Errors (4) 
Text not allowed in element iframe in this context. (4) - see error 1 above

- 'style.css'

1. Error: Parse Error * { margin: 0; padding: 0px; border: none; }. Fix: No fix.

2. Error: .social-media iProperty margin-block-end doesn't exist : auto. Fix: removed rogue code. 

Re-validated:
5		Parse Error * { margin: 0; padding: 0px; border: none; } No fix.
 
- Unfixed Bugs - none

- Deployment

- Screenshots of Project

Credits
- Content - References (no direct copying of code)
https://www.w3schools.com/cssref/pr_tab_table_layout.asp
https://stackoverflow.com/questions/8097744/how-do-i-center-this-form-in-css
https://www.w3schools.com/html/html_links.asp
https://stackoverflow.com/questions/19826663/why-is-my-youtube-video-not-showing-up/19826763
http://support.google.com/maps/answer/144361?co=GENIE.Platform%3DDesktop&hl=encourage

Code Institute's Diploma in Software Development (E-commerce Applications), course notes and videos

https://fonts.googleapis.com/css2?family=Open+Sans&family=Ubuntu:wght@300&display=swap'

- Media

https://www.youtube.com/watch?v=N8ZMzN40q0g
https://www.youtube.com/embed/BZtAwplllgo
https://www.youtube.com/embed/ToyvxcLP14Q

https://kit.fontawesome.com/7f60e0134f.js







