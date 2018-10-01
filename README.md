RTS-LB - Real-Time Scheduling in Libre Office
---------------------------------------------

Version : 2.0
Author : Giuseppe Lipari

---

# Introduction

This is a set of LibreOffice spreadsheet files and model to simulate
real-time schedules.

The template file fp_schedule.ots allows to simulate fixed priority
scheduling of up to 8 periodic independent tasks.

The template file edf_schedule.ots allows to simulate fixed priority
scheduling of up to 8 periodic independent tasks.


# Installing

1. Just open LibreOffice Calc Spreadsheet,
2. Click on the Menu "File/Templates" (or just press Ctrl-Shift-N),
   the template manager will open.
3. Then click on "My Templates" and "Import"
4. Select the template file you want to import (fp_schedule.ots).

Now, you can just open a new spreedsheet any time you want by clicking
on "File/Templates/My Templates" and fp-schedule.

Alternatively, you can run from the command line:

	soffice fp_schedule.ots

Of course, same procedure is valid for edf_schedule.ots


# Usage

Just change the parameters on the left table, the schedule on the
right will be updated instantly according to your modification. If you
want more than 2 tasks (up to 8), just un-hide rows 8-11.

The formulas are in the hidden rows 16-73. Do not modify them
otherwise the table does not work.







