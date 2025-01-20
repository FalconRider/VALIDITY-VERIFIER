This isn't about what it's about, that is an app that does a thing.
It's about the process of creating an app with Gen AI, specifically chatGTP.4

Instead of opening an IDE, like  in this case Visual studio Code, and typing away, testing editing over and over each character  that was mistyped to produce an error, or adding lines of code to add a tweak
this process involves writing "Prompts" tp the AI engine

That process is what I'm documenting here, so that I can remember how I did it or you can try it yourself.

1. You need an idea. You need a tool  for a purpose.

GOAL  Check validity  of an address or email

In this specific case: To keep from getting phished  and clicking a bogus link, a link where some of the characters appear to be normal but have been switched out - to similar looking characters.

2. You still need to know some old coder stuff.

BASIS of this App
Generally:
In the old days memory was tight  and there only 256 type characters in a character set called ASCII
Now there are thousands in character sets called Unicode, but the first 256 of any Unicode set are the old ASCII codes.  Each Character has a number. Other languages character sets are included after the old ASCII

ASSUMPTIONS:
This is for me, in Canada and all the addresses and emails I'm going to pursue are written in
the old Canadian alphabet, this app is useless to Russians using the Cyrillic alphabet as those characters would be  flagged out of range. ie over 256.

3 Process
An initial Prompt carefully worded cause you get what you ask for.  Notepad 
A returned bit of code, cut and paste into VSC, save in its own directory. As a HTML file.
A testing period, does it work, gaps tweaks
A second prompt requesting tweaks, use same chat session , don't have to repeat first part, Free
ChatGTP keeps stuff for 30 days, that resets if you pop in and add a  thanks to the tread
Repeat till happy. 
 
