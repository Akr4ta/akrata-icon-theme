# Akrata-icons
Icon theme that combines BeautyLine, Sweet, Papirus, and Candy, harmonized with the Catppuccin Mocha color palette.
* BeautyLine for the majority of the icons,
* Papirus for device-related icons,
* Candy to replace some app icons,
* Sweet for the cursor and folder themes,
* Catppuccin Mocha as the color reference.

There are two versions: akrata-icons (the default) and akrata-icons-anarchy. The only difference is that in the anarchy version, the menu/view-grid icon is replaced by the anarchist "A" symbol.

# Install
Download the .zip file.

Extract the archive and move either the akrata-icons or akrata-icons-anarchy folder to icons directory ~/.local/share/icons/ (Create this directory if it doesn't exist).

Ensure papirus-icon-theme is installed for correct device icons.

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
This icon theme has only been tested in Gnome and Cosmic desktop environment. Other environments may display color inconsistencies.

Akrata Theme uses device icons from Papirus Icon Theme. Not installing Papirus may result in missing or incorrect device icons.

This theme is still a work in progress, as we're currently adjusting the icon colors.
