# Ricks Radio Conversions work tracker

This first version is a public, read-only table. Its running totals and search are calculated from `work-orders.csv`. No customer records have been added.

## Updating the list

Open `work-orders.csv` in Excel, add or update rows, then save as CSV and upload the revised file to the GitHub repository. You can also edit the CSV directly on GitHub. Visitors cannot edit the list.

Use these exact status values: Received, In progress, Waiting on parts, Completed.

Keep customer names, addresses, phone numbers, email addresses, and private notes out of this public file. Use work order numbers so customers can identify their projects.

## Hosting and embedding

Upload index.html and work-orders.csv to a GitHub repository and enable GitHub Pages for the branch containing them. Once its actual URL is known, insert an iframe pointing to that URL into the IONOS HTML module, with width 100%, height 850, and title "Ricks Radio Conversions current work". If the plan has no HTML module, link a website button to the published tracker.

Publication and embedding are pending GitHub repository access and a signed-in IONOS editor. This version does not provide browser-based spreadsheet editing or a private database.
