Simple keylogger written in C#. The goal is observing activity on the local machine (e.g. monitoring children using the machine).

This is specifically NOT a spying tool and won't have features for e-mailing logs, hiding from the OS and such.

Features:
  * Simple to use. Start and forget.
  * Tray icon so it's obvious when in use (main issue I had with [PyKeylogger](http://pykeylogger.wiki.sourceforge.net) is that it's unclear when it is running, and it still logs passwords in plaintext).
  * Logs activity in an easy-to-read format. Notes the application context, and keys pressed.
  * Control panel for easy change of settings.
  * Allows setting a password for accessing the control panel.

Future features:
  * Screenshots of mouse click areas (optional)
  * Logging when the program itself starts / shuts down / detecting when it is forcibly terminated (kill process in task manager).