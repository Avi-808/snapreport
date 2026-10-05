# SnapReport

SnapReport turns a spreadsheet into a short, easy-to-read report. Add a file to see a plain-language summary, key numbers, a chart, and a preview of the first few rows. Use **Save report as PDF** to print or save the report.

## Use it

1. Open `index.html` in a modern browser with an internet connection.
2. Drop a CSV or Excel spreadsheet on the page, or choose the sample report.
3. Review the summary, chart, and sample rows.
4. Select **Save report as PDF**, then choose **Save as PDF** in the print window.

Files are read in the browser and are not uploaded to an app server. Excel and CSV files are handled by the [SheetJS standalone browser library](https://docs.sheetjs.com/docs/getting-started/installation/standalone/) loaded from its official CDN, so an internet connection is needed.
