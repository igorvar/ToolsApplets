# ToolsApplets
Tools applets with Created and Updated data

In the process of work, it is necessary to get information about the objects of Siebel. This can be done by selecting Help -> About record from the Siebel tools menu. At the same time, you need to become on each record and there is no possibility to sort by the date of the last change, for example.

As an alternative, an archive of applets is proposed, in which the fields Created, Created By, Updated and Updated By are added. These applets must be compiled into SRF Tools.

The algorithm of action is as follows:
1. Copy the SRF tools. Its location can be found in Help -> About SRF tools, File Name field. This file is copied with the name siebel_sia_new.srf.
2. Import applets from the archive and compile them into siebel_sia_new.srf.
3. Close the tools and replace the original file with siebel_sia_new.srf.
4. Open the tools with the new SRF and configure all the applets tools so that the new fields are at the end of the list (on all tools screens, right click -> Column Displayed)
5. Close the tools to save.
6. Open the tools and enjoy.
