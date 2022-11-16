# Week 3

## Spreadsheets

* The first steps a data analyst takes when working with data in a spreadsheet are to sort and filter the data.
* To perform calculations in a spreadsheet, data analysts use formulas and functions, such as SUM, AVERAGE, and COUNT.
* Spreadsheets are an important tool in every data analyst’s toolkit. They help you organize, clean, and analyze data. The sharing and commenting features in Google Sheets let you communicate and collaborate with teammates — a key part of your role as a data analyst.
* Spreadsheet titles should be short, clear, and state exactly what the data in the spreadsheet is about.
* Data analysts use formulas and functions to save time and effort by automating commands.

**Operator** - A symbol that names the type of operation or calculation to be performed.

**Cell Reference** - A cell or range of cells in a worksheet that can be used in a formula.

**Range** - A collection of two or more cells.

* Absolute referencing is marked by a dollar sign ($). For example, =$A$10 has absolute referencing for both the column and the row value. Absolute references will not change when you copy and paste the formula in a different cell. The cell being referenced is always the same.

* Resolving **#DIV/0!** error - =IFERROR(A1/B1,"Not Applicable")
* Resolving **ERROR!** (parsing error) - A formula can't be interpreted as input
* **N/A** error - Data in a formula can't be found in the spreadsheet. Use VLOOKUP
* **NAME?** error - A formula or function name isn't understood. Eg. VLOOOKUP instead of VLOOKUP.
* **NUM!** error - A formula or function calculation can't be performed as specified.
* **VALUE!** error - A general error that could indicate a problem with a formula or referenced cells.
* **REF!** - A formula is referencing a cell that is no longer valid or has been deleted. 
* **COUNTIF** - Quickly counts how many items in a range of cells meet a given criterion.  

****

Try not to confuse statement of work with scope of work, which are both abbreviated as SOW. Although they both are used to define deliverables and a timeline, they aren't the same and shouldn't be used interchangeably.

A statement of work is a document that clearly identifies the products and services a vendor or contractor will provide to an organization. It includes objectives, guidelines, deliverables, schedule, and costs. 

A scope of work is project-based and sets the expectations and boundaries of a project. A scope of work may be included in a statement of work to help define project outcomes. 

As a junior data analyst, It's more typical to be asked to create a scope of work than a statement of work. 

****

## Organize a project into a structured scope of work

* Data analysts use **structured thinking** to recognize the current situation, organize information, and identify opportunities. 

In this exercise, you'll organize a staff training event at a company to learn more about SOW.

* **Deliverables** are items or tasks you will complete before you can finish the project.
    * What work is being done, and what things are being created as a result of this project? When the project is complete, what are you expected to deliver to the stakeholders? Be specific here. Will you collect data for this project? How much, or for how long?
* **Timelines** include due dates for when deliverables, milestones, and/or reports are due.
    * Your timeline will be closely tied to the milestones you create for your project. The timeline is a way of mapping expectations for how long each step of the process should take. The timeline should be specific enough to help all involved decide if a project is on schedule. When will the deliverables be completed? How long do you expect the project will take to complete? If all goes as planned, how long do you expect each component of the project will take? When can we expect to reach each milestone?
* **Milestones** are significant tasks you will confirm along your timeline to help everyone know the project is on track.
    * This is closely related to your timeline. What are the major milestones for progress in your project? How do you know when a given part of the project is considered complete? 
* **Reports** notify everyone as you finalize deliverables and meet milestones.
    * Good SOWs also set boundaries for how and when you’ll give status updates to stakeholders. How will you communicate progress with stakeholders and sponsors, and how often? Will progress be reported weekly? Monthly? When milestones are completed? What information will status reports contain?

Usually, projects don’t start until an SOW is approved with its key pieces of content: the deliverables, milestones, timeline, and reports. To collect and synthesize this information, analysts identify and formalize quantifiable project requirements. They use structured thinking to ask clarifying questions, define what to accomplish, and specify project boundaries.

****

A data analyst asks who, what, when, where, why, and how in order to put information into context. Context can turn raw data into meaningful information. It is very important for data analysts to contextualize their data. This means giving the data perspective by defining it. To do this, you need to identify:

*   **Who**: The person or organization that created, collected, and/or funded the data collection
*   **What**: The things in the world that data could have an impact on
*   **Where**: The origin of the data
*   **When**: The time when the data was created or collected
*   **Why**: The motivation behind the creation or collection
*   **How**: The method used to create or collect it