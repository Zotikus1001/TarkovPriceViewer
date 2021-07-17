# Tarkov Price Viewer v1.00
This program is for newbies. It is especially good to find out the market price in advance when the flea market is not open yet. Currently, only English is available.

Most of the information for this program (names, prices, wiki links, etc.) was provided by the Tarkov Market, and some information (Needs, etc.) was provided by the Tarkov Wiki.

# How to use
<img width="100%" src="https://user-images.githubusercontent.com/32073152/126034618-8d46c368-752a-40d8-8a64-47a5519c50c7.gif"/>
When the name appears as in the image, press the shortcut key (default: F9). By default, it disappears when you move the mouse, and this can be removed from the settings. It disappears even if you press the shortcut key (default: F10).

If you got errors, please check you installed .NET Framework 4.7.2 (https://dotnet.microsoft.com/download/dotnet-framework/net472).

# Notice - User
1. It cannot be used in full screen. Borderless windowed mode is recommended.
2. Since this information is fetched through parsing from the relevant sites, the information of this program will not be updated unless the information of the relevant sites is updated (especially, the information may be very different right after initialization).
3. The name may not be recognized or incorrect product information may be obtained. When checking information, you must make sure that the name part of the searched item matches.
4. I do not take any responsibility for any disadvantages or damages including the above. However, there is no danger of ban, so don't worry. Overwolf's minimap overlay is also not a reason for ban.

# Notice - Developer
1. I'm a newbie developer who just graduated from college who used to program mostly in Java programs So please understand that most of the code is not optimized for C#. If you tell us about any strange parts in the code or where it can be improved, we will try to fix it as much as possible.
2. Originally, I was going to make a program that recognizes the image of the product itself, but there were too many variables in the image, so I stopped development and changed the direction to recognizing the name. If anyone can implement it, I'll try to fix it.
3. Capture the game screen, find the name with OpenCV and text it with Tesseract. If there are other free OCR modules, please recommend them.

# Program (or site) used and license
1. OpenCV (https://opencv.org/license)
2. Tesseract (https://github.com/tesseract-ocr/tesseract/blob/master/LICENSE)
3. Tarkov Market (https://tarkov-market.com/)
4. Tarkov Wiki (https://escapefromtarkov.fandom.com/wiki/Escape_from_Tarkov_Wiki)
