# take-a-sweet-break

# Description:

Widget (Plasmoid) designed to remind you to take a break from your computer. Modified with a cute cat icon to fit well with the colors of the 'Sweet' Plasma Theme.

![alt text](https://github.com/Nano-Ocelot/take-a-sweet-break/blob/master/face-yawn.svg?raw=true)

Shows an icon when it is time to take a break.

Original plasmoid; https://www.pling.com/p/998905


# Characteristics:

Non-intrusive; it doesn't show any dialog nor any buttons to be clicked. It just shows an icon in the panel when it is time to take a break.

Unattended; you don't have to do anything; everything is automatic. The widget detects when you are taking a break and when you come back.

Easy configuration; you only have to enter two values in the widget config, the 'work time' and the 'break time'.

And of course, it's easy to use.

To start, the widget shows a countdown with the minutes remaining to take a break.
When the countdown reaches zero, the cat is shown in the panel, with a red background. It means that it is time to take a break.
The tired face with the red background remains if you continue working.
If you are idle (not using mouse nor keyboard) for the configured 'break time' less one minute, the program considers that you are taking a break, and shows a yellow background behind the cat.
If you are idle for the configured 'break time', the program considers that you have completed the break, and shows a green background.
If you come back (use the mouse or keyboard) while showing the green background, the countdown will be shown and restarted.
If you come back while still showing the yellow background, the program considers that you haven't completed the break, so a red background will be shown again.

What if you took a short break, but you want to restart the countdown? No problem, you only have to click on the widget whenever you want to restart the countdown.

The widget works in horizontal panels, vertical panels, or on desktop.

Want to save space in the panel? Use the "hide&show" mode. To enable the "hide&show" mode, just ctrl+click on the widget. The widget will be hidden until countdown is over and the icon is shown, or if you want to see the countdown, you can mouse over the widget and it will be revealed for five seconds.

To disable the "hide&show" mode, just control+click on the widget again.

If you don't want the countdown to be shown when passing the mouse over the widget zone, then enable the "hide&show" mode by using "control+shift+click" instead of "control+click".

Alternatively you can configure the "hide&show" mode at "Advanced" preferences.


# Requirements:

KDE 5 (Plasma 5).


# Automatic Install:

Right click on a panel widget or desktop and choose 'Add Widgets'. Then choose 'Get new widgets' -> 'Download new Plasma widgets'.
Search for 'Take a Sweet Break', and click on 'Install'.

Then go back and add it to the panel or desktop from the 'Add Widgets' menu.


# Manual Install:

Download the file 'take-a-sweet-break.plasmoid' to some folder in your hard disk.
Right click on any panel or desktop and choose 'Add widgets'. Then click 'Install widget from local file'.
A file selection window will be shown. Then select the file you downloaded and hit enter.

Alternatively, run 'plasmapkg2 -i take-a-sweet-break.plasmoid' or to update 'plasmapkg2 -u take-a-sweet-break.plasmoid'.

Then go back and add it to the panel or desktop from the 'Add Widgets' menu.


# Uninstall:

Go to the 'Add Widgets' menu, find the widget in the list and click the remove button in the corner of it.


Alternatively run, plasmapkg2 --remove org.kde.contrib.takeabreak


# Licenses:

The license of this program is the GPLv3. See 'COPYING.GPLv3' file in the source code.

The tired icon (face-yawn.svg) is part of the 'Breeze icon theme', and its license is the LGPLv3. See 'COPYING.LGPLv3' file in the source code, and https://projects.kde.org/projects/kde/workspace/breeze
 
