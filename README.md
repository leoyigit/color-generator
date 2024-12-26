Leo's Color Palette Extractor

Leo's Color Palette Extractor is a simple and interactive web application that allows users to upload images, extract prominent colors from them, and display those colors in different formats (RGB, HEX, CMYK). The extracted colors can also be copied to the clipboard for easy use.

Features

Drag-and-Drop Image Upload: Easily upload images by dragging and dropping them into the interface.

Multiple Color Formats: Display extracted colors in RGB, HEX, or CMYK format.

Clipboard Copy: Copy color values to the clipboard with a single click.

Responsive Design: Fully responsive interface that works on desktop and mobile devices.

K-Means Clustering: Efficient algorithm to extract a set number of dominant colors from the uploaded image.

User Notifications: Visual feedback when colors are copied to the clipboard.

Demo



Installation

Clone the repository:

git clone https://github.com/leoyigit/color-generator.git

Navigate to the project directory:

cd color-generator

Open the color-palette.html file in your browser to use the application.

Usage

Drag and drop an image onto the upload section or click to upload an image from your device.

Select the desired color format (RGB, HEX, or CMYK) by clicking the respective button.

Click "Extract Colors" to display the dominant colors of the image.

Hover over a color to see its value. Click on the color to copy its value to the clipboard.

A notification will appear at the top center of the screen when a color is successfully copied.

Technologies Used

HTML5: Structure of the application.

CSS3: Styling and responsive design.

JavaScript: Interactive functionality, including image processing and K-Means clustering.

File Structure

color-palette-extractor/
|-- index.html       # Main HTML file
|-- style.css        # Styling file
|-- script.js        # JavaScript functionality
|-- assets/          # Directory for images and other assets

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix:

git checkout -b feature-name

Commit your changes:

git commit -m "Add new feature"

Push to your branch:

git push origin feature-name

Submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Inspired by the need for a simple color palette extraction tool.

Thanks to all contributors and users for their support.

Contact

For any inquiries, feel free to reach out at ygtekz@gmail.com.
