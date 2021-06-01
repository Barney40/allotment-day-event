Free Day Event For Allotment Beginners

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

- The site/page title is visually distinct from other headings and text being styled with a background colour. It
provides a link to the home page evident with the classic blue underline and pointer cursor on hover.

- Introductory Paragraph - This clearly and concisely states when and where the event is being held, who the 
event is aimed at and what the event offers. Hyperlinks are included to take the user to the 'Find Us' page should
they require location and/or travel assistance and also to the 'Speakers' page in order for the user to gain insight
into who will be speaking at the event. Both these links encourage the user to interact with the site enhancing UX.

- Schedule of Events - 

YouTube Videos -
Hyperlinks -
Footer -
Speaker Images -
Speaker Information -
Registration Form -
Find Us Map -
External Links -
Travel Options -
Accessibility -

Features Left to Implement

Testing - Validator Testing (see validator-testing.docx)
Code validated using: https://validator.w3.org/ and https://validator.w3.org/

- index.html
1. Error: The element button must not appear as a descendant of the a element. Fix: placed button outside of 
attribute and amended CSS styling element id's.

2. Error: th start tag in table body. Fix: placed th inside tr tags.

3. Error: Attribute not allowed on element at this point. Fix: placed button outside of attribute and amended 
CSS styling element id's.

4. Error: Text not allowed in element iframe in this context. Fix: Unknown

Re-validated : 
Errors (23) · 
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
Errors (2) - Explained above
Duplicate ID . (2) · Hide all · Show all
Duplicate ID email.
Duplicate ID telephone.

- Find-us.html
1. Error: Text not allowed in element iframe in this context. (4) Fix: changed h1 to p.

2. Error: No p element in scope but a p end tag seen. Fix: rogue id removed from p opening tag.

3. Error: Duplicate ID icon. Fix: Id's replaced with class.

Re-validated:
Errors (4) · Hide all errors · Show all errors
Text not allowed in element iframe in this context. (4)

- 'style.css'

1. Error: Parse Error * { margin: 0; padding: 0px; border: none; }. Fix: No fix.

2. Error: .social-media iProperty margin-block-end doesn't exist : auto. Fix: removed rogue code. 

Re-validated:
5		Parse Error * { margin: 0; padding: 0px; border: none; } No fix.
 







- Unfixed Bugs

Deployment

Credits
- Content
- Media









