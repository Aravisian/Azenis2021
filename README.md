# Azenis2021
Azenis2021 Cinnamon, Mate. XFCE theme. Styled after J.J.Yings Azenis2.


Azenis 2021 is based off of Azenis 2, originally created by J.J. Ying for Windowblinds. Azenis 2 won the GUI championship. Ported by EZy to KDE and to Gnome2 by JamesHardy88. Aravisian (that's this guy) later attempted a gtk 3.18 port and 3.22 port called AzenisEX that if typed in all caps has a funny name.
Azenis 2021 is built from the ground up for gtk3 rather than porting older files. I sought to incorporate the dark theme elements introduced by EZY and used by JamesHardy88, along with the original art style of J.J. Ying. There are many changes... Instead of relying on a lot of assets and images, linear gradiants have replaced many images to improve sizing and scaling. Buttons, checkboxes and Range are all examples of New design and images.
Metacity, XFWM and CSD titlebuttons have been increased, to make it easier to hit your target.

Many thanks to J.J. Ying for giving his permission to continue Azenis Theme in gtk3 along with Azenis-One, a port of the Original Azenis theme entry that preceded Azenis 2.

Installation:
Extract "azenis2012.tar.gz to your /usr/share/themes folder or to ~/.themes
Apply through your settings, appearance or window manager settings.
For Mate, Cinnamon, XFCE4 Desktops.
Cinnamenu; Stark Menu; Whiskermenu:
Right click the menu icon and select properties or configure. Under appearance, select custom icon. Navigate to .../themes/Azenis 2021/cinnamon/mint-menu-icon.png. XFCE 4.16 - Youc can select "No Icon" in whiskermenu, instead.
Select this as your icon - it will act as the 'transparency' to overlay the Menu Icon Button.
XFCE4 - WhiskerMenu users MAY experience a #474747 border around the icon. To resolve if this happens; Open your Panel Settings > Appearance and select the Panel.png from /themes/Azenis 2021/whiskermenutheme as the background on the panel instead of using the system panel.

To disable overlay scrollbars:
sudo nano /etc/environment
Add the following line:
GTK_OVERLAY_SCROLLING=0
Hit ctrl+x to exit, hit the Y key to say yes to save, then hit the Enter key to save under current configuration.

Alternatively, to disable overlay scrollbars only per specific application:
In terminal run (In this example Gedit- change the app name as needed)
GTK_OVERLAY_SCROLLING=0 gedit

OR in terminl run (Non-XFCE4 D.E.'s)
gsettings set org.gnome.desktop.interface overlay-scrolling false

Gedit users may want to use
gsettings set org.gnome.gedit.preferences.editor highlight-current-line false
to make highlited lines readable. Or, Navigate to preferences > themes and use the included Azenis.xml theme for Gedit, Pluma and Xed.

FIREFOX (and other browsers): To fix close, min, max buttons from appearing shrunkedn and no titlebars- click the hamburger icon on far top right.
Then click "Customize Toolbar." A window will open. On the very far left bottom is a checkbox "Titlebar". Check that to "On".
