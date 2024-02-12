## The HTML `<head>` Element

The `<head>` element is a container for metadata (data about data) and is placed between the `<html>` tag and the `<body>` tag.

HTML metadata is data about the HTML document. Metadata is not displayed. Metadata typically define the document title, character set, styles, scripts, and other meta information.

## The HTML `<title>` Element

The `<title>` element defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab. The `<title>` element is required in HTML documents!

Example :

```HTML
<html>  
<head>  
  <title>A Meaningful Page Title</title>  
</head>  
<body>  
  
The content of the document......  
  
</body>  
</html>
```

## The HTML `<style>` Element

In [[Style and CSS#Internal Style|Style and CSS]] section discuss about these element.
## The HTML `<link>` Element

The `<link>` element defines the relationship between the current document and an external resource.  The `<link>` tag is most often used to link to external style sheets:

```HTML
<link rel="stylesheet" href="mystyle.css">
```

## HTML Favicon

A favicon image is displayed to the left of the page title in the browser tab

```HTML
<link rel="icon" type="image/x-icon" href="/images/favicon.ico">
```


## The HTML `<meta>` Element

The `<meta>` element is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

The metadata will not be displayed on the page, but is used by browsers (how to display content or reload page), by search engines (keywords), and other web services.

## Examples

**Define the character set used:**

<meta charset="UTF-8">

**Define keywords for search engines:**

<meta name="keywords" content="HTML, CSS, JavaScript">

**Define a description of your web page:**

<meta name="description" content="Free Web tutorials">

**Define the author of a page:**

<meta name="author" content="John Doe">

**Refresh document every 30 seconds:**

<meta http-equiv="refresh" content="30">

**Setting the viewport to make your website look good on all devices:**

<meta name="viewport" content="width=device-width, initial-scale=1.0">

Example of `<meta>` tags:

```HTML
<meta charset="UTF-8">  
<meta name="description" content="Free Web tutorials">  
<meta name="keywords" content="HTML, CSS, JavaScript">  
<meta name="author" content="John Doe">
```

## Setting The Viewport

The viewport is the user's visible area of a web page. It varies with the device - it will be smaller on a mobile phone than on a computer screen.

You should include the following `<meta>` element in all your web pages:

```HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

This gives the browser instructions on how to control the page's dimensions and scaling.

The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.


## The HTML `<script>` Element

The `<script>` element is used to define client-side Java Scripts.

The following JavaScript writes "Hello JavaScript!" into an HTML element with id="demo":

```HTML
<script>  
function myFunction() {  
  document.getElementById("demo").innerHTML = "Hello JavaScript!";  
}  
</script>
```


### All head elements list

  
Here's a list of some common `<head>` elements used in HTML5:

1. `<title>`: Defines the title of the document.
2. `<meta>`: Provides metadata about the HTML document, such as character set, description, keywords, author, and viewport settings for responsive design.
3. `<link>`: Defines relationships between the current document and external resources like stylesheets or favicons.
4. `<style>`: Contains CSS rules for styling the document.
5. `<base>`: Specifies the base URL/target for all relative URLs in a document.
6. `<script>`: Defines client-side JavaScript within the document.
7. `<noscript>`: Provides fallback content for users who have disabled JavaScript in their browsers.
8. `<meta charset="">`: Specifies the character encoding for the document.
9. `<meta name="viewport" content="">`: Sets the viewport properties such as width, initial scale, and zooming options for mobile devices.

These are some of the key elements that you can typically find within the `<head>` section of an HTML document.

## Important meat elements list

In HTML5, the `<meta>` element is used to provide metadata about the HTML document. Here are some common attributes used with the `<meta>` element:

1. `charset`: Specifies the character encoding for the document.
2. `name`: Specifies the name of the metadata.
3. `content`: Specifies the value of the metadata.

Here are some examples of `<meta>` elements commonly used in HTML5:

1. Character Encoding:
```HTML
<meta charset="UTF-8">
```

1. Viewport Settings for Responsive Design:

```HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```
1. Description:

```HTML
<meta name="description" content="A brief description of the document">
```

4. Keywords:

```HTML
<meta name="keywords" content="keyword1, keyword2, keyword3">
```

5. Author:

```HTML
<meta name="author" content="Author Name">
```

6. Refresh Meta Tag:

```HTML
<meta http-equiv="refresh" content="30">
```

7. Application Name (for web applications):

```HTML
<meta name="application-name" content="Application Name">
```

8. Viewport settings for older Internet Explorer versions:

```HTML
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

These are just a few examples of how the `<meta>` element can be used in HTML5 to provide metadata about the document. There may be other custom metadata used depending on the requirements of the webpage or web application.