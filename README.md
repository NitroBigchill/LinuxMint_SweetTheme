
# LinuxMint_SweetTheme

To change the "System_Theme" you need gtk_themes, Icons & Cursor Files. So, first we have to download these files. To download the files go to these below mentioned websites and download them:
## Icons

BeautySolar Icons : https://www.gnome-look.org/p/2037657  ( File_Name: BeautySolar )

Candy Icons : https://www.gnome-look.org/p/1305251  ( File_Name: candy-icons )

BeautyLine Icons : https://www.gnome-look.org/p/1425426  ( File_Name: BeautyLineSimple )
## Cursors

Sweet Cursors : https://www.gnome-look.org/p/1393084 ( File_Name: Sweet-cursors )
## Desktop Themes

Sweet_New_Flavour gtk_Theme : https://www.gnome-look.org/p/1253385  ( File_Name: Sweet-Dark )
## Theme_Installation

Now extract the downloaded files in the downloads folder or whatever folder you are comfortable with. My suggestion is to create a folder named "Themes" in the home directory and extract all the files in the "Themes" folder. Then open the terminal and execute the below commands:

    cd Themes

For Icons:
    
    sudo cp -r icon_folder_name /usr/share/icons/
Default system location for icons & cursors is the icons folder. So, you have to copy both icons & cursors into the icons folder.

For Cursors:

    sudo cp -r cursor_folder_name /usr/share/icons/

For Desktop Themes:

    sudo cp -r theme_folder_name /usr/share/themes/

Now, open "Themes" application and click "Advanced Settings". The themes we downloaded will appear along with the system themes. Choose your preferred theme and enjoy!!!!!!!

For Wallpapers: https://github.com/whoisYoges/lwalpapers?tab=readme-ov-file#lwalpapers


## Terminal_Theme
You can set terminal colours in the terminal : open_terminal > edit > preferences > profiles

OR

You can try installing "Alacritty" terminal through "Software_Manager" or "Synaptic_Package_manager" or you can install it manually by following the instructions: https://github.com/alacritty/alacritty/blob/master/INSTALL.md

After Installation you have to configure Alacritty in order to make it work.

Alacritty Configuration Steps: https://www.youtube.com/watch?v=cvJ3jKPlIEQ

If you wanna change your default shell to "fish", install "fish" through the command:

    sudo apt install fish

And follow the below steps to change the default shell:

->Add the shell to "/etc/shells" with:

    echo /usr/local/bin/fish | sudo tee -a /etc/shells

->Change your default shell with:

    chsh -s /usr/local/bin/fish

To know your default shell:

    echo $SHELL





![alacritty](https://github.com/user-attachments/assets/1393673b-effd-46ee-9fb2-c40d133894aa)
![LMDE](https://github.com/user-attachments/assets/42fdad51-1dbd-4aa9-83b9-493670e91fd3)


