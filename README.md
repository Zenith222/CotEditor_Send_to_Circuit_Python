# CotEditor_Send_to_Circuit_Python
An AppleScript designed to be used with CotEditor, or customized to other code editors, that utilizes pbpaste to write CircuitPython files.

Setup is as easy as can be. Take this script and put it in the CotEditor scripts folder found in the scripts menu bar section. A keyboard shortcut can be utilized. Find those options in the manual of CotEditor under the help menu bar option, searching for "File naming rules for CotEditor scripts".

This dumps the contents of the focused document into the clipboard and then uses pbpaste shell command to write to the py file. This makes an instant write and works well for Circuit Python. 
