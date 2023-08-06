Cat Shelter

The Cat Shelter website is a simple one page website with links to different parts of the page. The purpose of the website is to raise awareness of the cat shelter, to raise funds for the cat shelter and to make it easy for people to adopt cats from the cat shelter.

Users of this website will be able to read about the cat shelter, learn about the cats available for adoption and donate money.

amiresponsive.png

Features

Navigation bar

The navigation bar helps users navigate around the webpage. For mobile phones the menu is displayed when the menu toggle button is pressed.

Main picture

The main picture shows users what the site is about.

Main section with contact details and donate button

This section clearly shows what the website is about. It also shows the contact details and donate button. These are very important for an animal shelter.

About section

This gives the background story of the shelter. This helps build trust and support.

Section about the cats

This section shows users what cats are available for adoption. I also gives a description of the cats to help users make a decision.

Contact form

This gives users an easy way to contact the animal shelter.

Donate section

This section gives users the information they need to donate money to the cat shelter online.

Testing

My website was tested with the following tools:

- various browsers

- <https://validator.w3.org/>. The first test showed a few errors, I corrected these and then did another test that had no errors.

html test.png

= <https://jigsaw.w3.org/css-validator/validator>. The first test showed a few errors. I corrected most of them but it's still showing one error: "496 Parse Error"

css test.png

- <https://ui.dev/amiresponsive>

amiresponsive.png

- Lighthouse in Google devtools.

Lighthouse.png

Bugs

For the wider desktop computer media query I copied and pasted the media query for narrow desktop computers while forgetting to update the width. This led to lots of problems with the layout but when I fixed it all of those problems were resolved.

The donate button wasn't responsive because the left and right padding was in pixels. I solved this by adding a percentage left and right padding.

The fixed header had to be removed for larger screens as it was covering part of the grid below it and that didn't work with the design. It did work with mobile as there was a picture below it that could be partially covered without messing up the design.