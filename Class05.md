#Images in HTML
To add an image into the page you need to use an img element. This is an empty element (which means there is no closing tag), . It carrys the following attributes:
1. src: This tells the browser where it can find the image file.
2. alt: This provides a text description of the image which describes the image if you cannot see it.
3. title: You can also use the title attribute with the img element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.

You should save images at the size you will be using
them on the web page and in the appropriate format

#Colors in HTML

1. The color property allows you to specify the color of text inside an element.
2. The color property allows you to specify the color of text inside an element.
3. There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
4. When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible. (otherwise people will not be able to read your content

#Texts in HTML
1. The font-family property allows you to specify the typeface that should be used for any text inside the element(s). 
2. The people who are visiting your site need the typeface you have specified installed on their computer in order for it to be displayed. You can specify a list of fonts separated by commas so that, if the user does not have your first choice of typeface installed, the browser can try to use an alternative font from the list.
body { font-family: Georgia, Times, serif;}
3. If a font name is made up of more than one word, it should be put in double quotes.
4. The font-size property enables you to specify a size for the font. uou can use px or percentage.
5. The default size of text in browsers is 16px. So a size of 75% would be the equivalent of 12px, and 200% would be 32px.
6. Setting font size in pixels is the best way to ensure that the type appears at the size you intended (because percentages and ems are more likely to vary if a user has changed the default size of text in their browser).
7. The default size of text in a web browser is 16 pixel.
8. @font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font which will be downloaded if it is not on the user's machine.
9. The font-weight property allows you to create bold text. it takes two values: bbold or normal.
10. If you want to create italic text, you can use the font-style property. There are three values this property can take: normal, italic, oblique.
11. The text-transform property is used to change the case of text giving it one of the following values:uppercase, lowercase, capitalize.
12. The text-decoration property allows you to specify the following values: none underline, overline, line-through, blink.


#JPEG VS PNG VS GIF

The three most commonly used image formats in websites and mobile applications are *JPEG, PNG and GIF.*

###JPEG
Use JPEG format for all images that contain a natural scene or photograph.
JPEG images don’t support transparency.

###PNG
Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos.
PNG images support transparency.

###GIF
GIF images are now mainly used only if the image contains animations.
PNG images support transparency.

###Compression

1. all forms of data that we see on the internet — text, image, video are compressed to reduce the size of data.

2. Compression can be of two types: **lossless and lossy.**

**lossless:** it is possible to reconstruct the original image from the compressed image. like: PNG, it is a great choice for images with text, logos and shapes with sharp edges.
GIF is also a lossless image but PNG compression is about 5–25% better than GIF compression.


**lossy:** it is not possible to reconstruct the original image from the compressed image because the data loss in lossy compression is irreversible. like: JPEG, JPEG images are best suited for photographs and paintings of natural scenes

