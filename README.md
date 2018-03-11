## Build a Portfolio Site

### **Design**

#### Required Elements
The page at minimum includes all of the following:`
- at least 4 images
- title text (h1, h2, etc.)
- regular (paragraph) text
- a logo.

#### Semantic HTML
HTML5 semantic tags such as `<header>`, `<footer>`, `<article>`, `<section>` etc. are used to add meaning to the code.

No `<div>` or `<section>` tags are without a CSS class or id.

#### Custom Design
- Customize images and text.
- Customize placement of the elements on the page (grid layout) with `HTML`, `CSS` or both.
- Customize `CSS` styles applied at minimum to paragraph and heading elements.

#### Grid-Based Layout
- Page utilizes a grid-based layout with styles making use of the `flexbox` layout or a framework like `Bootstrap`, `Foundation`, etc.
- If you're using `Bootstrap`: the rows and columns of the grid must be wrapped in an element with a container class.

### Responsiveness

#### Cross-Device Compatibility
All content is responsive and displays on all display sizes. This includes:

- Desktop
- Mobile: Google Nexus 5
- Tablet: Apple iPad

An image's associated title and text renders next to the image in all viewport sizes.

#### Provide All Content
All content is rendered on all three devices. No content should be hidden on mobile devices.

#### Viewport meta Tag
Viewport `meta` tag is included in `HTML`. `(i.e. <meta name=”viewport” …)`

##### Responsive Images
If a CSS framework is used, classes provided by the CSS framework are used to make images responsive, otherwise media-queries are used to ensure responsiveness of images.

### Separation of Concerns

#### Styles Separated From HTML
Portfolio completely separates structure (`HTML`) from design/style (`CSS`). There are no `style` attributes present in the body of the `HTML` document. There are no `<style> `elements in the document.

#### File structure
Files are organized with a directory structure that separates files based on functionality. For example:
`css`/ for stylesheets
`img`/ for images
`js`/ for JavaScript files

### Code Quality

#### HTML Formatting rules
- All code ( `HTML` element names, attributes, attribute values) is lowercase (except `text/CDATA`).
- Code does not have trailing white spaces.
- Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
- Code uses a new line for every block, list or table element and indent every such child element (it's acceptable to put all `<li>` elements in one line).
- [Optional] When quoting attribute values, code uses double quotation marks.
