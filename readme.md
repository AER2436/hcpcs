To update the fee schedule (medicare)
Get the new files from CMS, open the "DMEPOS25_XXX.csv" file and delete the first 6 rows. Then delete column D "Juris", then delete "Ceiling" to "TN (R)", then delete "UT (NR)" to
"VI (R)". This will leave you with "HCPCS	Mod	Mod2	CATG	TX (NR)	TX (R)	Description"
Save as DMEPOS.csv and upload/overwrite in github.

For "Former CBA Fee Schedule File- XXXXXXX.csv", delete the first 6 rows. Delete the "Mod3" column. Then delete from "Aiken County, SC" to "Covington, KY", then delete from "Dayton, OH' 
to "Youngstown, OH".
This should leave "HCPCS	Mod	Mod2	CATG	Dallas, TX	Description"
Save as formerCBA.csv and upload/overwrite in github.
