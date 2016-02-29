# enveloper
Winforms app for recording addresses and printing envelopes

This program is a 'DevOps' style demonstration of a program for recording 'send to' and 'return' addresses and printing envelopes. It is written in C#/Winforms and compiled to .net 4.5. It 'saves' and 'loads' the respective collections of addresses in XML files saved in one's personal 'my documents' folder. The main menu selects 'return' or 'send to' addresses. In each of the address edit screens, there is a search user control to the left and an 'edit' user control to the right. Click 'search' to fill the grid with records. Click 'clear' to blank out the edit form, type in an address line, and click 'add' to create a new record. When altering an existing record, click 'update' to save the changes.

Each address screen has a 'Font' selection under the 'File' menu. One can select the font for the respective address, it is saved automatically once selected.  If the user forgets to set the fonts, the preview crashes. The code is supposed to load defaults, but it isn't working at the moment.

Once a 'send to' record is selected, click on 'preview/print' to preview the envelope.  The only size envelope printed is #10. In the previewer, click on the print button to print the envelope.

*------------------------------------------------------------------------------------------------------------------------------------*

This application is intended to be reviewed by prospects that might use my services for software development. It was written quickly (in about 3 days). It demonstrates WinForms development, user controls, XML serialization, system.drawing.printing functionality, and font dialog box interaction. It is not designed to be a 'consumer product'.

Most of my work since 2010 has been heavily focused on ETL to SQL Server and PostGreSQL. This UI organization is appropriate to bulk imports and various rowset filtering and ordering presentation. The Edit screen allows the application of manual data cleanup where appropriate.
