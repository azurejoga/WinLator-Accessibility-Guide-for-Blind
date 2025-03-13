# WinLator Accessibility Guide for Blind  
A guide that allows blind and visually impaired people to use Winlator with NVDA and play PC games on Android.  

## Using Winlator with Accessibility for Blind and Visually Impaired    

### Credits  
[Guiador, in Audiogames Forum!](https://forum.audiogames.net/post/898032/#p898032)  

**Winlator** is an emulator designed to run Windows applications on Android devices. However, its accessibility is not native, requiring adjustments to allow blind or visually impaired people to use it efficiently. Below, the steps to configure the emulator and make it accessible are described.  

## 1. Initial Configuration  
Before creating a container, you need to configure multiple elements to ensure accessibility. Below are the essential adjustments:  

- **TalkBack is not compatible**, so it must be deactivated.  
- **Jieshuo**, along with its virtual screen, can be used for OCR in some situations.  
- A **physical keyboard, gamepad, or similar device** is required to map the main keys.  
- The version of **NVDA** to be used depends on the emulated operating system:  
  - **Windows XP** → Version 2017.  
  - **Windows 7** (default on the emulator) → Version 2023.  
  - **Windows 10 or 11** → Latest version available.  

## 2. Creation of the Container  
To create a new container in Winlator, follow these steps:  

1. Press the **"Add"** button and follow the assistant.  
2. Explore the different tabs and select the desired configuration:  
   - **Screen**  
   - **Audio**  
   - **Source**  
   - **Background Plan**  
   - **Version of Drivers and Operating System**  
3. If any term is unknown, it is recommended to research forums or consult an AI.  
4. At the end, press the **"Confirm"** button.  

## 3. Accessibility in the Emulator  
The emulator **does not have native accessibility** and does not include an integrated screen reader. Additionally, it allows startup in different loading modes (only essential services or all services).  

## 4. Additional Configuration in Jieshuo  
Some settings within **Jieshuo** need to be adjusted to improve emulator interaction:  

1. Access the **Stock Settings** option.  
2. Go to **Settings of Predefined Gestures**.  
3. Select **Border Gestures**.  
4. Activate the **"Lower Border"** gestures option.  
5. Swipe left and right on the edge of the screen to test.  

## 5. Accessing Files Within the Emulator  
Each container created has two main buttons:  

- **Run the Emulator**  
- **Access Useful Shortcuts**  

To install NVDA inside the emulator:  

1. Access the second button and find the file explorer option.  
2. The NVDA installer should be **previously downloaded** on mobile or moved to the download folder.  
3. Within the emulator, the **D:** drive corresponds to the download folder.  
4. Open the explorer and locate three main buttons:  
   - **View** (to explore subfolders).  
   - **Run** (to execute files).  
   - **Menu**.  
5. Find the NVDA installer and press **"Run"** to start the installation.  

## 6. Keyboard Configuration in the Emulator  
When running the NVDA installer, the **keyboard will not yet be functional**, as the emulator uses a touch-controlled cursor. To activate it:  

1. Use the **Back Gesture** (previously activated in Jieshuo) to open a submenu.  
2. Select **Input Controls**.  
3. Choose a predefined **profile**, such as **RTS**.  
4. Access the **Configuration Option within the Profile**.  
5. In the **Detected Keyboard Options**, press each physical key and assign a function.  
6. It is recommended to **temporarily disable Jieshuo** to avoid interference with keys such as arrows, tab, space bar, and enter.  
7. After each assignment, a screen will be displayed to define if the key belongs to a keyboard, controller, or other device.  
8. At the end, press **OK** or **Confirm**.  

## 7. Interaction with NVDA in the Emulator  
After the keyboard configuration, it will be possible to interact with **NVDA** both during the installation and in the emulated system.  

### Final Recommendations  

- **Disable Jieshuo** while using the emulator to avoid conflicts.  
- The **"Game Mode" of Jieshuo** is not sufficient, as it can still interfere with some parts of the emulator.  

With these settings, it is possible to use Winlator with accessibility, ensuring greater independence for blind and visually impaired users. Although some areas still need improvements, this method allows for a more functional experience within the emulator.  
  
