### HTML text formatting

```HTML
<b>This is a bold text .</b> <br>
<strong>This is a strong text . </strong> <br>
<i>This is an italic text. </i> <br>
<em>This is emphasized text</em> <br>
<u>This is an underlined text</u> <br>
<ins>This is an inserted text</ins> <br>
<small>This is a small text</small> <br>
<mark>This is a marked text</mark> <br>
<del>This is a deleted text</del>
<s>This is text is not relevent</s>
<p>(a+b)<sup>2</sup> = a<sup>2</sup> + 2ab + b<sup>2</sup></p>
<p>log<sub>a</sub>x = p, log<sub>b</sub>y = q, log<sub>c</sub>z = r</p>
```

### HTML `<time>` Tag

The `<time>` tag defines a specific time (or datetime).

The `datetime` attribute of this element is used translate the time into a machine-readable format so that browsers can offer to add date reminders through the user's calendar, and search engines can produce smarter search results.

```HTML
<p>Open from <time>10:00</time> to <time>21:00</time> every weekday.</p>
<p>I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>.</p>
```

Output :

**This is a bold text**
**This is a strong text**
_This is an italic text_
*This is emphasized text*
<u>This is an underlined text</u>
<ins>This is an inserted text</ins>
<small>This is a small text</small> <br>
<mark>This is a marked text</mark> <br>
~~This is a deleted text~~
~~This is a deleted text~~
<p>(a+b)<sup>2</sup> = a<sup>2</sup> + 2ab + b<sup>2</sup></p>
<p>log<sub>a</sub>x = p, log<sub>b</sub>y = q, log<sub>c</sub>z = r</p>

<p>Open from <time>10:00</time> to <time>21:00</time> every weekday.</p>
<p>I have a date on <time datetime="2008-02-14 20:00">Valentines day</time>.</p>

### HTML Quotations

```HTML
<q>This is a quotations</q>

HTML
<blockquote>
The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. It defines the content and structure of web content. It is often assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.
</blockquote>

The <dfn><abbr title="Hyper Text Markup Language">HTML</abbr></dfn> is the building block of the web.<br>

<address>
  Written by John Doe.<br>
  Visit us at:<br>
  Example.com<br>
  Box 564, Disneyland<br>
  USA
</address>
<br>

<p><b>The art work</b></p>
<img src="https://www.w3schools.com/html/img_the_scream.jpg" alt="">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893</p>
```

###### Output :

<q>This is a quotations</q>

HTML
<blockquote>
The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. It defines the content and structure of web content. It is often assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.
</blockquote>

The <dfn><abbr title="Hyper Text Markup Language">HTML</abbr></dfn> is the building block of the web.<br>

<address>
  Written by John Doe.<br>
  Visit us at:<br>
  Example.com<br>
  Box 564, Disneyland<br>
  USA
</address>

<p><b>The art work</b></p>
<img src="https://www.w3schools.com/html/img_the_scream.jpg" alt="">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893</p>

## HTML Directional Elements
### `<bdo>` Tag

BDO stands for Bi-Directional Override. The `<bdo>` tag is used to override the current text direction.

|Attribute|Value|Description|
|---|---|---|
|dir |ltr  <br>rtl|Required. Specifies the text direction of the text inside the <bdo> element|
```HTML
<bdo dir="rtl">This text direction is right to left </bdo>
```

***Output :***

<bdo dir="rtl">This text direction is right to left </bdo>

### `<bdi>` Tag

BDI stands for Bi-Directional Isolation. The `<bdi>` tag isolates a part of text that might be formatted in a different direction from other text outside it. This element is useful when embedding user-generated content with an unknown text direction.

### Example

Isolate the usernames from the surrounding text-direction settings

```HTML
<ul>  
  <li>User <bdi>hrefs</bdi>: 60 points</li>  
  <li>User <bdi>jdoe</bdi>: 80 points</li>  
  <li>User <bdi>إيان</bdi>: 90 points</li>  
</ul>
```

***Output :***
<ul>  
  <li>User <bdi>hrefs</bdi>: 60 points</li>  
  <li>User <bdi>jdoe</bdi>: 80 points</li>  
  <li>User <bdi>إيان</bdi>: 90 points</li>  
</ul>

### HTML `<ruby>` Tag

The `<ruby>` tag specifies a ruby annotation. A ruby annotation is a small extra text, attached to the main text to indicate the pronunciation or meaning of the corresponding characters. This kind of annotation is often used in Japanese publications.

Use `<ruby>` together with `<rt>` and `<rp>`.The `<ruby>` element consists of one or more characters that needs an explanation/pronunciation, and an `<rt>` element that gives that information, and an optional `<rp>` element that defines what to show for browsers that do not support ruby annotations.

```HTML
<p>We are learning <ruby>HTML<rp>(</rp><rt>Structure</rt><rp>)</rp></ruby><ruby>CSS <rp>(</rp><rt>Style</rt><rp>)</rp></ruby> and <ruby>JavaScript <rp>(</rp> <rt>Structure</rt><rp>)</rp></ruby></p>

<ruby>
  漢 <rt> kan </rt>
  字 <rt> ji </rt>
</ruby>
```

***Output :***
  <p>We are learning <ruby>HTML<rt>Structure</rt></ruby>  <ruby>CSS <rt>Style</rt></ruby> and <ruby>JavaScript <rt>Structure</rt></ruby></p>
  
  <ruby>
  漢 <rt> kan </rt>
  字 <rt> ji </rt>
</ruby>

### HTML Computer code

```HTML
<code>This is a computer code</code> <br>

<p>Press <kbd>Ctrl + C</kbd> for copy a text . </p> <br>

<p>Message from my computer:</p>

<p><samp>File not found.<br>Press F1 to continue</samp></p>

<p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>
```

Output :

<code>This is a computer code</code> <br>

<p>Press <kbd>Ctrl + C</kbd> for copy a text . </p> <br>

<p>Message from my computer:</p>

<p><samp>File not found.<br>Press F1 to continue</samp></p>

<p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>

### HTML Comments

```HTML
<h3>HTML Comments</h3>

<!-- This is a html single line comments -->
<!--

This is a html

multi line comment

or paragraph comments.

-->
<p>This is <!-- a great text--> a paragraph .</p>
```

Output : 

<!-- This is a html single line comments -->

<!--
This is a html

multi line comment

or paragraph comments.

-->
<p>This is <!-- a great text--> a paragraph .</p>