Important notes:

The purpose of this macro is to generate a .prg file for the Novastar that already contains the feeder locations for known parts on Upverter. Normally
 this requires the user to manually set the feeder for each part everytime a new board is entered. This macro helps in streamlining this process.

For the macro to work, ensure that all parts that have a known feeder have their feeder location set in Upverter. This can be done by editing the
 part attributes and adding the attribute "Feeder" if it does not already exist. Then, enter the feeder location as it appears in the pick and place 
software as the value. Remember the attribute name and value are case sensitive.

Lastly, create a folder called "Placement" in the root of "Documents." Place the BOM and placement file inside the newly created folder. (ensure BOM 
and placement are .csv files)

If the computer being ran is a non-GEA computer, also note that you need to enter the computer's username rather than your SSO in the "Enter SSO" field.
