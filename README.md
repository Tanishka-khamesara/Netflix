# Netflix
https://tanishka-khamesara.github.io/Netflix/netflix.html
![netflix-1](https://github.com/Tanishka-khamesara/Netflix/assets/127411985/5708fda9-53c7-4e18-9164-6a4e5d48ba55)
![netflix-2](https://github.com/Tanishka-khamesara/Netflix/assets/127411985/4053de19-4e0b-41c8-8cb7-5c4f16bdf555)
![netflix-3](https://github.com/Tanishka-khamesara/Netflix/assets/127411985/f97082fb-d907-42b4-84ea-39b1656b4e64)
html explination ->
<body>: The <body> tag contains the main content of the webpage, which is visible to the user.

Inside the <body>, there is a <div> element with the id="shadow". This <div> appears to be a container for the entire content of the webpage.

Inside the #shadow <div>, there is another <div> with the id="heading". This seems to be the header section of the webpage.

Inside the #heading <div>, there are two child <div> elements. The first one has the id="image" and contains an <img> element displaying the Netflix logo.

The second child <div> with the id="buttons" contains two <button> elements: "Sign In" and "Register."

Below the #heading <div>, there is another <div> with the id="main". This section appears to be the main content area of the webpage.

Inside #main, there is an <h1> element with the text "Unlimited movies, TV shows and more." This is likely the main heading of the webpage.

Following the <h1>, there are two <p> elements with the id attributes "p1" and "p2." The first <p> has the text "Watch anywhere. Cancel anytime.," and the second <p> has the text "Ready to watch? Enter your email to create or restart your membership."

Overall, this HTML code sets up the basic structure of a webpage with a header containing the Netflix logo and buttons for signing in and registering, as well as a main content area with a heading and two paragraphs. The visual styles for this content will be defined in the "style.css" stylesheet.

css properties->
body: This selector targets the <body> element of the HTML document.

margin: 0;: It removes any default margin around the <body>, ensuring that the background image covers the entire viewport.

background: This sets the background of the <body> to an image using the url() function. The image is the Netflix sign-up page background.

#heading: This selector targets an element with the id="heading".

height: 20%;: It sets the height of the #heading element to 20% of its containing element, which is the #shadow element.

display: flex;: This turns the #heading element into a flex container, allowing its child elements to be aligned easily.

h1: This selector targets all <h1> elements in the document.

font-size: 55px;: It sets the font size of all <h1> elements to 55 pixels.

margin: 0;: It removes any default margin around <h1> elements.

#shadow: This selector targets an element with the id="shadow".

background: It sets the background of the #shadow element to a semi-transparent black color using RGBA values, creating a dark overlay effect.

height: 100vh;: It sets the height of the #shadow element to 100% of the viewport height (vh), ensuring that the background overlay covers the entire viewport.

#image: This selector targets an element with the id="image".

width: 40%;: It sets the width of the #image element to 40% of its containing element's width.

display: flex;: It turns the #image element into a flex container, allowing its child elements to be centered horizontally and vertically.

justify-content: center;: It horizontally centers the child elements within the #image element.

padding: 30px;: It adds 30 pixels of padding around the content of the #image element.

#buttons: This selector targets an element with the id="buttons".

padding: 30px;: It adds 30 pixels of padding around the content of the #buttons element.

width: 60%;: It sets the width of the #buttons element to 60% of its containing element's width.

text-align: right;: It aligns the text content within the #buttons element to the right.

#main: This selector targets an element with the id="main".

display: flex;: It turns the #main element into a flex container.

flex-direction: column;: It arranges the child elements within the #main element in a column layout.

justify-content: center;: It vertically centers the child elements within the #main element.

align-items: center;: It horizontally centers the child elements within the #main element.

color: white;: It sets the text color of the #main element to white.

height: 80%;: It sets the height of the #main element to 80% of its containing element's height.

#signin: This selector targets elements with the id="signin".

background: red;: It sets the background color of these elements to red.

padding: 8px 14px;: It adds 8 pixels of padding to the top and bottom and 14 pixels of padding to the left and right of these elements.

border: none;: It removes any border around these elements.

color: white;: It sets the text color of these elements to white.

font-size: 15px;: It sets the font size of these elements to 15 pixels.

border-radius: 5px;: It rounds the corners of these elements with a 5-pixel radius, giving them a slightly rounded appearance.

font-weight: bold;: It sets the font weight of these elements to bold.

p: This selector targets all <p> elements in the document.

margin: 13px;: It adds 13 pixels of margin around all <p> elements.

font-weight: 400;: It sets the font weight of all <p> elements to a normal weight.

#p1 and #p2: These selectors target elements with the id="p1" and id="p2", respectively.

font-size: 28px; and font-size: 23px;: These set the font sizes for the elements with the respective IDs.
These CSS properties and selectors define the styling for various elements in the HTML document, creating a visually appealing and responsive webpage layout for Netflix's sign-up page.

