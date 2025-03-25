# Akrata-icons
Icon theme that combines BeautyLine, Sweet, Papirus, and Candy, harmonized with the Catppuccin Mocha color palette.
* BeautyLine for the majority of the icons,
* Papirus for device-related icons,
* Candy to replace some app icons,
* Sweet for the cursor and folder themes,
* Catppuccin Mocha as the color reference.

# Install
Download the .zip file

Extract the .zip file to the icons directory ~/.local/share/.icons/ (create it if necessary).

Ensure papirus-icon-theme is installed for correct device icons

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


# Warning
This icon theme has only been tested in Cosmic and GNOME desktop environments. Other environments may display color inconsistencies.

Akrata Theme uses device icons from Papirus Icon Theme. Not installing Papirus may result in missing or incorrect device icons.
