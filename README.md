# Felbdogg.AI Chat

## Overview
This project is a chat interface designed for Felbdogg.AI, a chatbot application. The interface is built using HTML, CSS, and JavaScript with Bootstrap and Font Awesome for styling and UI components.

## Features
- **Responsive Design**: The interface is responsive and adapts to various screen sizes.
- **Dark Mode Toggle**: Users can switch between light and dark themes using the theme toggle button.
- **Session Management**: Users can create, rename, and delete chat sessions. Sessions are stored locally using `localStorage`.
- **File Upload**: Users can upload images to the chat interface, which are sent as base64 encoded strings.
- **Modal Window**: An "About Us" modal provides additional information about Felbdogg.AI.
- **Toast Notifications**: Toast notifications provide feedback to users, such as confirming actions like copying text to the clipboard.

## File Structure
- **index.html**: The main HTML file that contains the chat interface.
- **assets/**: A folder containing assets such as images, including the logo for Felbdogg.AI.

## External Libraries
- **Bootstrap**: Used for responsive design and UI components.
- **Font Awesome**: Provides icon support.
- **Marked.js**: Used for parsing and rendering markdown.

## How to Use
1. Open the `index.html` file in a web browser.
2. Interact with the chat interface by typing a message in the input box and clicking the send button.
3. Use the dropdown menu to manage chat sessions or toggle the theme.
4. Upload an image by clicking the upload button and selecting a file.
5. Click the "About Us" button to view information in the modal window.

## Local Storage
- Chat sessions are saved locally in the browser's `localStorage`.
- The session logs are automatically saved and can be loaded when switching between sessions.

## Future Enhancements
- **Improved Error Handling**: Enhance error handling for failed API requests.
- **Rich Text Support**: Allow users to send formatted text using markdown.
- **Session Export/Import**: Add functionality to export and import chat sessions.

## License
This project is under the [MIT License](https://opensource.org/licenses/MIT).
