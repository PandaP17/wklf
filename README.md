# wklf
A Windows password stealer using USB and LaZagne.
--------------------------------------------------------------------
HOW TO SET UP

1. Download the ZIP file of the repository and extract it to your computer.
2. Plug in your USB.
3. Drag the contents of the wklf folder into the USB.
4. Eject the flash drive (if you wish).
--------------------------------------------------------------------
HOW TO USE

1. Plug into target(s) computer.
2. Double-click the "run.bat" file.
3. Wait.
4. Once the terminal window closes, either pull out the USB or eject it, then pull it out. (Safer to eject).
5. Go into the "Storage" folder and double click on the "passwords.txt" file. In there you should see the stored passwords that LaZagne was able to retrieve.
6. **_THE "PASSWORDS.TXT" FILE WILL BE REPLACED WITH NEW PASSWORDS THE NEXT TIME YOU USE THE "RUN.BAT" FILE, SO COPY IT SOMEWHERE SAFE._**
--------------------------------------------------------------------
COMMON QUESTIONS

Q. Does this work on all Windows systems?
A. Most new ones yes - I'd say XP and beyond. Possibly 98 and 95 but I doubt your target will be running that.

Q. Does this work on both 32 and 64 bit?
A. Yes. 

Q. Did you fully create everything here?
A. **NO!** I don't want to be getting in any trouble for people assuming that I claim that I own LaZagne - AlessandroZ does. I only created a way for this to be portable and USB-Compatible.
--------------------------------------------------------------------
COMMON ERRORS

If the "passwords.txt" file isn't replaced and still has the sample text, you may have to change the directory of the USB drive, however, it should be E: no matter what. To change the directory, simply open the "run.bat" file in any text editor and change the **E:**\Storage\passwords.txt to whatever your directory is (e.g D:\Storage\passwords.txt)
