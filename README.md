# phone-drop

The phone half of a small tool: scan a QR code shown by `phone_once.py` on a PC,
take a photo, and it lands on that PC's clipboard.

The page sends one shrunk photo to a random, single-use channel on the free relay
[ntfy.sh](https://ntfy.sh); the PC program downloads it and copies it to the clipboard.
The channel name travels in the link's `#` part and is never stored here.
