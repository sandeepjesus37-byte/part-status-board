# Part Status Board

A small production tracker for part-based work. Load a process sheet (Excel) and the board builds its buckets from the sheet's Stage column.

All data is fake. No real part numbers, drawings or company names.

## What it does
- Buckets as tiles with counts; click one to see the parts inside
- Planned vs working machine for setup stages
- Process sheet per part, with Done / WIP / Hold status and notes per operation
- Inspection pass or fail; failed parts go to Rework (with the stage to return to) or Scrap
- Team notes per stage (from, to, message)
- Back, Move to, Undo and a move log
- Chart of parts per bucket, and CSV export

## Try it
Open the live link, press "Import process sheet" and choose `sample-process-plan.xlsx`.

## Built with
React, SheetJS (Excel import), plain CSS. One static page, no server.

## Limits
Data is stored in the browser only. A shared version needs a database and login.
