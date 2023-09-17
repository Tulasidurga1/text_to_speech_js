# text_to_speech_js
# Hosted Link:-https://tulasidurga1.github.io/text_to_speech_js/

#### Title: Speech Text Reader

- Description: This is a web application that allows users to input text and have it read aloud using speech synthesis. Additionally, users can click on images, each associated with specific text, to have that text read aloud as well.

### HTML Structure:

<!DOCTYPE html>: Specifies the document type and version of HTML.
<html lang="en">: Defines the root element of the HTML document with the language attribute set to English.
Head Section:

<head>: Contains metadata and links to external resources.
<meta charset="UTF-8">: Specifies the character encoding of the document.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>Speech Text Reader</title>: Sets the title of the webpage.
<link rel="stylesheet" href="Style.css">: Links an external stylesheet for styling.
-Body Section:

<body>: Contains the visible content of the webpage.
.container: A container for the entire content.
<h1>: Displays the title "Speech Text Reader."
#toggle-btn: A button to toggle the text input modal.
#myModal: A modal for entering text.
.modal-content: The content of the modal.
.close: A close button for the modal.
#text-input: A textarea for entering text.
#start-btn: A button to read the entered text.
#output: A container for displaying images and associated text.
CSS Styling:

Defines styles for various elements to control their appearance.
### JavaScript Functionality:

- JavaScript interacts with the HTML elements to provide functionality.
- Event listeners are used to detect user interactions.
- When the "Toggle Text Box" button is clicked, the modal for entering text is displayed.
- When the "Close" button in the modal is clicked, the modal is hidden.
- When the "Read Text" button is clicked, the text entered in the textarea is read aloud using the Web Speech API.
- Clicking on image containers triggers the reading of associated text.
- The synth object represents the speech synthesis API, and a boolean variable speaking is used to track if speech is currently in progress.
### Concepts and Features:

- Modal for entering text.
- Button to toggle the modal.
- Speech synthesis using the Web Speech API.
- Displaying images with associated text.
- Event handling to trigger speech synthesis.
### Styling:

The webpage is styled using CSS to create a visually appealing and user-friendly interface.
The color scheme, fonts, and spacing are defined in the CSS.
Script Files:

<script src="script.js"></script>: Links an external JavaScript file for handling interactivity and functionality.
Overall Purpose:

The webpage serves as a speech text reader tool, allowing users to input text and have it read aloud, or click on images to have associated text read aloud. It provides a user-friendly interface and leverages the Web Speech API for speech synthesis.
