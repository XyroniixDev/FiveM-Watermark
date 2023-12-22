# FiveM-Watermark



![Repository Banner](xyrowatermark.jpeg)



### XyroWatermark: Elevate your FiveM server with a customizable watermark! Effortlessly add a unique touch to your server screen by adjusting opacity, size, position, and even use GIFs. Easy installation for any server framework. Upgrade your server aesthetics now!

//

### **Thank you for using XyroWatermark.**

Welcome to the ultimate guide for installing and customizing XyroWatermark on your FiveM server. Follow these detailed steps for a hassle-free experience, even if you're new to server management.

### Step 1: Locate Your 'Resources' Folder

1. Open the directory where your FiveM server is installed.
2. Find and open the 'resources' folder. This is where we'll be placing the XyroWatermark script.

### Step 2: Add '[XyroWatermark]' Directory to 'Resources'

1. Download XyroWatermark.
2. Extract the downloaded file if needed.
3. Inside the extracted folder, locate '[XyroWatermark]'.
4. Drag the entire '[XyroWatermark]' directory into the 'resources' folder from Step 1.

### Step 3: Add an Image to the 'Media' Folder

1. Within the '[XyroWatermark]' directory, create a new folder called 'media'.
2. Choose a watermark image in PNG, JPEG, or GIF format.
3. Rename your image to 'watermark.png' (or 'watermark.jpeg' or 'watermark.gif' if using a different format).
4. Move the renamed image into the 'media' folder.

### Step 4: Customize the Script

1. Open the '[XyroWatermark]' directory.
2. Locate the 'watermark.lua' file and open it with a text editor (e.g., Notepad or VS Code).
3. Customize settings like opacity, size, position, and image path.
   - For example, to adjust opacity, find `opacity = 0.5` and replace `0.5` with your desired value (between 0.0 and 1.0).
   - To use a different image, find `image = 'media/watermark.png'` and replace 'watermark.png' with your image filename.

### Step 5: Ensure XyroWatermark in 'config.lua'

1. Navigate to your server files directory.
2. Find and open the 'config.lua' file.
3. Add the line `ensure '[XyroWatermark]'` at the end of the 'config.lua' file.
   - This ensures that XyroWatermark is loaded when your server starts.

### Conclusion:

You've successfully installed, customized, and ensured XyroWatermark for your FiveM server! Restart your server to activate the changes.

This tutorial caters to various server frameworks, including custom, QB, ESX, and ESX Legacy. For assistance or questions, reach out to the script's creator or the FiveM community.

Enjoy your unique watermark, and thank you for choosing XyroWatermark!
This tutorial is designed to be flexible for various server frameworks, including custom, QB, ESX, and ESX Legacy. If you encounter any issues or have questions, don't hesitate to seek support from the script's creator or the FiveM community.

Enjoy your unique watermark in your server, and thank you for choosing XyroWatermark!
