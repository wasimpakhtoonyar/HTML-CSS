# Review of Week 1

Here is some lessons we learned from reviewing your work in week 1
- Please read the notes and check the links to avoid having the same issues in the future
-------------------------------

### Design
- Get some design inspiration online before you start working on project:
https://dribbble.com/

- Draw your design on a piece of paper (wireframes) and think of your HTML tags before start working on your:
https://design-nation.icons8.com/how-to-build-a-website-on-paper-fde0d8c1ad18

### Naming Conventions and Indentation

- Avoid spaces in file names

- Name your css meaningful name and avoid capitalizing first letter:
(styles.css, main.css, about.css, responsive.css)

- Make folders for projects assets (img, css, fonts, others) for better folder structure

- Name your main html file index.html (The browser search for this file if we didn't specify the main website page)

- USE external CSS file (avoid inline-styling)

- Always start with semantic html elements (<header><nav><article><section><aside><footer>...), and add <div> for wrapping content to make your file more structures or for the purpose of styling

- Avoid <div> tags with no class or id

- Start your work with:
<body>
<header><nav></nav></header>
<main>
</main>
<footer></footer>
</body>

- Identify your html element and use heading elements the right way <h1><h2>,<h3>....
https://medium.com/alistapart/writing-html-with-accessibility-in-mind-a62026493412

- In each section you CAN use <header><h1><p><footer> to identify the content

- Use <h1> when you start new section (better SEO)

- Use proper indentation for your HTML to make readable for you and other developers:
https://www.granneman.com/webdev/coding/formatting-and-indenting-your-html
Use this website if your code editor doesn't have auto-indentation:
https://htmlformatter.com/

- Add classes to all main blocks,  wrappers, elements (easier to select in css and JavaScript in the future)

- You CAN add more than one class for HTML element (<h1 class="title">, <h1 class="title red bold-text left">

- Add meaningful class names represents the content in each element

- Avoid right-left in class names (conceder viewing your work on mobile so the left-right would be top-bottom and you will mess the styling)

- Class naming best practice, check:
https://css-tricks.com/bem-101/

- Add comment in the end of HTML section tags to identify it:
<section><p>some text</p></section> <!-- end Education section -->

- In css files: Start with the general properties and work on each section at a time

- Add comments to CSS files to make more structures and easy to read and edit
https://www.sitepoint.com/how-good-are-your-html-and-css-comments/

- When styling images: if set one dimension to fixed pixel size (width: 300px) set the other property to auto (height: auto) to avoid image streching

- Use CSS Box Model currently (border, padding, margin):
https://css-tricks.com/the-css-box-model/

- When using JavaScript libraries, put the link in the end of your body so the page won't wait until this library loads (check the documentation for each library)

- Copy your html code to this page for validation to catch closing tags and other errors:
https://validator.w3.org/#validate_by_input


### VSCode Extensions
VSCode extensions to install before the class tomorrow:
- CSS Peek
- Debugger for Chrome
- Git Lens
- Highlight Matching Tag
- HTML CSS Support
- IntelliSense for CSS class names in HTML
- Live Server
- Project Manager
- Settings Sync
- VS Live Share

https://www.youtube.com/watch?v=PmdbndOoKq4
