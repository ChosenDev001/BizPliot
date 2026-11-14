# BizPilot

A browser-based business decision simulator built with plain HTML, CSS and JavaScript.


## Features
- Business planning inputs
- Monthly revenue, cost, profit, margin and break-even calculations
- Indicative business health snapshot
- Interactive stress test for sales, variable costs, selling price and fixed costs
- Printable report (choose Save as PDF in the browser print dialog)
- JSON backup export and import
- Local browser storage
- Responsive mobile and desktop layout

## Technology
- HTML
- CSS
- Vanilla JavaScript
- Browser localStorage and Blob downloads

## Important limitations
This is a client-side prototype. It has no server, cloud database, external API, user accounts, cross-device sync or shared collaboration. Data is stored in the current browser profile. Export a JSON backup before clearing browser data or changing devices.

All projections are estimates based on the assumptions entered by the user. They are not guaranteed results, accounting advice, investment advice or a substitute for professional financial advice.

## Suggested testing
- Load the example business and save it.
- Confirm revenue = selling price × monthly units.
- Change each stress-test slider and check the scenario profit updates.
- Export a backup, clear browser data, then import the backup.
- Open the report and use Print / Save PDF.
- Test the layout on a phone-sized screen.
