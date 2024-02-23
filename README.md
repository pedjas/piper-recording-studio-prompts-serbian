# Serbian (српски) prompts Piper Recording Studio

As there were no definitions for Serbian language for Piper Recording Studio I created this repository with intention to collect as much prompts as possible.

I hope this will help making Piper Voice AI files in Serbian language.

Feel free to join!

## Files organisation

/Serbian (Serbia)_rs_SR  - ready made prompts

/ods - ODS files (OpenOffice Calc, LibreOffice Calc) that contain definitions of prompts. Makes generating IDs easier.

You can edit existing ODS files or create new ones. The first column is reserved for ID and second is for actual prompt text in Serbian Cyrillic.

Make sure ID is unique for whole language, not just current file. Use cell formula to combine prefix with row number to create ID. Do not insert rows once data is exported to text file as taht would change IDćs for prompts. Only add propmts as new rows at the bottom.

Once ODS file is prepared export it in CSV format, un UTF-8, tab delimited nad with no quotes for cells. Saved file name should have TXT extension and placed in /Serbian (Serbia)_rs_SR directory.

If you creaste themed prompts create file prefixed with theme name. If more files would be created then create subdirectory to store them.

Do not enter more that 200 prompts in one file. Jsu create another file with unique prefix. feel free to use some numbering scheme.

For prompts that are generic (not themed) use IDs containing 10 numbers. File name should contain first prompt id which is in a file and first prompt id increased by 200 (as file should contain no mre than 200 entries). Example: 0000000000-0000000200.ods. Put these files in /ods directory. 

Do not edit existing files. Just create another one by choosing the fist free ID number, instead.

For thematic files, you cann add to existing thematic file and there is free rows. If there is no room, create file with same name just add number suffix.


## Copyright (absence of)

All entered propmts must be under free licence. That means do not just copy some random text and use it to create prompts. You must only use sources that allow freely copying text and usage in projcet like Piper Recording Studo. The best way is to create text by yourself.
