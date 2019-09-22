# Yet Another Molokai Theme Color Scheme for Vim

Yet Another Molokai Theme, or yamt,  is a Vim port of the monokai theme for TextMate originally created by Wimer Hazenberg.

By default, it has a dark gray background based on the version created by Hamish Stuart Macpherson for the E editor.
And what is magic is that you have to change it manually if you want a light background ;), given that I didn't introduce 
other background than dark yet.

![Molokai Original](http://www.winterdom.com/weblog/content/binary/WindowsLiveWriter/MolokaiforVim_8602/molokai_original_small_3.png)

This theme only include 256-Color, so every terminal should be able to apply it.

## Installation

if you use pathogen as vim plugin manager (wich I recommend), you just have to clone the repository into .vim/bundle.

Otherwise if you have another plugin manager and you don't know how to add yamt theme, please read the documentation of your plugin
manager.

Eventually, if you have no plugin manager, just copy the file on your .vim/colors folder.
(if colors folder does not exist, create it and then copy the file).

Then add this line to your vimrc file : colorscheme yamt
