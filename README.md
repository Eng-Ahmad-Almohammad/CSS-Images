# CSS-Images
## Controlling sizes of images in CSS
### You can control the size of an image using the width and height properties in CSS, just like you can for any other box. 

![image size](https://user-images.githubusercontent.com/70091044/93627461-ab04b800-f9ed-11ea-868c-3789d50f988d.PNG)

## Centering images Using Css
### By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it should be turned into a blocklevel element using the display property with a value of block. Once it has been made into a block-level element, there are two common ways in which you can horizontally center an image:

* On the containing element,
you can use the text-align
property with a value of center.

* On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.
![center image](https://user-images.githubusercontent.com/70091044/93628273-f5d2ff80-f9ee-11ea-87f7-29e6acf200b6.PNG)


## Background Images (backgroung-image)
### The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box
![backgroung image](https://user-images.githubusercontent.com/70091044/93628506-56623c80-f9ef-11ea-8f6a-3e6ddd864456.PNG)

## Repeating Images (background-repeat, background-attachment)

### The background-repeat property can have four values:

* repeat: The background image is repeated both horizontally and vertically (the default way itis shown if the backgroundrepeat property isn't used).

* repeat-x: The image is repeated horizontally only (as shown in the first example on the left).

* repeat-y: The image is repeated vertically only.

* no-repeat: The image is only shown once.

### The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:

* fixed The background image stays in the same position on the page.

* scroll The background image moves up and down as the user scrolls up and down the page.

## Background Position (background-position)
### When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed. This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.

* left top

* left center

* left bottom

* center top

* center center

* center bottom

* right top

* right center

* right bottom

