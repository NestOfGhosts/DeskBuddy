# DeskBuddy
A holder that you put on your desk that can hold pencils, scissors, pencil lead, a usb hub, random trinkets and also has a phone arm. Made by me for Hack Club Half Life

All photos are placeholders

<img width="652" height="563" alt="image" src="https://github.com/user-attachments/assets/2b8e9c1c-97f9-4901-9da7-bb5b7deb62c0" />

## Files

Hold is the complete file, with the parts assembled and disassembled. Hold-assembly is just the assembled model. The individual files are in separate.

You may notice that in the complete/assembled files there is an ominous flat rectangle. I'm not entirely sure where it comes from but it's removed in the separate files.

## Disclaimer: own a 3d printer. If you try to print this from a service it *will* bankrupt you 😭

I'm taking advantage of Hack Club Printing Legion, but if you don't own a printer and you don't know someone who does you're out of luck :(

## BOM 

|Part                                                            |QTY  |Unit |Total|Vendor         |
|----------------------------------------------------------------|-----|-----|-----|---------------|
|Filament                                                        |2    |11.47|22.94|Printing Legion|
|Hex Lock Zink Plated Nuts, M4                                   |3    |0.2  |0.6  |Canada Bolts   |
|Machine Screws, Phillips Flat Head, Zinc Plated Steel, M4 x 50mm|3    |0.45 |1.35 |Canada Bolts   |
|C Clamp                                                         |1    |8.39 |8.39 |Amazon         |
|Sandpaper                                                       |1    |5.23 |5.23 |Amazon         |
|Subtotal                                                        |     |     |38.51|               |
|Shipping + Taxes                                                |     |     |26.4 |               |
|Total                                                           |     |     |64.91|               |
|Shipping breakdown                                              |0.69 |     |     |               |
|                                                                |1.83 |     |     |               |
|                                                                |2.56 |     |     |               |
|                                                                |11.33|     |     |               |
|                                                                |11.82|     |     |               |

The design is specially built for ISO7046 M4 screws and DIN 985 nuts, so make sure to use those. If you need to use another screw, you're going to have to edit the model/do some carpentry. See more at [the customization section](https://github.com/NestOfGhosts/DeskBuddy/tree/main#Customization)

## Assembly

- Put the pins in the bottom body
<img width="571" height="490" alt="image" src="https://github.com/user-attachments/assets/99c36dc3-7532-4ffc-ba5a-16645d5be726" />

- Put the Top body on the bottom body
  - You can place your usb hub inside now
  - You can slide bookmarks/other small thin things in between the two halves  
<img width="598" height="535" alt="image" src="https://github.com/user-attachments/assets/65055839-8427-4a9a-9cf6-3d2b760e3567" />

- Two more pins into the side
<img width="658" height="657" alt="image" src="https://github.com/user-attachments/assets/160091e7-fc50-4b29-892f-88a616f2ff61" />

- Add glue to the side of the trinket tray and the side of the main body   
Insert Image

- Insert the trinket tray
<img width="783" height="670" alt="image" src="https://github.com/user-attachments/assets/97009f1b-3079-4939-ac63-bd1ade31bf1b" />

- 2 more pins... (other side)
<img width="724" height="548" alt="image" src="https://github.com/user-attachments/assets/f44baf36-e970-4c1c-be51-6b1fd3d6f7ad" />

- more glue
More placeholders

- Insert the other part or whatever
<img width="977" height="697" alt="image" src="https://github.com/user-attachments/assets/241cef64-84c7-4e23-9664-a965960e9624" />

- Screw in the arm 1, with the nut in the hex cage
<img width="967" height="724" alt="image" src="https://github.com/user-attachments/assets/3d9ad994-84d7-452f-9ace-da7b4aecd077" />

- Screw in arm 2
<img width="652" height="473" alt="image" src="https://github.com/user-attachments/assets/44c2600d-2a33-4156-b4b2-4002a612f48a" />

- Screw in the phone holder
<img width="661" height="616" alt="image" src="https://github.com/user-attachments/assets/bee1c745-d19f-46f4-86a6-d0a2a0e9564c" />

## Customization

There are .FCStd files, so you can use [the full editable files](https://github.com/NestOfGhosts/DeskBuddy/blob/main/hold.FCStd) and edit them with FreeCad or another software that accepts that file type. Unfortunately, I absolutely suck at cad, and the spreadsheet is a lie. While values throughout the file are based off values in the spreadsheet, pretty much everything will break if you attempt to change most of the values, so the editable files are like base objects you can carve/add to, but you cant really change the actual models without a bit of shenanigans. One value that did manage to change in the earlier iterations of the project was Spreadsheet.pin, but all that changes is the diameter of the pins and their corresponding holes. It is similarly difficult to accomodate for different types of screws, as I did not have the foresight to add the screw measurements to the spreadsheet. Luckily, there are only 3 screws and nuts, so it would be an easier modification.



