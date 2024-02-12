The HTML `<img>` tag is used to embed an image in a web page.
The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.
The `<img>` tag has two required attributes:

- `src` - Specifies the path to the image
- `alt` - Specifies an alternate text for the image

Example :

```HTML
<img src="image source" alt="alternative text">
<img src="img.jpg" alt="default image">
```

## Image Size - Width and Height

We can use the `style` attribute to specify the width and height of an image.

```HTML
<img src="img.jpg" alt="default image" style="width:500px; height:300px;">
```

Alternatively, We can use the `width` and `height` attributes:

```HTML
<img src="img.jpg" alt="default image" width="500" height="200">
```

## HTML Image Maps

The HTML `<map>` tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more `<area>` tags.

```HTML
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">  
  
<map name="workmap">  
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">  
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">  
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">  
</map>
```

## The Areas

Then, add the clickable areas.

A clickable area is defined using an `<area>` element.

### Shape

You must define the shape of the clickable area, and you can choose one of these values:

- `rect` - defines a rectangular region
- `circle` - defines a circular region
- `poly` - defines a polygonal region
- `default` - defines the entire region

You must also define some coordinates to be able to place the clickable area onto the image.

## Summary

- Use the HTML `<map>` element to define an image map
- Use the HTML `<area>` element to define the clickable areas in the image map
- Use the HTML `usemap` attribute of the `<img>` element to point to an image map

## The `<picture>` Element

#### Example
Show different images for different screen sizes:

```HTML
<picture>  
  <source media="(min-width: 650px)" srcset="img_food.jpg">  
  <source media="(min-width: 465px)" srcset="img_car.jpg">  
  <img src="img_girl.jpg">  
</picture>
```

The browser will use the first image format it recognizes:

```HTML
<picture>  
  <source srcset="img_avatar.png">  
  <source srcset="img_girl.jpg">  
  <img src="img_beatles.gif" alt="Beatles" style="width:auto;">  
</picture>
```





