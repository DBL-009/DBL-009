---
title: "HTML Semantic"
datePublished: Fri Aug 29 2025 17:16:39 GMT+0000 (Coordinated Universal Time)
cuid: cmex3hfsh000202jj9jovca7n
slug: html-semantic
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1756474214443/a9ed24c5-06ee-4f78-bdf8-e7ab0cd04634.webp

---

**HTML** **semantics** refers to using HTML elements according to their meaning and purpose, not just for visual presentation. Semantic HTML elements clearly describe their meaning in a human- and machine-readable way. This helps browsers, search engines, and assistive technologies understand the structure and content of your web pages.

**Whey HTML Semantic Matters**

**SEO**: Search engines understand the content and context of pages for better indexing.

**Maintainability**: Code is easier to read and maintain for developers.

**Accessibility**: Screen readers and assistive technologies can navigate and interpret content better.

**Examples of html semantic tags and how they work**

&lt;header&gt; Introduces a page or section; contains headings, nav, etc.

example

```plaintext
<header>
<h1>
semantic html
</h1>
</header>
```

&lt;nav&gt; Defines navigation link

Example

```plaintext
<nav>
    <li><a href="/home">Home</a></li>
    <li><a href="/about">About</a></li>
    <li><a href="/contact">Contact</a></li>
  </ul>
</nav><article> Shows self contained element
```

&lt;section&gt; Used for grouping related content.

Example

```plaintext
<section>
<h1>html semantics</h1>
<p>HTML  semantics refers to using HTML elements according to their meaning and purpose, not just for visual presentation. Semantic HTML elements clearly describe their meaning in a human- and machine-readable way. This helps browsers, search engines, and assistive technologies understand the structure and content of your web pages.

</p>
</section>
```

&lt;aside&gt; for content related to the main content, like sidebars or pull quotes

Example

```plaintext
<aside>
  <h2>Quick Tips</h2>
  <ul>
    <li>Use semantic HTML for better accessibility.</li>
    <li>Group related content with <code>&lt;section&gt;</code>.</li>
    <li>Use <code>&lt;aside&gt;</code> for side information.</li>
  </ul>
</aside>
```

&lt;footer&gt; Contains footer information, such as copyright or contact links.

Example

```plaintext
<footer>
  <p>&copy; 2025 My Website. All rights reserved.</p>
  <nav>
    <a href="/privacy">Privacy Policy</a> |
    <a href="/contact">Contact Us</a>
  </nav>
</footer>
```

&lt;main&gt; Specifies the main content of the document.

Example

```plaintext
<main>
  <section>
    <h2>Welcome to Our Site</h2>
    <p>This website demonstrates the use of semantic HTML elements. </p>
  </section>
  <article>
    <h2>Whey semantic html</h2>
    <p>Semantic html are beter than non-semantic html</p>
  </article>
</main>
```

&lt;article&gt; For self-contained content, such as a blog post or news article.

* Example
    
* ```plaintext
        <article>
          <h2>How to Use Semantic HTML</h2>
          <p>
            Semantic HTML improves accessibility and SEO by using tags that describe the meaning of the content.
            For example, use <code>&lt;section&gt;</code> for grouped content and <code>&lt;article&gt;</code> for independent items.
          </p>
          <footer>
            <p>Written by DBL-009 August  2025</p>
          </footer>
        </article>
    ```
    
    Those are examples of some html semantics and their purpose individualy. Now lets make an example that involves all the html semantics that we wave worked with that is &lt;header&gt;, &lt;article&gt;, &lt;nav&gt;, &lt;section&gt;, &lt;footer&gt;, &lt;main&gt;, and &lt;aside&gt;
    
* the following code is made of html semantic which we will try to compare with another code that is not made with html semantic
    
* ```plaintext
      <!DOCTYPE html>
      <html lang="en">
        <head>
          <meta charset="UTF-8">
          <title>Semantic HTML Layout Example</title>
        </head>
        <body>
          <header>
            <h1>My Semantic Website</h1>
            <nav>
              <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#blog">Blog</a></li>
              </ul>
            </nav>
          </header>
          <main>
            <section id="about">
              <h2>About Us</h2>
              <p>We create accessible and SEO-friendly websites using semantic HTML.</p>
            </section>
            <article id="blog">
              <h2>Latest Blog Post</h2>
              <p>Semantic HTML tags make your pages easier to understand for browsers and assistive technologies.</p>
              <footer>
                <p>Written by DBL-009, August 2025</p>
              </footer>
            </article>
            <aside>
              <h3>Did You Know?</h3>
              <p>Using semantic tags improves your site's search engine ranking!</p>
            </aside>
          </main>
          <footer>
            <p>&copy; 2025 My Semantic Website. All rights reserved.</p>
          </footer>
        </body>
      </html>
    ```
    
    In the comparison, we are going to make another code that is not made of semantic html. As you continue learning, try learning these two codes by yourself and you will see the deference.
    
* Now this is a code that is made of non-semantic html
    
* ```plaintext
      <!DOCTYPE html>
      <html lang="en">
        <head>
          <meta charset="UTF-8">
          <title>Non-Semantic HTML Layout Example</title>
        </head>
        <body>
          <div id="header">
            <h1>My Non-Semantic Website</h1>
            <div id="navigation">
              <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#blog">Blog</a></li>
              </ul>
            </div>
          </div>
          <div id="main">
            <div id="about">
              <h2>About Us</h2>
              <p>We create websites using traditional HTML structure.</p>
            </div>
            <div id="blog">
              <h2>Latest Blog Post</h2>
              <p>Using only <code>&lt;div&gt;</code> and <code>&lt;span&gt;</code> elements for layout is not recommended for accessibility or SEO.</p>
              <div class="footer">
                <p>Written by DBL-009, August 2025</p>
              </div>
            </div>
            <div id="aside">
              <h3>Did You Know?</h3>
              <p>Semantic tags are better for search engines and screen readers!</p>
            </div>
          </div>
          <div id="footer">
            <p>&copy; 2025 My Non-Semantic Website. All rights reserved.</p>
          </div>
        </body>
      </html>
    ```
    
    The next figure will display to you the deference between a html semantic and a html non semantic structure.
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1756486463937/53339920-04a9-4b0b-922e-6e53815c3b45.webp align="center")
    
    To my conclusion i will advice all learners and developers to invest more on html semantic than html non semantic for a good work .
    
* I pray and guarantee that are all coding wizards like me. Adios
    
* email lewismuiruri009@gmail.com GitHub DBL-009