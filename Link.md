Links are found in nearly all web pages. Links allow users to click their way from page to page.

```HTML
<a href="www.w3schools.com">W3School</a>
```

Output : 

<a href="www.w3schools.com">W3School</a>

### [[HTML Iframes#Target Attributes|Target Attribute]]

```HTML
<a href="https://www.w3schools.com/" target="_blank">W3School</a>
```


The `target` attribute can have one of the following values :

- `_self` - Default. Opens the document in the same window/tab as it was clicked
- `_blank` - Opens the document in a new window or tab
- `_parent` - Opens the document in the parent frame
- `_top` - Opens the document in the full body of the window

##### Absolute URLs vs. Relative URLs

Both examples above are using an **absolute URL** (a full web address) in the `href` attribute.

A local link (a link to a page within the same website) is specified with a **relative URL** (without the "https://www" part):

##### Example

##### Absolute URLs

```HTML
<p><a href="https://www.w3.org/">W3C</a></p>  
<p><a href="https://www.google.com/">Google</a></p>  
  
```
##### Relative URLs  

```HTML
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>

```


##### Image as a Link

The image below is a link. Try to click on it.

```HTML
<a href="default.asp"><img src="image source" alt="HTML tutorial" style="width:42px;height:42px;"></a>
```

##### Link to an email and phone


```HTML
<a href="mailto:someone@example.com">Send email</a>
<a href="tel:+88011111111111">Send email</a>
```

##### Button as a link

```HTML
<button onclick="document.location='default.asp'">HTML Tutorial</button>
```

##### Link title

```HTML

<a href="https://www.w3schools.com/html/" title="Go to W3Schools HTML section">Visit our HTML Tutorial</a>
```

##### Bookmark link

```HTML

  <a href="#C7">Jump chapter 7</a> <br>

  <a href="#C15">Jump chapter 15</a> <br>

  <a href="#C24">Jump chapter 24</a>

  
  <h2 id="C1">Chapter 1</h2>

  <p>This is chapter 1</p>

  <h2 id="C2">Chapter 2</h2>

  <p>This is chapter 2</p>

  <h2 id="C3">Chapter 3</h2>

  <p>This is chapter 3</p>

  <h2 id="C4">Chapter 4</h2>

  <p>This is chapter 4</p>

  <h2 id="C5">Chapter 5</h2>

  <p>This is chapter 5</p>

  <h2 id="C6">Chapter 6</h2>

  <p>This is chapter 6</p>

  <h2 id="C7">Chapter 7</h2>

  <p>This is chapter 7</p>

  <h2 id="C8">Chapter 8</h2>

  <p>This is chapter 8</p>

  <h2 id="C9">Chapter 9</h2>

  <p>This is chapter 9</p>

  <h2 id="C10">Chapter 10</h2>

  <p>This is chapter 10</p>

  <h2 id="C11">Chapter 11</h2>

  <p>This is chapter 11</p>

  <h2 id="C12">Chapter 12</h2>

  <p>This is chapter 12</p>

  <h2 id="C13">Chapter 13</h2>

  <p>This is chapter 13</p>

  <h2 id="C14">Chapter 14</h2>

  <p>This is chapter 14</p>

  <h2 id="C15">Chapter 15</h2>

  <p>This is chapter 15</p>

  <h2 id="C16">Chapter 16</h2>

  <p>This is chapter 16</p>

  <h2 id="C17">Chapter 17</h2>

  <p>This is chapter 17</p>

  <h2 id="C18">Chapter 18</h2>

  <p>This is chapter 18</p>

  <h2 id="C19">Chapter 19</h2>

  <p>This is chapter 19</p>

  <h2 id="C20">Chapter 20</h2>

  <p>This is chapter 20</p>

  <h2 id="C21">Chapter 21</h2>

  <p>This is chapter 21</p>

  <h2 id="C22">Chapter 22</h2>

  <p>This is chapter 22</p>

  <h2 id="C23">Chapter 23</h2>

  <p>This is chapter 23</p>

  <h2 id="C24">Chapter 24</h2>

  <p>This is chapter 24</p>

  <h2 id="C25">Chapter 25</h2>

  <p>This is chapter 25</p>

  <h2 id="C26">Chapter 26</h2>

  <p>This is chapter 26</p>

  <h2 id="C27">Chapter 27</h2>

  <p>This is chapter 27</p>

  <h2 id="C28">Chapter 28</h2>

  <p>This is chapter 28</p>

  <h2 id="C29">Chapter 29</h2>

  <p>This is chapter 29</p>

  <h2 id="C30">Chapter 30</h2>

  <p>This is chapter 30</p>
  
```


