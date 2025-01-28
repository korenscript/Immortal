# Immortal (My First Batch Project)
Batch script which was created for educational and entertaiment purposes only. The script provides interesting tricks with modern Windows (particularly Windows 8.1 and newer), but is also capable of damaging files, registry data ect.

## This was a challenge!

Yes, it really was. One day I asked my self "Wouldn't be a crazy idea to create interesting and destructive batch script with user interface?".
And just with that, I started learning the batch script.

## What's the purpose?

A lot of people in our community view batch script as a "scripting language for skidders". This might be true due to the fact how easy is to code in the batch script. However, I am not a script kiddie anymore and I want to prove you that even with the batch script you can do pretty amazing stuff in the Windows.
So what's the purpose of this? Just to show you what batch script can be capable of!

## My opinion on Batch Script

Well, I have to say that learning this script did not take long becuase batch is very low level scripting language. However, I ran into a lot of problems with syntax, spacing issues and escaping. So, it was not clean process as I thought it will be.
For instance: When I was trying to escape keyword "do" inside if statement it did not let me do that. No metter how hard you try to escape "do" keyword inside if statement or for loop, you will always fail.
Would I recommend batch script to you? Yes, but be prepared for a lot of errors and stay calm (not like me :D) because there is always reason why the problem occured.

## How this script works?

When you launch Immortal.bat, the first thing that you are going to experience is UAC promt. That is because this script need a administrator privileges to change and remove important files. Without these rights, the script would not do much. Then the script will show you the main menu with all stages (in other words levels) which you can try. Meanwhile, the script already dropped some of its files in "C:\Immortal" directory and it created bunch of registry files in "HKEY_LOCAL_MACHINE\SOFTWARE\Immortal". These files are very important for the script functionality. Also, it chnage the registry value "Shell" in order to start up along with explorer.exe.

### Levels

### Casual 😇
The harmless level.
It hide files, randomly launch applications, open random websites and lastly it restart the system via shutdown command.
The console window is visible.

### Normal 😊
It is a still harmless level, but some of its features can cause problems to users who does not understand basic stuff in registry and basically anyone who lacks basic knowledge in Windows.
Fist it disable Task Manager then Registry Editor, it will also disable UAC protection. Lastly it remove the wallpaper and write a message to the user.
The console window is visible.

### Annoying 😐
This level can do mess in the system. However, it does not do any kind of damage so it is still classified as a harmless level.
After execution it change a lot of file icons, rename username, create welcome message, swap the mouse inputs and it disable the Task Manager, Registry Editor and UAC protection. Pressing any key will lead to reboot.

**1st Payload**
After reboot, the Annoying Level will activate first payload.
In this payload, the script will try to create a gibberish files on all drives and its subdirectories.

**2nd Payload** (not shown in the video)
When this payload is launched, random gibberish message boxes will be displayed. Styles and buttons of the message boxes can appear randomly.

**3rd Payload**
This payload is about downloading files from hardcoded download links. When the file is downloaded, it will try to open it.
All the files will be stored inside "C:\Download" directory.

**4th Payload**
It will launch two scripts "spam.bat" and "letmeransomeaps.bat". This payload will slowdown the system because it will attempt to launch all files from system32 directory. "spam.bat" only display command "dir C:\ /s" with different variations of colors.

When you try to reboot the system again, you will return to the main menu.

The console window is visible, but it will change after reboot.

### Harsh 🙁



### Cruel 😡

### Deadly 😈
