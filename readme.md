
#Palett.es

This project aims create an marketplace for all of the the open-sourced
color collections I and other users has created based on the initial brand-colors project.

###Todo

#####[ ] Create a CLI that utilizes the generic project
![](https://raw.githubusercontent.com/yeoman/yo/master/screenshot.png)
yo is an already existing CLI that I will use as an inspiration for this project. 
It's a tool to quickly setup web boilerplates. I want to create something similar where
a user can install my CLI and then just run `palette`. 
My CLI will then guide the user through the process and then generate
a boilerplate version of the generic project created below.

Estimate: 1 week

#####[ ] Make a generic version of the brand-colors project
In order to enable the CLI meantioned above, I need to implement a generic version
of brand-colors that will be used as the boilerplate of above CLI.

Estimate: 2 weeks

Users should be able to import a list of colors or a list of images(containing colors :).

#####[ ] Create an web-interface that utilizes the generic project (stretch goal)
It would be very optimal if there was a way for people to generate these color
collections online as well.

Estimate: 3 weeks

#####[ ] Create a tutorial how to use import.io
In order to create these collections easily, it would be very
helpful for users to be able to scrape homepages for images that would
be used to generate a color collection.

Estimate: 1 week

#####[ ] Sketch a design for palette.es homepage
I am a huge fan of simplistic design. So I hope to design
something beautiful and exciting, while maintaining ease-to-use.

Estimate: 2 weeks

#####[ ] Implement initial palette.es homepage
Implement above design using JavaScript, CSS, HTML. Should be written
using React and build by Webpack so that I can deploy the homepage to
GitHub Pages, which give me free hosting and CDN.

Estimate: 2 weeks

#####[ ] Implement backend-service for generating unique posters per purchase (stretch goal)
I want each poster to be unique, so each poster should have an unique number, but
the colors should also update if the open-sourced project has been updated
since the last time someone bought the same poster.

My idea is to generate an HTML + CSS, then using Phantom.js to render it as a homepage.
I will then use Phantom.js `screenshot()` functionality to save the poster to disk.

Estimate: 2 weeks

#####[ ] Implement backend-service for doing purchases
I need to write a backend service that can validate purchases using Stripe so
that when someone tries to download a poster, I can verify that the file hasn't
been downloaded before and that the purchase was approved by the bank.

Estimate: 1 week

#####[ ] Implement backend-service for sending emails
I need to implement a service that will send an email containing the
poster if the above purchase-service approves a purchase.

Estimate: 0.5 week

#####[ ] Implement backend-service for sending physical posters (stretch goal)
I need to implement a service that will talk with the printing company
if a pruchase was approved by the bank, sending them an image, but also the
address where the poster should been sent.

Estimate: 1 week

#####[ ] Find printing company to partner with (stretch goal)
I obviously need to find a printing company that has an API
enabling me to create posters but also getting them sent to the buyer.

Estimate: 2 weeks

#####[ ] Create a marketing strategy (stretch goal)
If I have the time, it would be interesting to spend some
time investigating what the best way would be for me to
market this marketplace once it's done.

Estimate: 1 week


###Planning
- 14 weeks including stretch goals
- 7 weeks
