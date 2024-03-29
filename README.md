﻿<div align="center">

## cTextBox \(Customized Textbox\)

<img src="PIC20012161024521535.jpg">
</div>

### Description

This all started when I noticed that I was constantly adding in code for when a textbox got focus, lost focus, etc. I decided that this would be a great chance to try my hand at making my own control. Fortunately, I spared PSC users the pain of some of the early versions of the control. I'm pretty happy with the latest version, so let me know what you think (and if you like it, vote for me! :-). Oh, I guess I should mention what it can do. It has several customized properties, such as "AutoSelect," which when True causes the text to be automatically selected when the box receives focus. Then there's "AutoUpperCase," which makes all entered text to be in upper case as it is typed. Then you've got "BackColor_Normal" and "BackColor_OnGotFocus." That's right, you can have it change to a different color when it receives focus (great for highlighting the current textbox when a user has a lot of fields to fill in). There's also "DefaultText" and "UseDefaultText." These are for having the text in the textbox revert to the default text after escape is pressed twice (the first esc is like an undo when you've started typing over something in the box). The latest feature is "TextType," which causes the textbox to only accept certain keystrokes, depending upon the property value. For example, there's AlphaNumeric, which allows everything, and then there's one for allowing only positive integers, and one for negative integers, pos/neg reals, alpha only, etc. This isn't like normal validation which checks the text after it's entered. This checks each keystroke and throws out the ones that aren't to be accepted. To run the tester .exe you'll need to register the cTextBox.ocx, or you can open the cTextbox.vbg file and run it from there. Let me know if you have any comments/suggestions/bug reports. Thanks! (and don't forget to vote :-) Oh! I just remembered, there's another property (two actually), "EntryTimerEnabled" and "MaxEntryTime." These are used to keep track of how much time it takes for a user to enter text in the textbox. If the maxentrytime is exceeded then the "EntryTimedOut" event is fired. This was added because my company often wants users to login to shop floor systems by scanning there badge ID and we needed to prevent the user from typing in an ID. Since barcode readers (or whatever type of scan device you use) are generally faster at generating characters than most typists, you can prevent typing in an ID by experimenting with the MaxEntryTime value.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |2001-02-16 10:04:12
**By**             |[Gator](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/gator.md)
**Level**          |Advanced
**User Rating**    |4.4 (75 globes from 17 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[CODE\_UPLOAD150542162001\.zip](https://github.com/Planet-Source-Code/gator-ctextbox-customized-textbox__1-21062/archive/master.zip)








