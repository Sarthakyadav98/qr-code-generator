QR Code Generator
This is a Node.js project that allows you to generate QR codes from any text input. You can use this project to create QR codes for your personal or professional use cases, such as sharing information, promoting products, or facilitating payments.

Installation
To install this project, you will need to have Node.js and npm installed on your system. You can download and install them from the Node.js website.

Once you have Node.js and npm installed, you can clone this repository to your local machine using the following command:

git clone https://github.com/Sarthakyadav98qr-code-generator.git

Then, navigate to the project directory and install the dependencies using the following command:

npm install

Usage
To use this project, you can run the following command in the project directory:

node index.js

This will prompt you to enter the text that you want to encode in the QR code. You can enter any text, such as a URL, a message, or a JSON object. For example:

Enter the text to encode in QR code: https://www.bing.com

The project will then generate a QR code image file in the output folder, with the name qr-code.png. You can open this file to see the QR code. You can also scan the QR code with your smartphone or any QR code reader app to decode the text.

Alternatively, you can also pass the text as a command-line argument when running the project. For example:

node index.js https://www.bing.com

This will generate the QR code image file without prompting you for the text input.

Dependencies
This project uses the following npm packages:

qrcode: This is the main package that provides the functionality to generate QR codes from text inputs.
readline-sync: This is a package that enables synchronous user input from the command line.
License
This project is licensed under the MIT License. See the LICENSE file for more details.
