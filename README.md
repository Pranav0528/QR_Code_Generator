# QR_Code_Generator
This index.js script serves as a convenient QR code generator, allowing users to input a URL and then generating a corresponding QR code image. 
The script utilizes the Inquirer library for an interactive command-line experience, enabling users to provide the URL seamlessly.

## Installation
Before running the script, ensure you have Node.js installed on your system. You can install the required dependencies by executing the following command in your terminal:
npm install

## Usage
To run the script, use the following command:
node index.js
or if you have nodemon installed:
nodemon index.js

The script will prompt you to enter a URL. Once you provide the URL, it will generate a QR code representing that URL. 
The generated QR code will be saved as an image file named qr_img.png. Additionally, the provided URL will be saved in a text file named url.txt.

## Dependencies
### Inquirer: 
  This library facilitates an interactive command-line interface, making it user-friendly.

### qr-image:
  Used for generating QR codes based on the provided URL.

### fs: 
  A built-in Node.js module for handling file system operations, utilized here to write the QR code image and the URL to files.


  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If the prompt encounters issues rendering in your current environment, the script will catch and handle TTY errors.
In case of other errors during script execution, appropriate error handling is in place to provide meaningful feedback.
Feel free to customize this script according to your project needs. It provides a straightforward and efficient way to generate QR codes with minimal effort. Enjoy effortlessly creating QR codes for your URLs!
