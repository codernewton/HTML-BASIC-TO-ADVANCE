An HTML iframe is used to display a web page within a web page.

## HTML Iframe Syntax

The HTML `<iframe>` tag specifies an inline frame. An inline frame is used to embed another document within the current HTML document.

### Syntax

```HTML
<iframe src="_url_" title="_description_"></iframe>
```

## Iframe - Set Height and Width

Use the `height` and `width` attributes to specify the size of the iframe. The height and width are specified in pixels by default:

### Example

```HTML

<iframe src="https://www.w3schools.com" height="200" width="300" title="Iframe Example"></iframe>
```

## Target Attributes

##### `name` attribute

```HTML
  
  <iframe name="my-frame" style="border: 2px solid green;width: 500;height: 300;">
  </iframe>
  <br>
  <a href="https://source.unsplash.com/random/500x300" target="my-frame">My Pic</a>
```


##### `self,blank,parent,top` attribute

###### Top Page

```HTML
<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Top page</title>

</head>

<body>

  <h1 style="text-align: center; background: blue; color: #fff;">

  TOP PAGE</h1>

  <iframe src="./parents-page.html" style="border: 2px solid green; width: 500px; height: 300px;" >

  </iframe>

</body>

</html>
```

###### Parent page

```HTML
<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Document</title>

</head>

<body>

<h2 style="text-align: center; background: green; color: #fff;">PARENT PAGE</h2>

<iframe src="./child-page.html" style="border: 2px solid green; width: 450px; height: 200px;">

</iframe>

</body>

</html>
```

###### Child Page

```HTML
<html lang="en">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Document</title>

  <style>

    a {

      text-decoration: none;

      color: white;

      background: green;

      padding: 5;

      line-height: 2;

      border: 2px solid black;

    }

  </style>

</head>

<body>

  <h2 style="text-align: center; background: red; color: #fff;"

  >CHILD PAGE</h2>

  <a href="https://source.unsplash.com/random/400x200" target="_self">Self</a> <br>

  <a href="https://source.unsplash.com/random/400x300" target="_blank">Blank</a> <br>

  <a href="https://source.unsplash.com/random/300x200" target="_parent">Parent</a> <br>

  <a href="https://source.unsplash.com/random/300x200" target="_top">Top</a> <br>

</body>

</html>
```

