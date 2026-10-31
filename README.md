# Prompt-Builer
Build prompts by clicking cells in a spreadsheet. Open a CSV, XLSX or ODS file, click the pieces you want, and copy the finished prompt. It is one HTML file that runs offline in your browser, with nothing to install and nothing uploaded anywhere.

I made it for AI image-editing workflows, where a prompt is assembled from reusable parts (subject, style, lighting, camera, mood, and so on) kept in a table. Copying scattered cells out of a spreadsheet is awkward, so this tool does it with clicks.

screenshot

Features
Opens CSV, XLSX and ODS files. Drag a file onto the page or use the Open button. Workbooks with several sheets get a sheet picker.
Click cells to build a prompt. Click again to remove a cell. Join with a comma, space, period or new line, and order the result by click order or by table order (by column or by row).
Search. Matching cells are highlighted, and you can hide all other rows. Search treats Arabic and Persian letter variants as the same.
Bold text is preserved. If a word or a whole cell is bold in your file, it is bold in the table.
Edit in place. Double-click a cell to edit it. Tick Edit rows/columns to insert, delete or move rows and columns. Undo and Redo cover your last 60 changes.
Export the edited table as XLSX, ODS or CSV, with bold kept.
Saved combinations and history. Save prompts that work, reload them later (the cells are selected again), and export them as a text file.
Persian and other right-to-left text works in cells, search and prompts.
Light and dark mode follow your system setting.
Quick start
Download prompt-builder-table.html.
Open it in your browser (double-click it).
Click Open file and choose sample-prompts.csv, or your own table.
Click cells to build the prompt, then Copy prompt.

Your table, saved combinations and history are kept in the browser's local storage for that file, so they are still there next time. Clearing the browser's site data removes them, so use Export to keep a copy.

Your file format

Any table works. Put one prompt category per column (subject, style, lighting...) and the options for it below. The first row is treated as column headers, which you can switch off. CSV files may use commas, semicolons or tabs, and the encoding can be switched to Windows-1256 for Persian files saved by Excel.
