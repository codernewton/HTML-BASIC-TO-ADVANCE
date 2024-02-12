#### Inline style

We can give style any HTML element with style attribute 

```
<tagname style="properties : value"
```

For example :

```HTML
<h1 style="color : red">This is RED color heading</h1>
<p style="color:white; background-color:blue"> This paragraph's color is white and background color is blue. </P>
```

output : 
<h1 style="color : red">This is RED color heading</h1>
<p style="color : white; background-color  :blue"> This paragraph's color is white and background color is blue. </P>

#### Internal Style

```HTML
<html lang="en">

<head>

<title>Document</title>

<style>

  h1 {

    color: red;

    border: 2px solid green;

  }

  p {

    background-color: yellow;

    font-size: 18px;

  }

</style>

</head>

<body>

  <h1>This is a heading</h1>

  <p>This is a paragraph and the main content </p>

</body>

```

Output :

  <h1 style="color: red; border: 2px solid green ">This is a heading</h1>

  <p style="background-color: yellow; color : black; font-size : 18px ">This is a paragraph and the main content </p>




