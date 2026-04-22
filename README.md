HTML Review


Q: What does HTML stand for?
A: Hypertext Markup Language

Q: What is the difference between <head> and <body>?
A:      <head> --> Metadata - read by the browser
        <body> --> The content displayed on the screen, read by the user.

Q: Name THREE semantic HTML elements.
A: <header></header>
   <footer></footer>
   <main></main>
   <nav></nav>
   <article></article>
   <aside></aside>

Q: What attribute does an <a> tag need to create a link?
A:  href --> <a href="https://www.google.com">
    <br>
    <img>
    <link>
    <meta>

Q: What does <!DOCTYPE html> do?
A: Tells the browser that the file here is in HTML.

Every HTML file has the same SKELETON (boilerplate, template) structure: -->

<!DOCTYPE html>
<html lang="en">
<head>
    <title></title>
    <link>
    <style></style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width", initial-scale="1.0">
        <!-- - Makes the page Responsive -->
</head>
<body>
    <header>
    <nav>Contains any Navigation bar elements</nav>
    </header>
    <h1>Largest Header/most important heading. ONLY ONCE per page.</h1>
    <!-- All VISIBLE elements go inside the body -->
</body>
</html>


PART 2: Core HTML Elements
Headings 1 - 6
<h1> --> There should only be 1 <h1> per page
<h2> --> Section titles, subtitles
<h3> --> Subsections
<h4>
<h5> --> Fine print (Copyright statements, etc.)
<h6> --> Fine print (Copyright statements, etc.)

Text elements
<p> --> paragraph tag
<strong> --> bold/important tezt - semantic weight
<em> --> italic / emphasized text - semantic weight
<br> --> line break (void element)
<u> --> underline
<hr> --> Horizontal row --> visual line divider (void element)
<span> --> inline element, does not create a line break
<mark> --> highlights text

HTML Lists

Unordered list --> Bullet Points (used for items with no ranking order)
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

Ordered List --> Numbered / Alphabetized List (used for steps, rankings, etc.)
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

Links

Q: How do I create a link to sllboces.org?
A: <a href="https://sllboces.org" target="_blank">SLL Boces</a>

Q: How do I create a link to about.html - relative path (page in the same 
A: directory)?
<a href="about.html">About</a>

Q: Link to a file in the content folder?
A: <a href="content/page.html">Page</a>

Q: A link to another section of the page?
A: <a href="#about">Jump to the About section</a>

Q: A link to send an email?
A: <a href="mailto:student@sllboces.org">Email Me</a>

Images
Q: What are the two required attributes for <img> tags?
A: alt - accessibility text
   src - file path to the Image

<img src="images/hero.jpg" alt="Adirondack Mountains in Fall">
<img src="images/logo.png" alt="SLL BOCES Logo">

Q: What is hot-linking an image?
A: Linking to an image somewhere on the Internet (best for placeholder images for design purposes, replace before publishing the site, remove if the image gets moved). 

<img src="https://google.com/2/abc/files/images/myGoogleImage.png" alt="my hotlinked image">

Part 3:
Q: What is a semantic HTML element?
A: Semantic elements describe the meaning of the content inside of the element, not just the way it looks

Q: Reason why we use semantic elements?
A: Organization (Teamwork) - Allows other developers to more easily read and understand your code.

Affects the Document Object model - How the browser reads or understands the content.

Accessibility - Allows screen readers to understand the structure and meaning behind content.

SEO - Search Engine Optimization - How search engines rank well-structured pages - Moves them higher in the search results.

Semantic tags replaced the use of <div> tags:
    <div class="header"> vs <header>

Layout Semantic Elements: Header, nav, main, section, aside, footer.

Content Semantic Elements:
<figure> - Image with a caption
<figcaption> - Caption for a figure image
<time> - A date or time value
<address> - Contact address info
<mark> - Highlighted text
<details> / <summary> - Expand and collapse more details
<div> - Non-semantic container, made semantic by adding a class or ID