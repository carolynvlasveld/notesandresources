## LibreOffice Calc cheatsheet 🔢

[LibreOffice Calc](https://en.wikipedia.org/wiki/LibreOffice_Calc) is a free and open-source alternative to Excel. I’m learning how to do things in it that I would normally do in Excel. Here are some things I want to remember.

---

**Select across to the last data column:**

Ctrl + Shift + Right

**Select down to the last data row:**

Ctrl + Shift + Down
    
<!-- 

---
 
E.g., "Big spreadsheet" has data for 2553 species (columns: "Species", "variable 1", "variable 2"), and "Small spreadsheet" 2 has data for a subset of species from "Big spreadsheet" with only 343 species (columns: "Species", "variable 3").


**Answer:** Copy the data from Spreadsheet 2 into a new tab in Spreadsheet 1. Add two columns to the right of the existing data in Spreadsheet 1. In D2, enter: `=IFERROR(VLOOKUP(A2, Sheet2!A:B, 2, 0), "")` and fill down. In E2, enter: `=IFERROR(VLOOKUP(A2, Sheet2!A:C, 3, 0), "")` and fill down.
-->

---

Written by [Carolyn Vlasveld](https://carolynvlasveld.github.io/)
