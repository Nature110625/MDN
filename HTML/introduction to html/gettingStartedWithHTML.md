# Getting Started With HTML
<ul>
    <li>HTML is a markup language that tells web browser how to structure the web pages we visit.</li>
    <li>HTML is not case sensitive.</li>
    <li>HTML consists of series of elements</li>
    <li>HTML element consists opening tag, content, closing tag.</li>
    <li>there is no requirement to add / at the end of a void element's tag. However it is a valid syntax and you may do this when you want yout HTML to be valid XML.</li>
    <li><b>Attributes</b> : contains extra information about the elements.
    <ul>
        <li>There shoule be space between attributes and element name.</li>
        <li>Attribute value must be wrapped with opening and closing quote marks.</li>
        <li>We can omitt opening and closing quote marks arount the value of few attributes. example: href.
    </ul>
    </li>
    <li><b>Boolean Attribute</b> : written without values (there attribute value is there name). example: disabled or disabled="disabled" both are valid
    <li><b>Void Elements </b>
    <ul>
        <li>consist of a single tag.</li>
        <li>typically used to insert/embed sth in document.</li>
        <li>eg: &lt;img&gt;</li>
    </ul>
    <li>Accessing innerHTML of elements from JavaScript will keep all the white space intact.</li>
    <li>
        <b>Entity References</b>
        <ul>
            <li>< : &lt;</li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul>
    </li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>
<h1>Anatomy of HTML Document</h1>
&lt;doctype html&gt;<br>
&lt;html lang="en-us"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;head&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;meta charset="utf-8"&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;title&gtMy test page&lt;/title&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;/head&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;body&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;p&gt;This is my page&lt;/p&gt;<br>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;/body&gt;<br>
&lt;/html&gt;

<ul>
    <li>The <b>doctype</b> was meant to act as links to a set of rules that the HTML page had to follow to be considered as good HTML. Now it is a historical artifact needs to be included for every thing else to work right. <br>&lt;doctype html&gt; is the shortest string of characters count as a valid doctype.</li>
    <li>UTF-8 is character encoding, which includes most characters from the vast majority of human written languages.</li>
    <li></li>
    <li></li>
</ul>

<h1>HTML Elements</h1>
<ol>
    <li>Paragraph element (&lt;p&gt;&lt;/p&gt;)</li> 
    <li>Image tag (&lt;img&gt;) : Atttributes are src (is required attribute), alt, width, height ...</li>
    <li>Anchor Element (&lt;a&gt;&lt;a&gt;) : Enclose text and turn them into links<br>Attributes are href, title ...</li>
    <li>&lt;html&gt; element : wraps all the content on the page<br>Sometimes known as the root element.</li>
    <li>&lt;head&gt; element : Acts as a container for everything included on HTML page, that is  not the content.</li>
    <li>&lt;meta&gt; element : this element represents metadata (data about data) that cannot be represented by other HTML meta related elements, like &lt;base&gt;, &lt;link&gt;, &lt;script&gt;, &lt;style&gt;, or &lt;title&gt;.<br> Attributes are charset ...</li>
    <li>&lt;title&gt; element : sets the title of the page (i.e, title that appears in the browser tab). Also discribe the page when it is bookmarked.</li>
    <li>&lt;body&gt; element : contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, etc.</li>
    <li></li>
    <li></li>
    <li></li>
</ol>
<h1>HTML Attributes</h1>
<ol>
    <li>src : Specifies the location of data</li>
    <li>alt : specifies text description of the image.</li>
    <li>width and height: expressed in pixels.</li>
    <li>disabled : boolean attribute, used to disable input elements.</li>
    <li>href: specifies the web address the link points to.</li>
    <li>title: specifies text discription of linked page.</li>
    <li>charset attribute specifies character encoding for our document</li>
    <li></li>
</ol>