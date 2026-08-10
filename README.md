# Akrata-icons
<img src="https://github.com/Akr4ta/akrata-icon-theme/blob/main/ex_image.png" alt="e.g image">

Icon theme that combines BeautyLine, Sweet, Tela and Candy, harmonized with the Catppuccin Mocha color palette.
* BeautyLine for the majority of the icons,
* Tela for symbolic icons,
* Candy to replace some app icons,
* Sweet for the cursor and folder themes,
* Catppuccin Mocha as the color reference.

There are three versions: akrata (the standard), akrata-anarchy, and akrata-anarchy-op2. The only differences are: in the akrata-anarchy version, the menu/app grid icon is replaced by the anarchist "A" symbol, and in akrata-anarchy-op2, the cosmic launcher icon is replaced by the anarchist "A" symbol.

# Install
Download the .zip file.

Extract the archive and move either the akrata, akrata-anarchy or akrata-anarchy-op2 folder to icons directory ~/.local/share/icons/ (Create this directory if it doesn't exist).

# Usage
Change via distribution specific tweak-tool.

# Don’t like the folder colors? Try this:

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
