# Save Julia! Lottery Game
Sample software that puts into practice unique lottery game method of generating winning and losing tickets.

Software was created using Pascal (Delphi) and can be compiled for Windows and OS X.

A free one (1) year license of Delphi can be downloaded in the following link: https://www.embarcadero.com/products/delphi/starter/free-download

Code can be translated into any other language such as to create a web app.

Points to take into account when creating a commercial version of software:
- Use Odds+ Factor: generate a losing / winning ticket by using a result with less than eight (8) characters and adding fake coordinates and/or colors for the missing number of characters in the result up to having eight (8) characters.
- Generate tickets based on results with five (5) or less characters.
- Using large images to create ticket and show in the ticket only the small version of image.
- If using large images, resize grid as well.
- Using a barcode generator that generates uniques barcodes (should be compared to a database).
- Save a copy of the ticket generated as well as some data such as: both coordinates, html color code for each coordinate, barcode, date in which was created, result, state if winning or losing as default, and Hash function used to hash result.
- A losing ticket as default is one that never wins because it has less than five (5) not fake characters in the result.
- A winning ticket as default is one that can win because it has the minimum number of characters established for winning tickets (can be 6,7 or 8).
- Have a set of Themes previously established such as that ticket generator can pick one randomly.
- Assign an availability date to each theme such as that theme is available only for a given set time frame.
- Design multiple forms of displaying grid in a way that a software can use those forms of displaying grid: software in this repository uses square units, but these units can have any shape as long as they are closed surfaces.
- Use a secure hash function to generate hash based on result. 
- I recommend a new result every week to keep pace and interest.
