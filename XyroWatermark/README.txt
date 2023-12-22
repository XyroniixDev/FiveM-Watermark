1. **Download and Install:**
   - Download the "XyroWatermark" script.
   - Place the script in the resources folder of your FiveM server.

2. **Restart Your Server:**
   - Restart your FiveM server to load the new script.

3. **In-Game Usage:**
   - In the game, players can use the "/setwatermark" command to customize the watermark.
   - Examples:
     - `/setwatermark opacity 0.7` (Sets opacity to 0.7)
     - `/setwatermark size 150,75` (Sets the size to a width of 150 and height of 75)
     - `/setwatermark position 0.8,0.02` (Sets the position to x=0.8 and y=0.02)

4. **Default Settings:**
   - The script has default settings for opacity, size, and position.
   - Opacity: 0.5
   - Size: Width = 100, Height = 50
   - Position: X = 0.85, Y = 0.01

5. **Events:**
   - The script triggers the "updateWatermarkSettings" event when a player spawns or when the "/setwatermark" command is used.
   - This event updates the watermark settings for all players.

6. **Customization:**
   - You can customize the default settings in the script file (`watermark.lua`) if needed.
   - Rename the script file if you want to change the script's name.

7. **Feedback and Support:**
   - If you encounter any issues or have questions, refer to the script documentation or seek support from the script's creator.

8. **Enjoy the XyroWatermark:**
   - Players will now see the XyroWatermark at the top right corner of the screen with the specified customization.

Remember to communicate any specific instructions or commands to your server's players, so they can make use of the watermark customization features.