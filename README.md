# QAProcess
This document has been produced for all QA testers working at Gooey, and explains what is expected in regards to QA.

---
## Table of contents
- [Design](#design)
- [Useability](#useability)
- [Browsers](#browsers)
- [Standards](#standards)
- [Speed](#speed)
- [CMS](#CMS)
---

## Design

It is of fundamental importance that the build looks identical to the designs supplied:

- Check each design against the built page looking for any errors or inconsistencies.
- If there is mobile or tablet designs also check these against the build.
- The build should look identical to the designs unless otherwise agreed.

---

## Useability

Browse through the website as a user would, checking for any errors or bugs.

- Browse everypage via navigations in the header and footer.
- If there is a search bar, search the website using terms like 'the' to get results, and jibberish like 'ergferg' to return no results.
- If there is any filters, forms, logins or any other widgets - use them to check the functionality, styling and any errors.
- Check to see if the website has a 404 error page.

---

## Browsers

All websites should be thoroughly tested on multiple browsers and devices, and by using Browserstack.

- Check the website on IE (back to IE10 unless agreed otherwise), Edge (latest version), Chrome (latest version), Firefox (latest version) and Safari (latest version).
- Check the website using the in-house tablets.
- Check the website using the in-house phones.
- Check website on desktop, scaling the browser down to check for sizes in-between device sizes. The website should look good at all sizes, and not break at any size whatsoever.

---

## Standards

All code released by Gooey should be to a high standard, and semantic:

- Run each page through https://validator.w3.org/ and report any issues to the developer.
- Check the CSS has been concatenated and compressed.
- Check the JS has been concatenated and compressed.
- Check the source code of the website and report anything unusual or any inconsistencies.

---

## Speed

With Google assigning more and more weight to website speed, it is important that each website we produce is optimised properly:

- Run each page through https://developers.google.com/speed/pagespeed/insights/ and ensure the score for both desktop and mobile is 'good'.
- Check for page loading times when navigating the site on desktop, tablet and mobile.

---

## CMS

Login to the CMS and:

- Check that the CMS is client friendly, and you can create pages, posts easily.
- Create a test page and make sure this formats correctly on the frontend.
- Check what plugins have been installed, and advise to disable and delete any non-essential ones (i.e. clone posts, fakerpress).
- Check to see if Wordfence and WP Super Cache is installed but not activated.
- Check to see the user email address is not set to a @abitgooey.com address.

---

-- Produced by James Holloway - Gooey (Last updated 25/01/2018)
