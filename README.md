# MTGA-Card-Data-Explorer
A simple way to extract card data from Magic The Gathering Arena using only HTML and Javascript to read the included MTG Arena data files.
Here is a quick video preview of how it looks: https://youtu.be/aIo06p5G1WQ

# How to configure

1. Delete the two example files provided with the project: data_cards.js and data_loc.js
2. Copy the data_cards_xxxxx.mtga and data_loc_xxxxx.mtga files from "\MTGA_Data\Downloads\Data" to the same folder as the Index.html file. These two files each contain an array of data.
3. Rename the two files to data_cards.js and data_loc.js
4. Edit the two files with an editor that can open large files and put the array in each file into a variable by doing the following:

- In data_cards.js add the following to the start of the file in front of the "[" character:

    var cards =
  
  Then add a ; at the end of the file right after the "]" character;
- In data_loc.js add the following to the start of the file in front of the "[" character:

    var loc =
  
  Then add a ; at the end of the file right after the "]" character;

You can now open the Index file and search through the MTG Arena card database
