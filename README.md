# Edict in Wanikani order 

This is a repository for my "Edict dictinary in Wanikani order" csv file and for the python script used to create it.

The file includes the all the words included in the edict dictionary that can be constructed using Kanjis learned through the Wanikani order. This file includes all of the kanjis not yet included in Wanikani but are in the JLPT N1. Each level after 60 has 33 kanjis in them, except for level 68 which has 30. Words constructed only out of hiragana or katakana are excluded from this file.

In total there are 133,106 words in the file. Learning all of these is almost impossible but you are free to try. Who there is to stop you? No one!

You are free to use the file and the script however you want, just please credit me if you use it somewhere.

## File structure

Here's an example row from the file:

`業|10|手工業|しゅこうぎょう|handicraft industry`

This is how the file is read:

`Kanji | Wanikani Level | Word and additional readings | Hiragana reading | English translation`

Some of the words might also contain multiple readings. These are seperated with `;` instead of `|`. Alternative translations are sperated with `/`:

`横|10|横持ち;横持|よこもち|(1) conveyance (of goods, materials, etc.) / (2) holding horizontally (e.g. a smartphone) `
