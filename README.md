# nautilus-copypaste-images

Provides a context menu entry in Nautilus (Gnome3 File Browser) to copy/paste the contents of an image file to and from the clipboard.

Fork of [nautilus-copypaste-images](https://github.com/atareao/nautilus-copypaste-images) with the following fixes:
 - Add saving jpeg and png file type
 - Improved file chooser
   - Closes correctly when cancelled
   - OK button changed to Save button
   - Opens in current folder instead of home

## Prerequisites
 - python-nautilus (`sudo apt install python-nautilus`)

## Installation (Ubuntu)
Make sure you have the *Prerequisites* installed first, then run:
```bash
sudo curl -L https://raw.githubusercontent.com/vijay-prema/nautilus-copypaste-images/master/src/nautilus-copypaste-images.py -o /usr/share/nautilus-python/extensions/nautilus-copypaste-images.py
nautilus -q
```
The above will also update the plugin to the latest version, if it's already installed.
