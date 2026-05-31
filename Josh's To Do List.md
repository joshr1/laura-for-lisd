# Now To Do's
[x] Update the mail to contact links to send to 'lauraforlisd@gmail.com' that currently send to info@laurforlisd.com
[x] Change the name of the 'strengths.html' page name to 'why.html' and update the main menu button to from 'Strengths' to 'Why I'm Running' and ensure it points to why.html
[x] Replace this line in the footer 'Paid for by Laura for LISD. Not authorized by any candidate or candidate's committee.' with 'Political advertisement paid for by Laura for LISD campaign.' 


# My To do's
- Connect the 'Volunteer' forms to a Google Sheet on her account
- Update all the photos
- Remove the logo from the footer
- Remove privacy and terms links (or get them populated)
[x] Make a horizontal friendly logo and update the logo in the header 

## Formspree Form Integration
- Create a free account at formspree.io
- Create a new form in Formspree and copy the endpoint ID (looks like `https://formspree.io/f/XXXXXXXX`)
-- Actual Endpoints
--- Volunteer "https://formspree.io/f/xpqnkbzk"
--- Stay in Touch "https://formspree.io/f/mkoekywy"
- Optionally create a second form endpoint if you want volunteer submissions separate from general signups
- Give Claude the endpoint ID(s) and ask to wire up all forms:
  - Homepage hero 'Join Our Campaign' form (index.html)
  - Homepage bottom email signup form (index.html)
  - Meet Laura bottom email signup form (meet-laura.html)
  - Why I'm Running bottom email signup form (why.html)
  - Priorities bottom email signup form (priorities.html)
  - Volunteer form including 'How would you like to help?' checkboxes and address fields (volunteer.html)
- Test each form by submitting a test entry and confirming it arrives in Laura's email
- Set the reply-to email in Formspree dashboard to Laura's address