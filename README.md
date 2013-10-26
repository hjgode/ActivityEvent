ActivityEvent
=============

Windows Mobile: How to use the ActivityEvent

I have a project like a screen saver one that watches keyboard presses and resets a timer. If there are no kepresses for a longer period, the other app will issue an alarm and enables the user to find the device.

Now the above one should be extended to reset the timer for screen activities too. As Windows Mobile only provides a keyboard hook and this hook will never catch screen taps, I had to look for an option to get screen activities too.

I found the ActivityEvent, which is used to reset the windows mobile power manager idle time.

The given ActivityEvent Visual Stido 2008 C SmartDevice project shows a first attempt on how to use the named event.

keywords: ActivityEvent, Windows Mobile, Screen, Touch, Input, Power Manager, GWE, SmartDevice
