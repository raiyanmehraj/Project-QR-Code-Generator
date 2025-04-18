# Project-QR-Code-Generator 
## Resources used to make this project-https://youtu.be/g1j9rR-H1lk?feature=shared
## Deploy link :https://scintillating-bombolone-b9f940.netlify.app/
What This Project Does:

This is a web app that lets you generate QR codes from any text or URL you type in. Just enter your input, click the button — it shows your QR code right on the screen. If you try to hit the button without typing anything, the input box will shake a bit to let you know something's missing.

#What I Used:

*HTML to build the basic structure of the page (input field, button, and image area).
*CSS to make everything look clean and add animations like shaking or expanding boxes.
*JavaScript to handle what happens when you click the button — and to connect with a free online QR code API.
*QR Code API from goqr.me to generate the actual QR images.


#How I Built It (Step-by-Step):

1.Started with HTML
I made a simple container with:
*An input field for the user to type in text or a URL
*A button to trigger the QR code generation
*A hidden image box that will show the QR code after it’s created

2.Styled it with CSS
I centered everything and gave it a clean, modern look. I also added:
*A smooth animation that reveals the QR code
*A "shake" effect on the input field if it's left empty

3.Wrote the JavaScript logic
I grabbed the HTML elements using their IDs (qrText, qrImage, and imgBox) and:
*Made a function that checks if input is given
*If yes: it builds a QR code using the API and displays it
*If no: it adds an animation to shake the input field

4.Tested it in the browser
*Open the HTML file, type something in the box, click the button, and it just works.


#Cool Features & Small Challenges:

*The QR code box only pops up when valid input is given, which keeps the UI clean.
*I added a shaking effect to help users realize they need to type something first.
*A tiny challenge was timing the animations and making sure the QR code shows up nicely without breaking the layout.







