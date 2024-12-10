Video Splitter

The Video Splitter app allows you to divide large video files into smaller parts by specifying the size of each part (in MB). It's easy to use and works with popular video formats like MP4, MOV, AVI, and MKV.

How to Use the App
Step 1: Open the App
Double-click the app to launch it.
Step 2: Select a Video
Click the "Browse" button to choose the video file you want to split.
Step 3: Enter the Desired Size
In the "Chunk Size (MB)" field, type the size of each smaller part you'd like (e.g., 50 for 50 MB).
Step 4: Choose an Output Folder
Click "Browse" next to "Output Folder" to select the folder where the split parts will be saved.
Step 5: Start Splitting
Click the "Start Splitting" button to begin.
A progress bar will show the status of the process.
Features
Split large video files into smaller parts.
Works with MP4, MOV, AVI, MKV, and more.
Keeps the original video quality.
Simple and user-friendly interface.
System Requirements
Operating System: Windows 10 or later.
FFmpeg Installed: The app requires FFmpeg for video processing. (If FFmpeg is missing, the app will guide you to set it up.)

How to Install FFmpeg
The Video Splitter app requires FFmpeg to work. FFmpeg is a free tool that processes video files. Follow these simple steps to install it:

Step 1: Download FFmpeg
Go to the official FFmpeg website: https://ffmpeg.org/download.html.
Under "Get packages & executable files", click the link for Windows.
Choose a version (we recommend the latest static build) and download the ZIP file.
Step 2: Extract the Files
Once the ZIP file is downloaded, right-click on it and select Extract All.
Choose a folder where you want to extract the files (e.g., C:\ffmpeg).
Step 3: Add FFmpeg to Your System Path
This step ensures the Video Splitter app can find FFmpeg.

Open the Start Menu and search for Environment Variables.
Click on "Edit the system environment variables".
In the new window, click the Environment Variables button at the bottom.
Under System Variables, find the Path variable and click Edit.
Click New, and add the path to the bin folder inside your FFmpeg directory (e.g., C:\ffmpeg\bin).
Click OK to save and close all windows.
Step 4: Verify the Installation
Open the Command Prompt:
Press Windows Key + R, type cmd, and press Enter.
Type the following command and press Enter:
ffmpeg -version
If installed correctly, you will see the FFmpeg version information.
Step 5: Open the App
Now that FFmpeg is installed, reopen the Video Splitter app, and it should work without any issues!

Frequently Asked Questions
1. What video formats are supported?
The app supports popular formats like MP4, MOV, AVI, MKV, and more.

2. Why is the app asking for FFmpeg?
FFmpeg is a tool required to process videos. If it's not already installed on your system, the app will guide you on how to set it up.

3. How do I fix a splitting error?
Ensure the video file is not corrupted.
Check that you have enough space in the output folder.
Ensure the video file isn't open in another app while splitting.
