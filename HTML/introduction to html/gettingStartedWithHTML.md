# Getting Started With HTML

* HTML is a markup language that tells web browser how to structure the web pages we visit.
* HTML is not case sensitive.
* HTML consists of series of elements.
* HTML element consists opening tag, content, closing tag.
* there is no requirement to add / at the end of a void element's tag. However it is a valid syntax and you may do this when you want yout HTML to be valid XML.
* **Attributes** : contains extra information about the elements.
    * There shoule be space between attributes and element name.
    * Attribute value must be wrapped with opening and closing quote marks.
    * We can omitt opening and closing quote marks arount the value of few attributes. example: href.
* **Boolean Attribute** : written without values (there attribute value is there name). example: disabled or disabled="disabled" both are valid
* **Void Elements**
    * consist of a single tag.
    * typically used to insert/embed sth in document.
    * eg: &lt;img&gt;
* Accessing innerHTML of elements from JavaScript will keep all the white space intact.
    
* **Entity References**
    |literal character|character reference equivalent|
    |-----------------|------------------------------|
    | < | `&lt`     |
    | > | `&gt`     |
    | " | `&quot`   |
    | ' | `&apos`   |
    | & | `&amp`    |
* HTML comments
    ```
        <!-- <p>I am!</p> -->
    ```
    
## Anatomy of HTML Document
```
    <doctype html>
    <html lang="en-us">
        <head>
            <meta charset="utf-8">
            <title>My test page</title>
        </head>
        <body>
            <p>This is my page</p>
        </body>
    </html>
```

* The **doctype** was meant to act as links to a set of rules that the HTML page had to follow to be considered as good HTML. Now it is a historical artifact needs to be included for every thing else to work right. 
<br>&lt;doctype html&gt; is the shortest string of characters count as a valid doctype.
*UTF-8 is character encoding, which includes most characters from the vast majority of human written languages.

# What's in the head? Metadata in HTML
* contains information such as 
    * `<title>`
    * link to css
    * links to custom fevicons
    * other metadata 
        * data about the HTML, such as author, important keywords that describe the document.
* specifying a discription that includes keywords relating to content of our page is useful as it has potential to make our page appear higher in relevant searches performed in search engine (i.e. Search Engine Optimization). Ex: `<meta name="description" content="This web docs aims to provide short note of HTML">`
    * Nowadays these are ignored by search engines, because spammers were just filling the keyword list with hundreds of keywords, biasing results.
* Sitelinks
    * are relevant subpages listed below the main home page link of searched site.
    * configurable Google's webmaster tools (a way to make our site's search result better in google search engine)
* Open Graph Data
    * a metadata protocol
    * invented by Facebook to provide richer matadata for websites.
# HTML Elements
1. Paragraph element `<p></p>`
2. Image tag `<img>` : Atttributes are src (is required attribute), alt, width, height ...
3. Anchor Element `<a></a>`: Enclose text and turn them into links
    * Attributes are href, title ...
4. `<html>` element : wraps all the content on the page
    * Sometimes known as the root element.
5. `<head>` element : Acts as a container for everything included on HTML page, that is  not the content.
6. `<meta>` element
    * is an official way of adding metadata to a document
    * this element represents metadata (data about data) that cannot be represented by other HTML meta related elements, like `<base>`, `<link>`, `<script>`, `<style>`, or `<title>`.
    * Attributes are charset, name, content ...
7. `<title>` element 
    * sets the title of the page (i.e, title that appears in the browser tab and also discribe the page when it is bookmarked). 
    * is a metadata.
8. `<body>` element : contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, etc.

# HTML Attributes
* **src** : Specifies the location of data
* **alt** : specifies text description of the image.
* **width** and height: expressed in pixels.
* **disabled** : boolean attribute, used to disable input elements.
* **href**: specifies the web address the link points to.
* **title**: specifies text discription of linked page.
* **charset**: specifies character encoding for our document.
* **name**: specifies the type of meta element it is; what type of information it contains. eg. name="author", etc.
* **content**: Specifies the actual meta content. example: content="Prakriti", etc.