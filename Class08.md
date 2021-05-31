# Layout in HTML

1. **Block-level boxes** start on a new line. Example: *h1*, *p*, *ul*, *li* 
You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.

2. **Inline elements** flow in between surrounding text Examples include:
*img* , *b*, *i* .

3. Browsers display pages in normal flow unless youspecify relative, absolute, or fixed positioning.

4. **Relative positioning** moves an element in relation to where it would have been in normal flow.

5. When the position property is given a value of **absolute**, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not
there.) The box offset properties (top or bottom and left or right) specify where the element should appear in relation to its containing element.

6. **Fixed positioning** is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place.

7. By default, most browsers add a margin to the top of the h1
element. This is why there is a gap between the top of the browser and the box containing the h1 element. If you wanted to remove this margin, you could add the following code to the h1 element's style rules: margin: 0px.

8. Designers keep pages within 960-1000 pixels wide.

9. Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.

10. **Resolution** refers to the number of dots a screen shows per inch.