# CitrixCopyPasta
Just two little scripts if you would like to have text copy/paste like functionality for Citrix connecting from MacOS. Just text.

ocrclipboard: "copy from inside Citrix", allows to chose a screen area that is then OCR'ed and the text put into the clipboard. Obviously you know that OCR can make mistakes, so take care.

typeclipboard: "paste into Citrix", takes whatever is in the clipboard and mimics keyboard presses that go to wherever the current focus is on (hopefully inside Citrix). Obviously you know that type speed and Citrix are enemies so there can be mistakes, so take care. My osascript invocation is just nicely slow enough so that the typing speed is right, but your mileage may vary.

Always invoke these scripts with Spotlight search (Command + Space), that makes it efficient.

WARNING: You will shoot yourself in the foot once at least. Read. Think. Understand. And test with short texts first.

I think this is one of the really ridiculous things that might break, but are nevertheless super useful.
