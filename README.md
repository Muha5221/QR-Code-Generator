
# QR-Code-Generator
QR Code Generator
A simple Node.js application that generates QR codes from URLs and saves them as images along with the original URL in a text file.

Features
- Prompts user for a URL input using [Inquirer](https://www.npmjs.com/package/inquirer)
- Converts the URL into a QR code using [qr-image](https://www.npmjs.com/package/qr-image)
- Saves the QR code as a `.png` file
- Stores the URL in a `.txt` file

## 🚀 Getting Started

### Prerequisites

Make sure you have Node.js installed.

To check, run:

node -v inquirer
Installation
Clone the repository:
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator

Install the dependencies:
npm install inquirer qr-image


📂 Project Structure
qr-code-generator/

├── index.js

├── package.json

├── qr_img.png      # (will be created after running the app)

└── URL.txt         # (will be created after running the app)

🛠️ Usage
Run the application:
node index.js
You’ll be prompted to enter a URL. Once submitted:

A QR code will be saved as qr_img.png

The URL will be saved in URL.txt

📸 Example
Type in your URL: https://example.com
The file has been saved!

📄 License
This project is licensed under the MIT License.


Let me know if you’d like to add badges, author info, or make it more beginner-friendly!
