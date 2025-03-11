# actor-export-tov
This allows Foundry VTT users to export Tales of the Valiant Characters to a PDF using bushvin\actor-export's Custom Provider Option

High Level Instructions:
1) Open up your version of Foundry and install the Module: 'Actor export' and add that Module to your Game World.
2) Download the files 'Export ToV.txt' and 'ToV BF41.pdf' to your PC from this project.
3) Edit the 'Export ToV.txt' file and where it says YOURSERVERHERE, replace that with name of your server.  If you are using your PC for hosting, Localhost:30000 works, assuming you are using the default port.
4) In your Game World in Foundry, click on the 'Game Settings' tab, click on 'Configure Settings' and choose the 'Actor export' tab.
5) Click on the Custom Provider button and in the white area, copy and paste all rows from 'Export ToV.txt' into that area.  Save changes.
6) Open a Character in Foundry that you want to export and click on the 'Export' button at the top right of the character sheet.  In the box that appears, check the 'Custom Provider' checkbox and click on the 'Choose File' button.  In the 'Open' window that appears, click on the 'ToV BF41.pdf' you downloaded and hit 'Open'.  Click Download.
7) You will be prompted on where to place and name the file.  Click Save.  Open that Saved file and you should see your data.

Notes:

Kobold Press' pdf file will not work with this code, as I had to change the orginal file from KP.  Once the code is more stable, KP has said they will replace their file with mine so it will work in the future.

Video Instructions: Soon :)
