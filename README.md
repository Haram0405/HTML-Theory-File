<h2>Brief Answers</h2>
<h3>Question 0:  What is HTML and what is the difference between HTML and HTML5?</h3>
<h3>Answer:</h3>
    <b>i- HTML(Old Version):</b><br><br> The basic code used to build websites in the past. It could not play video or audio without using slow extra software like flash player.<br><br>
    <b>ii- HTML5(Modern Standard):</b><br><br> The latest version used today. It has native support to play video and audio directly inside the browser.<br><br>
    <b>iii- Mobile Friendly:</b><br><br> HTML5 includes mobile responsive features so website look perfect on the smartphones automatically.
<br>

<h3>Question 1:  What are semantic HTML tags? Why are they important in web development?</h3>
<h3>Answer:</h3>
      <b>Definition:</b> Tags that clearly describe their meaning to both the developer and the browser. <br>Like, header tag tells the browser it is a top section.
        <br><br>
      <b>Benefits:</b> They have search engines like Google find your website faster (SEO) and help blind users navigate your side using screen readers.
        <br><br>
      <b>Example:</b> header, nav, article, section, footer(tags).
<br>

<h3>Question 2:  What is the difference between div and span tags?</h3>
<h3>Answer:</h3>
     <b>Div Tag:</b><br> <br> i- It is a block level tag.<br> ii- A large container box used to group layout sections. <br> iii- It always starts on a brand new line and takes up the full width of the screen.<br>
  <br>
      <b>Span Tag:</b><br> <br> i-  It is an inline tag.<br> ii- A small container used to style specific words or text. <br> iii- It does not start a new line and stays inside the same sentence.<br>
<br>
<b>Code Example:</b><br>

```html
<div>
  <p>This is a <span>red</span> word inside a layout box.</p>
</div>
```

<h3>Question 3:  Explain the difference between block-level elements and inline elements.</h3>
<h3>Answer:</h3>
<br>
     <b>Block-level Elements:</b> <br><br> These elements start on a fresh line and stretch as wide as the screen. They push any element after them down.
     <br><br>
     <b>Examples:</b><br> <br> div, p, h1, ul, form(tags).
     <br><br>
     <b>Inline Elements:</b> <br><br> These elements stay on the same line. They sit side by side with other content and only take up the width of their actual text.
     <br><br>
     <b>Examples:</b><br><br> span, a, img, strong, em(tags).
<br>
<h3>Question 4:  What is the purpose of the DOCTYPE declaration in HTML?</h3>
<h3>Answer:</h3>
<br>
<b>i. Version Declaration:</b> <br>
<br> It is written at the very top of your document to tell the browser that this file uses modern HTML5.<br><br>
<b>ii. Standard Rendering Mode:</b><br><br> It forces the browser to display your website correctly using modern rules.<br><br>
<b>iii. Prevents Quirks Mode:</b><br><br> Without this tag, browsers will render your site using old, broken rules from the 1990s, causing formatting errors.
<br>
<h3>Question 5:  What is the difference between id and class attributes?</h3>
<h3>Answer:</h3>
<b>ID Attribute:</b><br><br> A unique name given to exactly one element on a webpage. You cannot reuse the same ID name on that page. It uses the # prefix in CSS.

<br>
<b>Class Attribute:</b> <br><br> A reusable name given to multiple elements on a webpage. You can use it to apply the same style to many items at once. It uses the . prefix in CSS.
<br><br>
<b>Code Example:</b>

```html
<!-- ID used once -->
<h1 id="main-heading">Welcome</h1>

<!-- Class used multiple times -->
<p class="error-text">First Error</p>
<p class="error-text">Second Error</p>
```

<h3>Question 6:  How do you create a form in HTML? Which input types are commonly used?</h3>
<h3>Answer:</h3>
<b>Form Tag:</b> The form tag acts as a wrapper container to gather user information.<br><br>
<b>Action and Method:</b> The action attribute tells the form where to send the data, and the method defines how securely the data is sent.<br><br>
<b>Input Types:</b> Different input tags accept different types of data, such as usernames, secure passwords, or checkboxes.
<br><br>
<b>Code Example:</b>

```html
<form action="/submit-data" method="POST">
  <input type="text" placeholder="Enter Name">
  <input type="email" placeholder="Enter Email">
  <input type="password" placeholder="Enter Password">
  <input type="submit" value="Register Now">
</form>
```
<h3>Question 7:  What are meta tags in HTML and why are they used?</h3>
<h3>Answer:</h3>
<b>Definition:</b> Small snippets of code placed inside the head tag that provide hidden information about the webpage.<br><br>
<b>Visibility:</b> Regular users cannot see them on the screen, but search engines and browsers read them.<br><br>
<b>Usage:</b> They are used to set character encoding (UTF-8), write website descriptions for Google search results, and manage mobile responsiveness.
<br>

<h3>Question 8:  Explain the purpose of the alt attribute in the img tag.</h3>
<h3>Answer:</h3>
<b>Screen Readers:</b> It describes what an image shows to blind or visually impaired users by reading the text out loud.<br><br>
<b>Broken Images:</b> If a user has a weak internet connection and the image fails to load, this text is displayed in its place.<br><br>
<b>SEO Boost:</b> Search engines cannot visually look at photos, so they read the alt text to understand what the image represents.
<br><br>
<h3>Question 9:  How do you make an image clickable in HTML?</h3>
<h3>Answer:</h3>
<b>The Link Wrapper:</b> To turn an image into a clickable button, you wrap a standard img tag completely inside an a (anchor) hyperlink tag.<br><br>
<b>Code Example:</b>

```html
<a href="https://google.com">
  <img src="search-logo.png" alt="Google Search Button">
</a>
```

<br><br>
<h3>Question 10: What is the difference between JPG, PNG, SVG, and WebP image formats in web development?</h3>
<h3>Answer:</h3>
<b>JPG:</b> Best for normal realistic photographs. It offers small file sizes but does not support see-through backgrounds.<br><br>
<b>PNG: </b>Best for logos, clip art, and screenshots. It supports high quality and fully transparent, see-through backgrounds.<br><br>
<b>SVG:</b> A vector format based on math code. It can be stretched infinitely to any size without getting blurry or pixelated.<br><br>
<b>WebP: </b>A modern format created by Google. It provides the clear quality of a PNG but keeps the tiny file size of a JPG.
<br><br>
<h3>Question 11:  What are semantic tags introduced in HTML5 such as header, footer, section, and article?</h3>
<h3>Answer:</h3>
<b>header tag:</b> Used at the top of a webpage to hold logos, site names, and introduction menus.<br><br>
<b>nav:</b> Used exclusively to hold navigation menus and website links.<br><br>
<b>section:</b> Groups matching content together, like a "Contact Us" or "Services" block.<br><br>
<b>article:</b> Used for independent content that can be read anywhere on its own, like a blog post or news story.<br><br>
<b>footer:</b> Placed at the very bottom of the page for copyright notes and privacy links.
<br>

<h3>Question 12:  What is the difference between script, async, and defer in HTML?</h3>
<h3>Answer:</h3>
<b> (Normal) script:</b> The browser completely stops building the website HTML until the JavaScript file is fully downloaded and executed. This slows down the page.<br><br>
<b>Async (script async):</b> The JavaScript downloads in the background while the HTML builds, but the moment it finishes downloading, it pauses the HTML to execute immediately. It can run out of order.<br><br>
<b>Defer (script defer):</b> The JavaScript downloads quietly in the background and politely waits until the entire HTML layout is fully built before executing. This is the best practice.
<br>
<h3>Question 13:  How do you embed audio and video in HTML5?</h3>
<h3>Answer:</h3>
<b>Native Elements:</b> HTML5 uses direct video and audio tags so you do not need third-party media applications.<br><br>
<b>The Controls Keyword:</b> You must add the word controls inside the tag, or the play, pause, and volume buttons will be invisible to the user.
<b>Code Example:</b>

```html
<!-- Video Player -->
<video src="movie.mp4" controls width="300"></video>

<!-- Audio Player -->
<audio src="song.mp3" controls></audio>
```
<br>

<h3>Question 14: What is the difference between relative paths and absolute paths in HTML?</h3>
<h3>Answer:</h3>
<b>Relative Path:</b> Links to a file based on your current folder location inside your project. Ideal for local development files.<br><br>
<b>Example:</b> src="images/avatar.png"<br><br>
<b>Absolute Path:</b> Links to the complete web URL address on the internet. Used when pulling resources from external websites.Example: src="https://example.com"
<br>

<h3>Question 15:  What are data attributes in HTML (data-*)? Where are they used?</h3>
<h3>Answer:</h3>
<b>Purpose:</b> They let you store your own custom, private information directly inside an HTML tag without breaking layout rules.<br><br>
<b>Syntax:</b> You start the attribute name with data- followed by any lowercase word you choose.<br><br>
<b>JavaScript Link:</b> Developers look up these values later using JavaScript to create interactive, dynamic page updates.
<b>Code Example:</b>

```html
<div data-user-id="5501" data-membership="premium">John Doe</div>
```
<br>
<h3>Question 16:  What is the purpose of the viewport meta tag in responsive web design?</h3>
<h3>Answer:</h3>
<b>The Problem:</b> Mobile phones inherently try to open websites using giant desktop layouts, making all the text look microscopic.<br><br>
<b>The Solution:</b> This tag tells the browser to automatically resize the webpage scale to fit the exact width of whatever mobile device screen is opening it.
<b>Code Example:</b>

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

<br>
<h3>Question 17:  How can you improve SEO using HTML?</h3>
<h3>Answer:</h3>
<b>Heading Order:</b> Use exactly one h1 tag for the main topic of your page, followed in structural order by h2 and h3 tags for subsections.<br><br>
<b>Page Titles:</b> Write descriptive, keyword-rich names inside the <title> tag located in your page header.<br><br>
<b>Structural Elements:</b> Stop using empty div boxes for everything. Use descriptive layout wrappers like main, article, and nav.
<br>
<h3>Question 18:  What are accessibility best practices in HTML?</h3>
<h3>Answer:</h3>
<b>Input Labels:</b> Use explicit label tags connected to form fields via the for attribute so screen readers tell users exactly what to type.<br><br>
<b>Keyboard Control:</b> Ensure all links, buttons, and form inputs can be fully navigated using just the keyboard Tab key.<br><br>
<b>High Contrast:</b> Ensure text colors are distinct and dark enough against background elements so they are easy for everyone to read.
<br>

<h3>Question 19:  What is the difference between strong vs b and em vs i tags?</h3>
<h3>Answer:</h3>
<b>strong</b>: Marks text as highly important. It tells search engines and screen readers to place stress on the words. Visually displays as bold.<br><br>
<b>b</b>: Bolds text purely for visual style and design. It adds no extra meaning or importance.<br><br>
<b>em:</b> Emphasizes the conversational tone of a word. Visually displays as italic.<br><br>
<b>i:</b> Italicizes text purely for visual style, such as when formatting technical terms, foreign words, or fictional thoughts.
