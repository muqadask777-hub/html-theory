# HTML Theory Assignment

 Q0: What is HTML and what is the difference between HTML and HTML5?
HTML is the standard language used to create the basic structure of websites. It tells the browser what content to show, like text, images, or buttons.

### Key Differences:
* **HTML (Older versions):** Needed extra plugins (like Adobe Flash) to play audio or video. It didn't support mobile devices very well.
* **HTML5 (Latest version):** Has built-in support for audio and video using simple tags like `<audio>` and `<video>`. It's built for modern mobile screens and includes new semantic elements.

---

 Q1: What are semantic HTML tags? Why are they important in web development?
Semantic tags are HTML elements that clearly describe their meaning to both the browser and the developer. Instead of using generic tags like `<div>`, you use tags that tell you exactly what the content is. Examples include `<header>`, `<footer>`, and `<article>`.

### Why they matter:
1. **Better SEO:** Search engines like Google can easily scan your page and understand which part is the menu, the main content, or the footer.
2. **Accessibility:** Screen readers use these tags to help visually impaired users navigate the page easily.
3. **Clean Code:** It makes the code much easier to read and maintain for developers.

## Q2: What is the difference between `<div>` and `<span>` tags?
* **`<div>`:** It is a **block-level** element. It always starts on a fresh line and stretches out to take up the full width available. It's mostly used to group large sections together for layout purposes.
* **`<span>`:** It is an **inline** element. It does not start on a new line and only takes up as much space as the text or content inside it. It's perfect for styling a specific word inside a paragraph.

```html
<div>
  <h3>This is a separate section using a div</h3>
</div>

<p>This is a regular sentence with a <span style="color: blue;">blue word</span> inside it.</p>
Q3: Explain the difference between block-level elements and inline elements.
Block-level elements: These elements always start on a new line and push any content after them down. They take up the 100% width of their parent container.
Examples: <div>, <p>, <h1> to <h6>, <ul>, <li>
Inline elements: These elements stay in line with the surrounding content. They do not start on a fresh line and their width depends only on what is inside them.
Examples: <span>, <a>, <img>, <strong>
Q4: What is the purpose of the DOCTYPE declaration in HTML?
<!DOCTYPE html> is not an HTML tag; it's an instruction written at the very top of the document. It tells the web browser that the file is written in HTML5. This ensures the browser loads and renders the page correctly without messing up the layout.
<!DOCTYPE html>
<html>
  <head>
    <title>My Project</title>
  </head>
  <body>
  </body>
</html>
Q5: What is the difference between id and class attributes?
ID (id): An ID must be completely unique on a single webpage. You cannot give the same ID to more than one element. It's typically used when targeting a specific element with JavaScript or CSS.
Class (class): A class is reusable. You can apply the exact same class name to multiple elements across the page. It's the best way to apply shared CSS styling.
<div id="main-navigation">Unique Header</div>
<p class="error-text">This is an error message.</p>
<p class="error-text">This is another error message using the same class.</p>
Q6: How do you create a form in HTML? Which input types are commonly used?
You create a form using the <form> tag. Inside it, you add different kinds of <input> elements depending on what data you need from the user.
Common Input Types:
type="text": For regular text inputs like names.
type="password": Hides the text as dots or stars.
type="email": Ensures the user types a proper email format.
type="submit": A button to send the form data.
<form action="/login" method="POST">
  <input type="text" placeholder="Username">
  <input type="email" placeholder="Email Address">
  <input type="password" placeholder="Password">
  <button type="submit">Submit Form</button>
</form>
Q7: What are meta tags in HTML and why are they used?
Meta tags go inside the <head> section of the HTML document. They don't show up on the actual webpage. Instead, they provide data (metadata) about the page to browsers and search engines, like the page description, character encoding, or responsive scaling settings.
<meta charset="UTF-8"> <meta name="description" content="A simple HTML theory guide for developers."> ```

---

## Q8: Explain the purpose of the alt attribute in the `<img>` tag.
The `alt` (Alternate Text) attribute is crucial for two reasons:
1. If an image fails to load due to broken links or a slow internet connection, this text shows up instead so the user knows what was there.
2. Screen readers read this text out loud to visually impaired users, making the site accessible.

```html
<img src="profile-pic.jpg" alt="Muqadas profile picture">
Q9: How do you make an image clickable in HTML?
To make an image clickable, you just wrap the <img> tag inside an anchor (<a>) link tag.
<a href="[https://github.com](https://github.com)">
  <img src="github-logo.png" alt="Click to go to GitHub">
</a>
Q10: What is the difference between JPG, PNG, SVG, and WebP image formats in web development?
JPG / JPEG: Great for real photographs because it keeps file sizes small, but it does not support transparent backgrounds and loses quality when compressed.
PNG: Supports fully transparent backgrounds and maintains high quality, but the file size can get quite heavy.
SVG: A vector format meant for icons and logos. You can scale it up to any size without it ever getting blurry or pixelated.
WebP: A modern format created for the web. It delivers the high quality of PNG and small size of JPG all in one, making websites load faster.
Q11: What are semantic tags introduced in HTML5 such as <header>, <footer>, <section>, and <article>?
HTML5 introduced structure-specific tags to replace endless <div> elements:
<header>: Holds the top content of a page or section, usually containing logos and navigation menus.
<footer>: Placed at the bottom of the page for copyrights, contact info, and secondary links.
<section>: Used to group broad, related content together on a page.
<article>: For standalone, independent content that could make sense on its own, like a blog post or news story.
Q12: What is the difference between <script>, async, and defer in HTML?
Normal <script>: The browser stops parsing the HTML completely while it downloads and runs the JavaScript file. This can slow down page loading.
async: The script downloads in the background, but the moment it's ready, it pauses the HTML parser to run immediately. This means scripts might run out of order.
defer: The script downloads in the background and waits to run until the browser has finished completely parsing the HTML. This is the safest way to load scripts.
<script src="app.js" defer></script>
Q13: How do you embed audio and video in HTML5?
HTML5 allows you to add multimedia natively using <audio> and <video> tags without external players. Adding the controls attribute gives the user play, pause, and volume buttons.
<audio controls>
  <source src="audio-file.mp3" type="audio/mpeg">
</audio>

<video width="400" controls>
  <source src="video-file.mp4" type="video/mp4">
</video>
Q14: What is the difference between relative paths and absolute paths in HTML?
Absolute Path: The complete internet address of a file, including the protocol (http/https) and domain name.
Example: href="https://images.unsplash.com/photo.jpg"
Relative Path: Points to a file relative to where the current HTML file is located in the local project folder.
Example: href="./about.html" or src="images/logo.png"
Q15: What are data attributes in HTML (data-*)? Where are they used?
Data attributes let you store custom, extra information inside standard HTML tags without changing how they look. They always start with data-. You can easily pull this stored data later using JavaScript or use it for CSS styling.
<div class="product-card" data-id="1024" data-category="electronics">
  Smart Laptop
</div>
Q16: What is the purpose of the viewport meta tag in responsive web design?
The viewport meta tag forces the mobile browser to adjust the page layout to match the physical width of the screen. Without it, mobile phones will display the full desktop layout zoomed out, making text unreadable.
<meta name="viewport" content="width=device-width, initial-scale=1.0">
Q17: How can you improve SEO using HTML?
You can build search-engine-friendly HTML by:
Using proper semantic elements (<main>, <nav>, <header>).
Ensuring each page has only one <h1> tag for its main title, and maintaining a logical heading order (h2, h3).
Always writing descriptive alt text for images.
Adding an accurate <title> and <meta name="description"> inside the head tag.
Q18: What are accessibility best practices in HTML?
Making a site accessible means ensuring everyone, including disabled users, can use it:
Always connect input fields with a proper <label> tag.
Provide clear alt text for images.
Use aria-label fields when text isn't visible on screen but needs context.
Build menus so they can be fully navigated using just a keyboard (using Tab keys).
Q19: What is the difference between <strong> vs <b> and <em> vs <i> tags?
<b> and <i>: These tags are purely visual. They make text bold or italicized without giving it any extra importance or context.
<strong> and <em>: These tags carry semantic weight. They change how text looks (bold/italic) but also notify screen readers and search engines that the words are highly important or emphasized.
<p>This word is just <b>bolded</b> for visual style.</p>
<p>Please <strong>danger</strong> do not cross this line.</p>