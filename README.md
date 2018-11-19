# Mockup Action Pack

This repository contains all Photoshop Actions (.atn files) used to speed up the customization of some highly complex edition mockups.

## How to use the mockups with PS Actions
These Photoshop Actions are only required in some mockups and this is in order to streamline customization and facilitate their use, please follow these steps to edit the mockups using Actions:

1. Download the Latest [Actions Pack](https://github.com/CarlosViloria/Mockup-Action-Pack/releases/latest)  
2. Install the actions by double clicking to the CV Mockups Action Pack.atn file
3. Open the Mockup in Photoshop
4. Place your design inside the blue layers -these are Smart Objects, so to open them you just have to double click on the icon or right click on the layer and select Edit Contents-.
5. Place your design using the help guide, hide the Guide layer, Save, close the current document and continue with the next Blue Layer if there are.
6. Open the Actions Panel (Window / Actions) and play the related action which is described on the Help Guide layer -Step 02-.

## I don't want to use the PS Actions
Go to the Resource / Mockups Folder and edit the contents of the Purple Layers. It'll be opened in a new window (tab) allowing you to place your own design without use Actions.

## Troubleshooting
Handling the error: The command “Select” is not currently available running the Actions.
This error happens when Photoshop arbitrarily rename the Smart Objects causing the loss of the link between the Mockup file and the Actions. It is due to the Photoshop temporary directory is full. So easiest way to fix this is closing Photoshop without save the Mockup in order to free up that directory.

If you accidentally saved the changes with the bad names, you can fix it manually deleting the number added at the end of the layer arbitrarily by Photoshop and then run de action again.
