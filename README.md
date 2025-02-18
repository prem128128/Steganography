# Data Hider - Hide Secret Text in Images

## Overview
This is a simple steganography tool that allows users to hide and retrieve secret messages within image files using the **Least Significant Bit (LSB)** method. It is built with Python, **Tkinter** for the GUI, and **stegano** for image steganography.

## Features
- Load and display images.
- Hide text messages inside images.
- Retrieve hidden messages from images.
- Save the modified image with hidden data.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install pillow stegano
```

## How to Use

1. **Run the Application**
   ```bash
   python main.py
   ```

2. **Open an Image**
   - Click "Open Image" and select an image file (PNG or JPG).
   
3. **Hide a Message**
   - Enter a secret message in the text box.
   - Click "Hide Data" to embed the message into the image.
   - Save the modified image using "Save Image".

4. **Reveal a Message**
   - Open an image with hidden text.
   - Click "Show Data" to retrieve the message.

## File Structure
```
├── main.py        # Main application script
├── logo.png       # Application logo
├── README.md      # Project documentation
└── requirements.txt # Dependency list
```

## License
This project is open-source and licensed under the MIT License.

## Contribution
Feel free to submit issues or pull requests to improve this tool!

## Author
[Prem Nayak]
[Phanindra Singarapu]


