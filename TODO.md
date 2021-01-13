# Open Tasks:

### Checkbox for Email

People have to confirm that their data gets sent to us. A simple checkbox with _"Ich bin damit einverstanden, meine persönlichen Daten an Explore Europe e.V. weiterzuleiten"_ should do the trick.

### Logo

We have to implement the company's logo into /index.html. Minor adjustments in Figma or similar may be required.

### Imprint Styling

Right now, imprint.html is ugly. It doesn't need to be the prettiest thing ever, since it's just a legal requirement, but why don't make it look at leat somewhat appealing?

### Success Page

Right now, feedback for our form submission is given by Netlify's default success message.
We should build a success page to give the user some feedback and bring him back to our main page.

### Site Transfer

Right now, the project is running in @lbeul's personal Netlify & Github account. In order to separate the page from his private projects and make it maintainable for future employees, it should run on its own environment.

- Create netlify account for exploreeurope
- Transfer site to new account (Netlify support can help)
- Create exploreeurope github account (or team)
- Fork repo
- Change CI pipeline to point at new repo

### Burger & Dropdown

Right now, our site doesn't really need a dropdown menu, as it's really small and just a landing page to sell a product. However, it may be expanded in a while, so it's good to already have the dropdown menu ready to roll. :)
