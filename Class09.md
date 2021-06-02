# Forms in HTML

1. Forms allow users to perform other functions online. Example: when registering as a member of a website, when shopping online, and when signing up for newsletters.

### types of forms

Text input (single-line), Password input,Text area (multi-line), Radio buttons, Checkboxes, Drop-down boxes, Submit buttons, Image buttons, File upload.

### Structure

1. form element should always carry the action attribute and will usually have a method and id attribute too.
2. Every form element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
3. method: Forms can be sent using one of two methods: get or post.
4. type="text" When the type attribute has a value of text, it creates a singleline text input.
5. type="password" When the type attribute has a value of password it creates a text box that acts just like a single-line text input, except the characters are blocked out.
6. The textarea element is used to create a mutli-line text input. Unlike other input.
7. A drop down list box (also known as a select box) allows users to select one option from a drop down list. 
8. You can turn a drop down select box into a box that shows more than one option by adding the size attribute. I
9. type="file" creates a box that looks like a text input followed by a browse button. When the user clicks on the browse button, a window opens up that allows them to select a file from their computer to be uploaded to the website.
10. type="submit" The submit button is used to send a form to the server.
11. type="image" If you want to use an image for the submit button, you can give the type attribute a value of image.
12. You can group related form controls together inside the fieldset element. This is particularly helpful for longer forms.
13. The legend element can come directly after the opening fieldset tag and contains acaption which helps identify the purpose of that group of form controls.
14. list-style-image: You can specify an image to act as a bullet point using the list-style-image property
15. List markers can be given different appearances using the list-style-type and list-style imageproperties.Table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. 

# Events in JS

1. Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
2. Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
3. When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user. 
