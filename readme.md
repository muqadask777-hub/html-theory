Aapka likha hua content bilkul sahi aur accurate hai! Kisi bhi question ka answer galat nahi hai. Lekin GitHub par jo text bohot bada aur bold ho raha tha (jaisa aapne pichli picture mein dikhaya), usko theek karne aur Markdown format ko bilkul perfect banane ke liye maine aapke poore assignment ko achhi tarah organize kar diya hai.
Maine har question ko ## Question (Heading 2) bana diya hai aur code blocks ko proper format mein kar diya hai. Aap bas iss poore text ko copy karke apni README.md file mein paste kar dein, aapka text bilkul normal aur professional dikhega!
```markdown
## Question 0: What is HTML and what is the difference between HTML and HTML5?

**Answer:**
HTML stands for HyperText Markup Language. It is used to create webpages and structure content like text, images, links, and forms.

**Difference between HTML and HTML5:**
* HTML is the older version.
* HTML5 is the latest version.
* HTML5 supports audio and video directly without any extra plugins.
* HTML5 introduced new semantic tags like `<header>` and `<footer>`.

**Example:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>HTML5 Video</title>
</head>
<body>
    <video controls width="320">
        <source src="video.mp4" type="video/mp4">
    </video>
</body>
</html>

```
## Question 1: What are semantic HTML tags? Why are they important in web development?
**Answer:**
Semantic HTML tags are tags that describe the meaning of the content clearly to both the browser and the developer.
**Examples:**
 * <header>
 * <footer>
 * <section>
 * <article>
**These tags are important because:**
 * They make code easy for humans to understand and maintain.
 * They improve SEO (Search Engine Optimization) so Google can rank the site better.
 * They help screen readers for better accessibility for visually impaired users.
**Example:**
```html
<header>
  <h1>My Website Title</h1>
</header>

```
## Question 2: What is the difference between <div> and <span> tags?
**Answer:**
<div> and <span> are both container tags used to group content, but they work differently:
 * **<div>:** It is a block-level element. It always starts on a new line, takes up the full available width, and is used for large sections of a webpage.
 * **<span>:** It is an inline element. It does not start on a new line, takes up only the required width of its content, and is used for small text styling.
**Example:**
```html
<div>This is a div tag (takes full width)</div>
<p>This is a paragraph with a <span style="color: red;">red span tag</span> inside it.</p>

```
## Question 3: Explain the difference between block-level elements and inline elements.
**Answer:**
 * **Block-level elements:** They always start on a new line and take up the full 100% width of the page.
   * *Examples:* <div>, <p>, <h1> to <h6>
 * **Inline elements:** They do not start on a new line. They stay in the same flow and take up only the width needed by their content.
   * *Examples:* <span>, <a>, <strong>
## Question 4: What is the purpose of the DOCTYPE declaration in HTML?
**Answer:**
The <!DOCTYPE html> declaration tells the web browser which version of HTML is being used on the webpage. Writing it at the very top helps the browser display and render the webpage properly in modern HTML5.
**Example:**
```html
<!DOCTYPE html>
<html>
  </html>

```
## Question 5: What is the difference between id and class attributes?
**Answer:**
 * **id:** It is a unique identifier. It can be used for **only one** element per webpage (like a fingerprint).
 * **class:** It is a reusable identifier. It can be assigned to **multiple** elements on the same webpage (like a school uniform).
**Example:**
```html
<p id="main-title">Hello (Unique ID)</p>

<p class="text-blue">Paragraph 1</p>
<p class="text-blue">Paragraph 2</p>

```
## Question 6: How do you create a form in HTML? Which input types are commonly used?
**Answer:**
A form is created using the <form> tag, which holds different input elements to collect user data.
**Common input types:**
 * text (for names)
 * email (for email addresses)
 * password (hides typed characters)
 * checkbox (allows multiple selections)
 * radio (allows only one selection from a group)
 * submit (a button to send the form data)
**Example:**
```html
<form action="/submit" method="POST">
  <input type="text" placeholder="Name">
  <input type="email" placeholder="Email">
  <input type="password" placeholder="Password">
  <input type="submit" value="Submit Form">
</form>

```
## Question 7: What are meta tags in HTML and why are they used?
**Answer:**
Meta tags provide background information (metadata) about the webpage. They go inside the <head> tag and do not appear directly on the screen.
**They are used for:**
 * **SEO:** Providing descriptions for search engines.
 * **Character encoding:** Setting characters via charset="UTF-8".
 * **Responsive design:** Making sure the site scales correctly on mobile screens.
**Example:**
```html
<meta charset="UTF-8">
<meta name="description" content="Free HTML Tutorial for beginners">

```
## Question 8: Explain the purpose of the alt attribute in the <img> tag.
**Answer:**
The alt (alternative text) attribute gives a text description of an image.
**It is useful when:**
 * The image fails to load due to a slow internet connection or a broken link.
 * Visually impaired people use screen readers (the software reads the alt text aloud).
 * Search engines crawl the site to understand what the image shows.
**Example:**
```html
<img src="cat.jpg" alt="A cute white cat sleeping on a blanket">

```
## Question 9: How do you make an image clickable in HTML?
**Answer:**
An image can be made clickable by wrapping the <img> tag completely inside an <a> (anchor/link) tag.
**Example:**
```html
<a href="[https://google.com](https://google.com)">
  <img src="google-logo.png" alt="Google Homepage">
</a>

```
## Question 10: What is the difference between JPG, PNG, SVG, and WebP image formats in web development?
**Answer:**
 * **JPG:** Best for complex photographs. It compresses files well but does not support transparent backgrounds.
 * **PNG:** Best for logos and graphics because it supports high-quality transparent (see-through) backgrounds.
 * **SVG:** A vector format best for icons and simple illustrations. It never gets blurry or pixelated when you zoom in because it uses math paths.
 * **WebP:** A modern format that provides high quality with much smaller file sizes than JPG and PNG, making websites load faster.
## Question 11: What are semantic tags introduced in HTML5 such as <header>, <footer>, <section>, and <article>?
**Answer:**
These are layout tags introduced in HTML5 to divide a webpage into meaningful blocks instead of using generic <div> tags:
 * **<header>:** Defines the top section of a page (logo, search bar, menu).
 * **<footer>:** Defines the bottom section (copyright, links, contact info).
 * **<section>:** Defines a specific thematic section or chapter of a page.
 * **<article>:** Wraps independent, self-contained content (like a blog post or news story).
**Example:**
```html
<header>Website Header</header>

<section>
  <article>
    <h2>News Article Title</h2>
    <p>Article content goes here.</p>
  </article>
</section>

<footer>Website Footer</footer>

```
## Question 12: What is the difference between <script>, async, and defer in HTML?
**Answer:**
 * **Normal <script>:** Pauses the loading of the HTML page entirely while it downloads and runs the JavaScript file. (Slows down page load).
 * **async:** Downloads the script in the background while HTML continues loading, but pauses HTML to run the script the exact second it finishes downloading.
 * **defer:** Downloads the script in the background while HTML loads, but waits until the entire HTML page is fully loaded before running it. (Best practice).
**Example:**
```html
<script src="app.js"></script>
<script async src="analytics.js"></script>
<script defer src="main.js"></script>

```
## Question 13: How do you embed audio and video in HTML5?
**Answer:**
HTML5 provides native <audio> and <video> tags to play media directly without external tools. The controls attribute adds play, pause, and volume buttons.
**Audio Example:**
```html
<audio controls>
  <source src="song.mp3" type="audio/mp3">
</audio>

```
**Video Example:**
```html
<video controls width="400">
  <source src="movie.mp4" type="video/mp4">
</video>

```
## Question 14: What is the difference between relative paths and absolute paths in HTML?
**Answer:**
 * **Relative paths:** Point to a file location inside your own local project folders (e.g., src="images/pic.jpg").
 * **Absolute paths:** Point to a complete external web address with the full URL anywhere on the internet (e.g., src="https://example.com/pic.jpg").
## Question 15: What are data attributes in HTML (data-*)? Where are they used?
**Answer:**
Data attributes (data-*) let you embed custom, private data directly inside standard HTML elements. The * can be replaced with any word you like. They are widely used with JavaScript to read data quickly without altering the layout.
**Example:**
```html
<button data-id="101" data-status="active">Click User</button>

```
## Question 16: What is the purpose of the viewport meta tag in responsive web design?
**Answer:**
The viewport meta tag controls how a webpage is displayed on mobile screens. Without it, mobile browsers render pages at desktop width, making them tiny. This tag forces the website width to match the device screen width so it scales perfectly.
**Example:**
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">

```
## Question 17: How can you improve SEO using HTML?
**Answer:**
You can improve search rankings directly through clean HTML by:
 1. Using proper semantic tags (<nav>, <main>, <article>).
 2. Keeping a correct heading order and using only one unique <h1> tag per page.
 3. Writing clear <title> tags and <meta name="description"> tags.
 4. Adding descriptive alt text to all images.
## Question 18: What are accessibility best practices in HTML?
**Answer:**
To make websites usable for everyone, including people with disabilities:
 * Always provide descriptive alt text for images.
 * Use semantic elements instead of unreadable <div> nests.
 * Always connect form inputs to text <label> elements using the for attribute.
 * Use clean HTML structure so elements can be navigated easily using the keyboard Tab key.
**Example:**
```html
<label for="user-email">Email Address:</label>
<input type="email" id="user-email">

```
## Question 19: What is the difference between <strong> vs <b> and <em> vs <i> tags?
**Answer:**
 * **<strong> vs <b>:** Both make text bold. However, <strong> adds strong semantic importance (interpreted by screen readers), while <b> is purely for visual bold styling without any extra meaning.
 * **<em> vs <i>:** Both turn text into italics. However, <em> emphasizes the spoken meaning of words, while <i> is just a visual italic style for things like technical terms or book names.
**Example:**
```html
<strong>Important Warning!</strong>
<b>Just bold text for layout looks</b>

<p>You <em>must</em> complete this now.</p>
<p>The term <i>HTML</i> stands for language.</p>

```
```

```
