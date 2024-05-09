# Serbian (српски) prompts for Piper Recording Studio

As there were no definitions for Serbian language for Piper Recording Studio I created this repository with intention to collect as much prompts as possible.

I hope this will help making Piper Voice AI files in Serbian language.

Feel free to join!



If you are asking why this is not part of Piper Recording Studio Repository (https://github.com/rhasspy/piper-recording-studio/tree/master/prompts) simple explanations is that documetntaton how to prepare promts is scarse, and I am not sure how to organize them properly. My intention is to move all this into https://github.com/rhasspy/piper-recording-studio/tree/master/prompts/ after it is cleared out it this kind of prompt organization is acceptable.

I did ask (https://github.com/rhasspy/piper-recording-studio/issues/17) but got no proper response. So, not to loose time, I created this repository so prompts can be created and collected until it is decided to move all of this to Piper Recording Studio Repository.

## Files organisation

/Serbian (Serbia)_rs-SR  - ready made prompts

/ods - ODS files (OpenOffice Calc, LibreOffice Calc) that contain definitions of prompts. Makes generating IDs easier.

You can edit existing ODS files or create new ones. The first column is reserved for ID and second is for actual prompt text in Serbian Cyrillic.

Make sure ID is unique for whole language, not just current file. Use cell formula to combine prefix with row number to create ID. Do not insert rows once data is exported to text file as that would change ID's for prompts. Only add prompts as new rows at the bottom.

Once ODS file is prepared export it in CSV format, un UTF-8, tab delimited nad with no quotes for cells. Saved file name should have TXT extension and placed in /Serbian (Serbia)_rs_SR directory. When you update rpository, please update both ODS and CSV file at the same time.

If you create themed prompts create file prefixed with theme name. If more files would be created then create subdirectory to store them.

Do not enter more that 200 prompts in one file. Just create another file with unique prefix. Feel free to use some numbering scheme.

For prompts that are generic (not themed) use IDs containing 10 numbers. File name should contain first prompt id which is in a file and first prompt id increased by 200 (as file should contain no more than 200 entries). Example: 0000000000-0000000200.ods. Put these files in /ods directory. 

Do not edit existing files. Just create another one by choosing the first free ID number, instead.

For thematic files, you can add to existing thematic file if there is space (meaannig there is less than 200 rows in a file). If there is no room, create file with same name just add number suffix.


## Copyright (absence of)

All entered propmts must be under free licence. That means do not just copy some random text and use it to create prompts. You must only use sources that allow freely copying text and usage in projcet like Piper Recording Studo. The best way is to create text by yourself.
