# Gallery Components

## Dependencies
 * [Polymer (version 1.2 or later)](https://www.polymer-project.org/1.0/)
 * [Webcomponentsjs](https://github.com/webcomponents/webcomponentsjs)

## Attributes

### Container
 * delay: Timeout for gallery (miliseconds).
 * color: Color for text of Gallery (Ex: FF4081).

### Photo
 * src: Source of image
 * alt: Description of image

## How to use

```html
<gallery-container delay="2000" color="795548">
    <gallery-text>My favorite instrument is trumpet.</gallery-text>
    <gallery-photo
            src="http://medleyana.files.wordpress.com/2013/10/elysiantrumpetheroshotmedium.jpg"
            alt="Trumpet"></gallery-photo>
    <gallery-text>This is my favorite trumpets.</gallery-text>
    <gallery-photo
            src="http://www.bachbrass.com/images/products/trumpets/180S37.jpg"
            alt="Vincent Bach Stradivarius 180S37"></gallery-photo>
    <gallery-photo
            src="http://i.imgur.com/7OikZl.jpg"
            alt="Getzen 90 Deluxe"></gallery-photo>
</gallery-container>
```

## Author
 * Nam Hoai Vo <vhnam2504@gmail.com>

## License
 * Copyright 2016 - MIT