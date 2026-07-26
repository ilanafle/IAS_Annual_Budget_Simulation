# Institute of Advanced Studies Annual Budget Simulation
This repository contains a preliminary budget simulation for maintaining an interdisciplinary research institute estimating annual personnel, infrastructure, technology, research-program, outreach, governance, and contingency costs. All parameters are configurable, allowing the simulation to be adapted to different institutional models. 

**Documentation and User Guide**
A browser-based simulation for estimating the annual running costs of an interdisciplinary research institute – Institute of Advanced Studies. The model is intended for early-stage planning, scenario comparison, and discussion, rather than as a final institutional budget or financial quotation. Notably, this simulation does not include the initial set up costs. 
The simulator is configurable - users can change institute size, staffing levels, stipends, service costs, research-program allocations, technical infrastructure assumptions, exchange rates, and contingency assumptions. 
Budget lines may also be added, removed, reordered, or moved between categories.
Purpose

**The simulator can helps users explore questions such as:**
•	What would it cost to maintain a research institute of different sizes each year?
•	How does the total budget change when faculty, student, postdoctoral, visitor, or administrative headcounts change?
•	What share of the budget is devoted to people, operations, technology, research activity, governance, and contingency?
•	Which assumptions have the largest effect on the final estimate?
The default values represent one possible institutional model and should be treated as editable planning assumptions.

**Running the simulator**
The application is contained in a single HTML file and does not require installation.
1. Download budget_simulation_offline.html.
2. Open it in an Internet browser.
3. Edit the values directly in the interface.
4. Use Generate Report to open a printable summary.
The application is designed to work on desktop, tablet, and mobile screens.

**Main fields**
Each budget line contains one or more of the following fields:
Field	Meaning
Budget line	The name of the cost, such as faculty salaries, server services, seed grants, or legal support.
Description	A short explanation of what the line includes or the assumption behind it.
₪ / unit	The annual cost of one unit, entered in New Israeli Shekels. A unit may be one person, license, grant, publication, service contract, or another planning unit.
Units	The number of people, licenses, grants, publications, positions, or other units included.
Line total	Calculated automatically as cost per unit × number of units. For lump-sum items, the number of units is treated as one.
Subtotal	The combined annual cost of all lines in a category or subcategory.
Contingency percentage	A reserve calculated as a percentage of all other budget lines combined.
Grand total	The annual subtotal plus the contingency reserve.

All underlying inputs are stored in NIS. Currency controls change how totals are displayed.
Currency display
The simulator supports:
•	NIS
•	USD
•	A custom currency, such as EUR

**Editing the simulation**
Change a value
Edit the ₪ / unit or Units field. Totals and category shares update automatically.
Add a budget line
Use Add budget line under the relevant category. A custom line allows you to enter:
•	A title
•	An optional description
•	A cost per unit
•	A number of units

**Remove a budget line**
Custom lines include a remove button. Default lines are retained by design, but their values may be set to zero when they do not apply.
To permanently delete or rename a default line, edit the DEFAULTS object in the HTML source.

**Reorder or move a line**
Use the drag handle (⠿) to reorder a budget line. Lines can also be moved between categories where browser drag-and-drop support permits it.

**Reset the model**
Use Reset to defaults to restore all original values. This removes custom lines and discards current edits

