-----------------------------
INTRO
-----------------------------

The extensions framework lets you import Flash libraries (SWF) and use them  inside of your games. The most common use case is to import a sponsor's API into a Stencyl game.


-----------------------------
CONVERTING A SWC TO A SWF
-----------------------------

Stencyl only recognizes SWFs. If you have a SWC, follow these steps to extract the SWF from it.

1) Rename the SWC's extension to ZIP.
2) Unzip the file.
3) Inside will be the SWF.


-----------------------------
HOW TO MAKE A FLASH EXTENSION
-----------------------------

In short, follow what's done here.

1) Make a new folder under plaf/haxe/extensions/ - if it helps, just copy and paste this folder there.

2) Edit info.txt with the appropriate details.

3) Edit icon.png to your liking. (Optional)

4) Provide the SWF library and name it library.swf. If you want to import multiple libraries, you can provide as many as you'd like, but you need to edit include.nmml to refer to them.

5) Provide .hx source files, which can call functions directly from libraries. Alternatively, you can skip this step and call the Flash code directly from the game.

6) Enable the extension inside of Stencyl (Open game, click 'Settings', flip to the Extensions page and click Enable). Reopen the game and your extension will be ready for use.