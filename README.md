# Serbian (српски) prompts Piper Recording Studio

As there were no definitions for Serbian language for Piper Recording Studio I created this repository with intention to collect as much prompts as possible.

I hope this will help making Piper Voice AI files in Serbian language.

Feel free to join!

## Files organisation

/Serbian (Serbia)_rs_SR  - ready made prompts

/ods - ODS files (OpenOffice Calc, LibreOffice Calc) that contain definitions of prompts. Makes generating IDs easier.

You can edit existing ODS files or create new ones. The first column is reserved for ID and second is for actual prompt text.

Make sure ID is unique for whole language, not just current file. Use cell formula to combine prefix with row number to create ID. Do not insert rows once data is exported to text file as taht would change IDćs for prompts. Only add propmts as new rows at the bottom.

Once ODS file is prepared export it in CSV format, un UTF-8, tab delimited nad with no quotes for cells. Saved file name should have TXT extension and placed in /Serbian (Serbia)_rs_SR directory.
