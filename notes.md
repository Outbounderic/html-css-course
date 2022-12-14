# Front-end vs Back-end development

We visit a page, the browser sends a request to the web server where the website is hosted, the server then sends a response with all of the files requested. It responds with html, css, and javascript, which are the core web technologies. The browser then renders the website with the provided files.

The process of writing html, css, and js is called front-end development. When the files are simply stored on the server a request will return a static website.

When you visit a dynamic website the request is sent to a server where the website is hosted, not just stored. Web apps store and maitain a larger amount of features to store in such things as a database. Applications that are executed on the backend will use nodejs or python that will take the request and assemble the proper response on the server. Everytime you visit the website a new version will be assembled and sent.

The files are sent as before and the browser renders the site in the same way.

## The three languages

HTML is the content of the webpage. CSS is the styling of that content on the page. JS is the dynamic effects and data of the webpage.

---

## HTML

HyperText Markup Language is a core language for structuring and describing the content of a page.

HTML uses _elements_ to describe it's content.
Web browsers understand HTML and render the code as websites.

### HTML Element

`<p>HTML is a markup language</p>`
An element has an opening tag, the content and the closing tag.
If the content is another element it is called a child element and it is the parent element.

### HTML Document Structure

Consists of a DOCTYPE declaration, the html tag which has two children elements called head and body.
