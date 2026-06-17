# Price Calculator

A single-file static calculator for turning a cost and target margin percentage into a selling price.

## Published Page

```text
https://numerate64.github.io/margin/
```

## File

- `index.html` - contains the HTML, CSS, and JavaScript for the calculator.

## What It Does

The visible page has one calculator:

- Enter a cost.
- Enter a target margin percentage.
- Click **Calculate Price**.
- The browser displays the required selling price.

The calculation used by the page is:

```text
price = cost / (1 - margin / 100)
```

## Local Preview

Open `index.html` directly in a browser. No build step or server is required.

## Notes

All calculations happen in the browser. The page does not send values anywhere and does not require external services.

The source file contains some unused table/spreadsheet CSS and JavaScript, but the checked-in HTML does not expose a spreadsheet view.
