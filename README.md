# Portable Scrcpy by Diễn Nguyễn (CodonquaVN)

Welcome to Portable Scrcpy - a convenient solution to mirror and control your Android device from your Windows computer without complex installation.

## Simple Usage:

1.  **Download the Portable Scrcpy package:**
    *   Download the `.zip` or `.rar` file of the Portable Scrcpy package shared by Diễn Nguyễn (CodonquaVN).
    *   **Extraction Password: `codonqua`**
    *   Extract the downloaded file to any folder on your computer.

2.  **Folder Structure:**
    After extracting, you will see a folder structure similar to this:

    ```
    Portable Scrcpy/
    ├── adb/           (Contains necessary files for ADB)
    ├── scrcpy/        (Contains necessary files for scrcpy)
    ├── README.md      (This guide file)
    └── start_scrcpy.bat
    ```

3.  **Run the tool:**
    *   Open the extracted `Portable Scrcpy` folder.
    *   Right-click on the `start_scrcpy.bat` file.
    *   Select **"Run as administrator"**. (Running as administrator helps ensure ADB functions correctly.)

4.  **Option Menu:**
    A Command Prompt window will appear with the following options menu:

    ```
    ===================================
       Diễn Nguyễn (CodonquaVN)
    ===================================

    1. Connect via USB
    2. Connect via WiFi
    3. Show connected devices
    4. Exit

    Enter your choice (1-4): _
    ```

5.  **Select connection method:**
    Enter the number corresponding to your desired option and press Enter.

    *   **1. Connect via USB:** Connect your phone via a USB cable. Make sure you have **"USB Debugging"** enabled on your phone and accept the authorization prompt on your phone's screen if asked.
    *   **2. Connect via WiFi:** Connect your phone via WiFi. **For the first WiFi connection, you need to plug in the USB cable first and select option 1 to connect via USB once.** After that, select option 2, enter your phone's IP address (found in your phone's WiFi settings), and press Enter. You can disconnect the USB cable after a successful connection.
    *   **3. Show connected devices:** Display a list of connected Android devices recognized by ADB.
    *   **4. Exit:** Close the program and stop the ADB server.

## Handling Issues with Antivirus Software (Windows Defender)

Occasionally, Windows Defender or other antivirus software may incorrectly identify files like `adb.exe`, `scrcpy.exe`, or the `.bat` file as threats and block or delete them. To prevent this, you should add the folder containing the Portable Scrcpy package to your antivirus software's exclusion list.

**Steps to add to the exclusion list in Windows Defender:**

1.  Open **Windows Security** from the Start Menu or System Tray.
2.  Select **Virus & threat protection**.
3.  Under **Virus & threat protection settings**, click **Manage settings**.
4.  Scroll down to **Exclusions** and click **Add or remove exclusions**.
5.  Click **Add an exclusion** and select **Folder**.
6.  Browse and select the folder where you extracted the Portable Scrcpy package.
7.  Click **Select Folder**.

The folder containing the Portable Scrcpy package will now be ignored by Windows Defender. If you use different antivirus software, look for similar instructions to add a folder to the exclusion list.

## Important Notes

*   Ensure **"USB Debugging"** is enabled on your Android device.
*   This package includes the necessary files, you do not need to download ADB or Scrcpy separately.

## About Original Scrcpy

This Portable Scrcpy package is built upon the excellent open-source scrcpy project by Genymobile. Scrcpy is a free and open-source command-line application that allows displaying and controlling Android devices connected via USB or TCP/IP. You can learn more about the original project here: [https://github.com/Genymobile/scrcpy](https://github.com/Genymobile/scrcpy)

Enjoy using Portable Scrcpy by Diễn Nguyễn (CodonquaVN)! 
