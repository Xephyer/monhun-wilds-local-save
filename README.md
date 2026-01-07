# monhun-wilds-local-save
A simple script for saving Monster Hunter Wilds save data locally.

Steps to set up:
1. Create a folder on your desired location (eg. C:\Users\YourName\Documents\MyFolder) and paste the bat file there.
2. Edit the bat file using Notepad (or any desired text editor)
3. On the last line (xcopy), inside the quotation marks ("C:/ Program Files/..."), paste here the path where your Monster Hunter Wilds save data is stored.
4. After the quotation marks (C:/Users/...) replace "C:\Users\YourName\Documents\MyFolder" with the location where you saved the bat file.
5. Run the bat file. It should create a folder with date and time and inside is a copy of your save data.

How it works (for nthose who don't know)
Line 1, Echo off, makes it so that the command line doesnt display the prompt. 
Line 2 - 9 is basically getting the time on your computer (year-month-date_hour-minute-second) and use it as a name for the creation of folder
Line 11-13 creates the folder using the time stamp and additional folder inside as it is the strucutre of the folder save data.
The last line basically copies the save data to the folder of your choosing.

I usually run this after closing wilds and steam finishes cloud syncing. It takes seconds to copy.

If you have any questions, please hesitate to ask.

Happy hunting!
