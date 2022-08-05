# Permt Readme

I live in an area where parking is restricted. However, one can obtain virtual parking permits for guests through a city website. The way the process used to work for me was when we'd have a visitor, they would text me their license plate number, then I would sign in to the website, navigate to order a new permit, confirm the permit. Once confirmed, I then had to navigate to a new page where I would have to enter the license plate twice along with checking a radio button before submitting. Not the worst thing in the world, but I knew there had to be a better way.

Permt (deployed using Github Pages) is the front end of that better way. It is a single html file that has an input box, a submit button, and, when necessary, the status of the request. Clicking the submit button then consumes the backend API of Permt (deployed with Heroku), which does all of the above steps and confirms if a permit has been created. The backend was built with Node and Express.

Please do not use this app unless you are visiting me and need a permit. The number of permits is limited.
