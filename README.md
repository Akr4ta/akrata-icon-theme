# Akrata-icons
### Standard version
<img src="https://github.com/Akr4ta/akrata-icon-theme/blob/main/image_akrata.png" alt="e.g image">

### Anarchy version
<img src="https://github.com/Akr4ta/akrata-icon-theme/blob/main/image_akrata-anarchy.png" alt="e.g image">

### Second Anarchy version
<img src="https://github.com/Akr4ta/akrata-icon-theme/blob/main/image_akrata-anarchy-op2.png" alt="e.g image">

Icon theme that combines BeautyLine, Candy, Sweet, Tela and Breeze, harmonized with the Catppuccin Mocha color palette.
* BeautyLine for the majority of the icons,
* Candy to replace some app icons,
* Tela for symbolic icons,
* Sweet for the folders,
* Breeze for the cursor,
* Catppuccin Mocha as the color reference.

There are three versions: akrata (the standard), akrata-anarchy, and akrata-anarchy-op2. The only differences are: in the akrata-anarchy version, the menu/app grid icon is replaced by the anarchist "A" symbol, and in akrata-anarchy-op2, the cosmic launcher icon is replaced by the anarchist "A" symbol.

# Install
The icon theme is available in the AUR, so you can run the command below if you are using Arch Linux or an Arch-based system:

`yay -S akrata-icon-theme`

If you are using a different system, follow the instructions below.

Download the .zip file.

Extract the archive and move either the akrata, akrata-anarchy or akrata-anarchy-op2 folder to icons directory ~/.local/share/icons/ (Create this directory if it doesn't exist).

# Usage
Change via distribution specific tweak-tool.

# Don’t like the folder colors? Try this:
Note: This method only works if you install the theme manually by placing the theme file in ~/.local/share/icons/; it does not work when installing via AUR.

Extract the zip file in your Downloads folder.

When prompted for new_color, enter the HEX color code (e.g., #123456).

Run the following commands in the terminal:

`new_color=`

In other words, the terminal command should look like this: `new_color=#123456`

Finally, run:

`find $HOME/Downloads/akrata-icon-theme-main -type f -exec sed -i "s/#7287fd/"$new_color"/Ig" {} +`

Move either the akrata-icons or akrata-icons-anarchy folder to icons directory ~/.local/share/icons/

# Warning
This icon theme has only been tested on GNOME and COSMIC desktop environments. Other environments may display colors inconsistently.

This theme was designed to be used in dark themes.

This theme is still a work in progress, as we're currently adjusting the icon colors.
