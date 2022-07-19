# CleanGDrive

A script to tidy up the Micromet G:drive.  Eddypro can end up creating duplicate output folders that need to be cleaned up.

It will move files that are in folders with names e.g.: 
* From eddypro_binned_cospectra (1) to eddypro_binned_cospectra
* If file already exists in the destination, it will skip over it and allow you to delte it at the end of the process.
* This is much faster than trying to use the windows file manager or vinimet
