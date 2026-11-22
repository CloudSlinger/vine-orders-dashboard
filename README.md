# Vine Orders Dashboard

A browser-based dashboard for Amazon Vine itemized reports. Track orders, shipments, cancellations, and estimated tax value (ETV) across one or more reports.

## Getting Started

1. Download `index.html` and open it in your browser. No installation or build step is required.
2. Select or drag in one or more Vine itemized reports. The dashboard accepts `.xlsx`, `.xls`, and `.csv` files.
3. Use the filters to explore your orders. In **All Orders**, select **Export CSV** to save the rows currently shown.

## Features

- Combine multiple reports and years, and merge overlapping order entries.
- Review order trends by month, week, weekday, and value tier, plus rolling 30, 60, 90, and 180 day totals.
- Find your highest-value days and see predicted best days and product categories.
- Review shipping times and cancelled orders.
- Set a rolling ETV limit, see when you go over it and when you will be back under, and switch between **All Items** and **Shipped Items Only**.
- View quarterly estimated tax payments for planning. Enter your own **Taxable Percentage**. The chart marks every due date, with April 15 highlighted.
- Drag report cards and summary tiles to rearrange them. The dashboard saves your layout in your browser. Select **Reset Layout** to restore the default order.
- Switch between light and dark themes.

## Privacy

The dashboard processes imported reports in your browser and never uploads them. Keep personal spreadsheets, CSV exports, and any generated `vine_data.js` file out of the repository.

## Disclaimer

All figures, including estimated tax values, taxable percentages, limit tracking, and quarterly payment amounts, are calculated from the report data you load and are for estimation purposes only. Nothing here constitutes tax, legal, accounting, or financial advice, and no guarantee is made about accuracy or completeness. Tax rules, rates, and due dates can change and may not reflect your situation, such as state or local taxes. Confirm amounts and deadlines with the IRS or a qualified tax professional before filing or paying.

This project is provided "as is," without warranty of any kind. To the fullest extent permitted by law, the authors are not liable for any damages, penalties, interest, or losses arising from its use.

## Trademarks

Amazon, Amazon Vine, and related names and colors are trademarks of Amazon.com, Inc. or its affiliates and are used only to describe the report format this tool reads. This project is not affiliated with or endorsed by Amazon.

## Third-Party Software

Includes [SheetJS Community Edition](https://sheetjs.com/) (Apache License 2.0) to read spreadsheet files. Its copyright notice is kept at the top of the bundled library in `index.html`.

## License

Free to use, share, and copy. See the `LICENSE` file for terms.
