# Chapter 2 – Google Sheets Automation

The following explanation is documentation derived from the project at this link:
[Link](https://github.com/adstika20/portfolio-automation-Google-Appscript/blob/main/Chapter%202%20%E2%80%93%20Google%20Sheets%20Automation/Google%20Sheets%20Dashboard%20with%20Custom%20Menu)

## Google Sheets Dashboard & Data Viewer (with Custom Menu)

This project is an implementation of Google Apps Script integrated with Google Spreadsheet to:

- Create a custom menu in Google Sheets
- Manage sheet content (create new sheets, copy data, add formulas)
- Display sheet data in an interactive dashboard using an HTML modal dialog

### Key Features

1. Custom Menu (Advanced)
   - Content → Generate new sheets with random data & copy values from the main sheet.
   - Formula → Insert formulas & apply formatting to specific ranges.
   - Info → Show additional information in an HTML modal popup.
   - Dashboard → Display all sheets in a dropdown and render sheet data as an HTML table.

2. Sheet Data Management
   - Automatically create and delete sheets.
   - Copy values from a main sheet into new sheets.
   - Insert formulas programmatically in specific ranges.

3. Interactive Dashboard (HTML Service)
   - Modal dialog with a dropdown of sheet names.
   - Render sheet data dynamically in a table.
   - Client–server communication using google.script.run.

### How to Use
   - Open Google Spreadsheet.
   - Paste the provided code into Apps Script Editor.
   - Create HTML files (dashboard.html and info.html).
   - Reload the Spreadsheet → A new Advanced menu will appear.
   - Use the menu items (Content, Formula, Info, or Dashboard) as needed.

     <img width="1918" height="860" alt="image" src="https://github.com/user-attachments/assets/1e441d8a-4936-4ee5-b5b3-f5b916beaa43" />
