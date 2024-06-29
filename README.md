# Image to Text OCR with Express

Hey! This project showcases an Image to Text OCR (Optical Character Recognition) application using Tesseraact.js. It allows users to upload an image file, which is then processed using Tesseract.js to extract text from the image.

## Technologies Used

### Development Tools
- **VSCode**: Used as the primary IDE for coding.
- **Git**: Version control system used to track changes in the project and collaborate with others... Well it was only me this time around.
- **NPM**: Package manager for JavaScript used to install and manage project dependencies.
- **NVM**: Node Version Manager used to manage multiple active Node.js versions.

### Dependencies
- **Tesseract.js**: The meat of this project; OCR (Optical Character Recognition) engine used for converting images to text.
- **Express**: Web framework for Node.js used to create the local server and handle HTTP requests.

### Languages
- **HTML/CSS/JavaScript**: Frontend technologies used to create the user interface and handle client-side logic.

## How It Works

1. **File Upload**: Users select an image file using the upload form.
2. **Server-side Processing**: Express.js handles the file upload and serves the HTML interface.
3. **OCR Processing**: Tesseract.js is employed to recognize text from the uploaded image.
4. **Display Results**: The recognized text is displayed on the webpage in ~realtime.

## Setup Instructions

1. **Clone Repository**: Clone this repository to your local machine.
   ```bash
   git clone https://github.com/8omz/Img-to-Text-OCR.git
   ```

2. **Install Dependencies**: Install necessary dependencies using npm.
   ```bash
   npm install
   ```

3. **Start the Server**: Start the Express server.
   ```bash
   npm start
   ```

4. **Open in Browser**: Open your browser and navigate to `http://localhost:3000` to use the application.

## Future Enhancements

- Improve OCR accuracy and speed.
- Enhance user interface for better user experience.
- Add support for multiple languages and fonts.
- Planned feature to push OCR results directly to a Discord bot, enabling real-time dissemination of OCR data into designated channels.

## Additional Notes

- This project is a demonstration of integrating OCR capabilities into a web application using modern JavaScript technologies.
- Feel free to explore and modify the code according to your needs.
