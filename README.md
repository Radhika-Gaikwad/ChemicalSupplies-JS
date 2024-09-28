# Chemical Inventory Management System

## Overview
The Chemical Inventory Management System is a web-based application designed to help manage and track chemical supplies. It allows users to add, edit, delete, and save data about chemicals in inventory. The application is built using HTML, CSS, and JavaScript, and it leverages Bootstrap for styling and responsiveness.

## Problem Statement
Build the UI as per the given image.

The page has a table that contains a list of chemicals with their details. It also has sort options on each column based on which the user can sort the data. The left top toolbar contains the functionality to add a row, move a row down, move a row up, delete a row, refresh the data, and save the data.

### Requirements
1. Create a JSON array of 15 rows and store the following information about each chemical:
   - `id`
   - `Chemical name`
   - `Vendor`
   - `Density`
   - `Viscosity`
   - `Packaging`
   - `Pack size`
   - `Unit`
   - `Quantity`
   
   Assume suitable data to create the array.

2. Create a table with the column headers:
   - `id`
   - `Chemical name`
   - `Vendor`
   - `Density`
   - `Viscosity`
   - `Packaging`
   - `Pack size`
   - `Unit`
   - `Quantity`
   
3. The table should sort in ascending and descending order when clicking the table column header.

4. Use creative ideas to build the edit functionality. The edit feature is not shown in the table; each individual can take liberty to design this functionality with UI components.

## Features
- **Add New Chemicals**: Users can add new chemical entries to the inventory.
- **Edit Existing Entries**: Users can edit chemical details directly in the UI.
- **Delete Rows**: Users can delete selected rows from the inventory.
- **Move Rows Up and Down**: Users can change the order of the rows.
- **Select All/None**: Users can select or deselect all chemicals in the inventory.
- **Data Persistence**: The application saves data in local storage, ensuring that user changes are not lost upon page refresh.
- **Responsive Design**: The application is responsive and works well on different screen sizes.

## Technologies Used
- HTML
- CSS
- JavaScript
- Bootstrap

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Radhika-Gaikwad/Chemical-Table-Js.git

   Usage
Launch the application in your browser.
Use the toolbar buttons to manage your chemical inventory:
Click the + button to add a new chemical.
Select a row and click the ⬆ or ⬇ buttons to move it up or down.
Select a row and click the 🗑️ button to delete it.
Click the 🔄 button to refresh the table.
Click the 💾 button to save your changes.
Screenshots

Contribution
Contributions are welcome! Please feel free to submit a pull request or create an issue for any suggestions or improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Special thanks to Bootstrap for providing a responsive design framework.
Thanks to all contributors for their support.
