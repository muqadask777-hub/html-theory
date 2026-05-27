Question 0: What is HTML and what is the difference between HTML and HTML5?

Answer:

HTML stands for HyperText Markup Language. It is used to create webpages and structure content like text, images, links, and forms.

Difference between HTML and HTML5

HTML is the older version.

HTML5 is the latest version.

HTML5 supports audio and video directly.

HTML5 introduced semantic tags like <header> and <footer>.


Example:

<!DOCTYPE html>
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>


---

Question 1: What are semantic HTML tags? Why are they important in web development?

Answer:

Semantic HTML tags are tags that describe the meaning of the content clearly.

Examples:

<header>

<footer>

<section>

<article>


These tags are important because:

They make code easy to understand.

They improve SEO.

They help screen readers for accessibility.


Example:

<header>
  <h1>My Website</h1>
</header>


---

Question 2: What is the difference between <div> and <span> tags?

Answer:

<div> and <span> are both container tags but they work differently.

<div>

It is a block-level element.

It takes full width.

Used for large sections of a webpage.


<span>

It is an inline element.

It takes only required width.

Used for small text styling.


Example:

<div>This is a div tag</div>

<span>This is a span tag</span>


---

Question 3: Explain the difference between block-level elements and inline elements.

Answer:

Block-level elements start on a new line and take full width.

Examples:

<div>

<p>

<h1>


Inline elements do not start on a new line and take only needed width.

Examples:

<span>

<a>

<strong>



---

Question 4: What is the purpose of the DOCTYPE declaration in HTML?

Answer:

DOCTYPE declaration tells the browser which version of HTML is being used. It helps the browser display the webpage correctly.

Example:

<!DOCTYPE html>


---

Question 5: What is the difference between id and class attributes?

Answer:

id is unique and used for one element only.
class can be used for multiple elements.

Example:

<p id="title">Hello</p>

<p class="text">Paragraph 1</p>
<p class="text">Paragraph 2</p>


---

Question 6: How do you create a form in HTML? Which input types are commonly used?

Answer:

A form is created using the <form> tag.

Common input types:

text

email

password

checkbox

radio

submit


Example:

<form>
  <input type="text" placeholder="Name">
  <input type="email" placeholder="Email">
  <input type="password" placeholder="Password">
  <input type="submit">
</form>


---

Question 7: What are meta tags in HTML and why are they used?

Answer:

Meta tags provide information about the webpage.

They are used for:

SEO

Character encoding

Responsive design


Example:

<meta charset="UTF-8">
<meta name="description" content="HTML Tutorial">


---

Question 8: Explain the purpose of the alt attribute in the <img> tag.

Answer:

The alt attribute gives alternative text for an image.

It is useful when:

The image does not load.

A screen reader is used.


Example:

<img src="cat.jpg" alt="Cute cat">


---

Question 9: How do you make an image clickable in HTML?

Answer:

An image can be made clickable by placing it inside the <a> tag.

Example:

<a href="https://google.com">
  <img src="image.jpg" alt="Image">
</a>


---

Question 10: What is the difference between JPG, PNG, SVG, and WebP image formats in web development?

Answer:

JPG

Used for photos and compressed images.

PNG

Supports transparent background.

SVG

Vector image format that does not lose quality.

WebP

Modern format with smaller size and good quality.


---

Question 11: What are semantic tags introduced in HTML5 such as <header>, <footer>, <section>, and <article>?

Answer:

Semantic tags in HTML5 describe different parts of a webpage.

<header> → top section

<footer> → bottom section

<section> → page section

<article> → independent content


Example:

<header>Website Header</header>

<section>
  <article>News Article</article>
</section>

<footer>Website Footer</footer>


---

Question 12: What is the difference between <script>, async, and defer in HTML?

Answer:

Normal <script>

Stops HTML loading until the script loads.

async

Loads the script parallel and runs immediately.

defer

Loads parallel but runs after HTML is fully loaded.

Example:

<script src="app.js"></script>

<script async src="app.js"></script>

<script defer src="app.js"></script>


---

Question 13: How do you embed audio and video in HTML5?

Answer:

HTML5 provides <audio> and <video> tags to embed media.

Audio Example

<audio controls>
  <source src="song.mp3" type="audio/mp3">
</audio>

Video Example

<video controls width="400">
  <source src="movie.mp4" type="video/mp4">
</video>


---

Question 14: What is the difference between relative paths and absolute paths in HTML?

Answer:

Relative paths use local folder locations.
Absolute paths use full URLs.

Example of Relative Path:

<img src="images/pic.jpg">

Example of Absolute Path:

<img src="https://example.com/pic.jpg">


---

Question 15: What are data attributes in HTML (data-*)? Where are they used?

Answer:

Data attributes (data-*) store extra custom information in HTML elements.

They are commonly used with JavaScript.

Example:

<button data-id="101">Click</button>


---

Question 16: What is the purpose of the viewport meta tag in responsive web design?

Answer:

The viewport meta tag helps webpages display properly on mobile devices.

Example:

<meta name="viewport" content="width=device-width, initial-scale=1.0">


---

Question 17: How can you improve SEO using HTML?

Answer:

SEO can be improved in HTML by:

Using semantic tags

Adding proper headings

Using meta descriptions

Adding alt text to images

Using meaningful titles


Example:

<title>HTML Tutorial</title>
<meta name="description" content="Learn HTML easily">


---

Question 18: What are accessibility best practices in HTML?

Answer:

Accessibility best practices in HTML include:

Using alt text for images

Using semantic tags

Adding labels in forms

Using proper heading order


Example:

<label for="email">Email</label>
<input type="email" id="email">


---

Question 19: What is the difference between <strong> vs <b> and <em> vs <i> tags?

Answer:

<strong> shows important text while <b> only makes text bold.

<em> shows emphasized text while <i> only makes text italic.

Example:

<strong>Important</strong>

<b>Bold Text</b>

<em>Emphasized</em>

<i>Italic Text</i>