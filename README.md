# Information Architecture 2, Project (Summer 2020)
## E-Comm Web Store: Design, Content & Responsive Styling
**Value: 40% of course grade**

### Project Overview

Create the "index" page for an e-commerce retail store, selling any product of your choosing. Think of the "index" page, like the first page of a listing of all available products, products of a category, or the results of a search - where multiple different products are displayed (in brief, not necessarily with _all_ product info), and a (fake) pagination component at the bottom shows this is _"X products of Y total"_.

A sample HTML page has been provided as `index.html`, with a structured sample product (repeated five times, as an example). You may use this markup as a guide, or as the starting markup to modify as needed. At minimum, the product content should be modified to add your store's unique products by simply updated the given content to create at least five unique products. Each product should have enough information available to allow a user to add it to their cart.

**This page is a styled _"template"_ layout, not a functional web store. Meaning, products are not loaded from a database, added to a cart, or purchased. Your goal for this project is simply to structure and style a single page for a web store, with the understanding that a developer will connect this template to a database and payment processing service.**

Note that [Google's Material Icons library](https://material.io/resources/icons/) has been included in the project to give you a starting set of icons, which you may use, or remove/replace as you see fit.

### Deliverables

You will be completing two (2) deliverables:

1. [Styled website, suitable for small-width viewports](#deliverable-a-styled-website-small-width-viewports-only) (25%)
2. [Completely responsive website](#deliverable-b-complete-responsive-website-all-viewport-sizes) (15%)

#### Deliverable A: Styled website (small-width viewports only)
##### Due: Jul 31st, 2020, 11:59pm (25% of final)

Be sure to:
- Create unique content for at least 5 products
- Consider the content outside of the products (logo, menu, filters, etc) and modify as needed
- Decide on a colour and font scheme for your site, use CSS variables to store them
- Complete the styling for a site suitable for a small, portrait-oriented device (aka "mobile")
- Content should remain fluid and fill the entire width of the viewport (minus spacing on the outer edges as needed)
- Use clean and readable HTML and CSS, adhering to all "best practices" learned in the course

Your styling (CSS) may include any/all properties learned in class (or beyond) for text/fonts and basic layouts.

The page will be graded in the latest version of Google Chrome (both browser AND "device" mode) with testing in viewport widths ranging between 320px (minimum) and 639px (maximum) only. (Note, do not restrict your design to either of those numbers, just know the site should look suitable at any viewport size in that range)

Before submitting, ensure the site:
- Passes w3c validation: <https://validator.w3.org/#validate_by_input>
- Scores green across all Google Chrome "Audit" metrics

#### Deliverable B: Complete responsive website (all viewport sizes)
##### Due: Aug 14th, 2020, 11:59pm (15% of final)

Complete the remaining style for this site using `@media` queries to create at least two "breakpoints" (three layouts in total)

- Use breakpoints of your choosing
- Site should meet best practices for design at all viewports, on all devices
- Use this opportunity to continue to improve the overall design, look and feel

### Other notes and tips

**Create a content list**: Visit 3-5 existing e-commerce stores and compare the content and functionality for each. Specifically, look at a single product and what information is shown/presented, as well as the site overall (header, menu, footer, etc). Look for commonalities amongst them, as well as unique/interesting content that improves the overall shopping experience. When creating a content list, consider *everything* a web store would require in terms of information **and** functionality. The sample HTML provided in `index.html` has mostly just the basics, but you will want to modify/add additional content to complete the project.

**Think "mobile first"**: To start, resist the urge to view your site in any viewport greater than 600px (ideally between 320-400px). This will force you to focus first on styling and content, rather than fiddling with layout CSS, which can be the most challenging to get right.

### Submission

- All projects will be uploaded to your personal Github account as a public repo
- Commits must be made prior to the due dates to be considered
- Github Pages must be activated on your site can be viewed live on the web
- The live url must be added to the "Website" field of the repository's "About"
- Both urls (code, and live) will be collected prior to the first deliverable being due
- The same repo links should be used for both deliverables
