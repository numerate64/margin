# Price Calculator

A single-file static calculator for turning a cost plus either a target margin or markup percentage into a selling price.

## Published Page

```text
https://numerate64.github.io/margin/
```

## File

- `index.html` - contains the HTML, CSS, and JavaScript for the calculator.

## What It Does

The visible page has one calculator:

- Choose **Margin** or **Markup**.
- Enter a cost.
- Enter the target percentage.
- Click **Calculate Price**.
- The browser displays the required selling price.

For margin calculations, the page uses:

```text
price = cost / (1 - margin / 100)
```

For markup calculations, the page uses:

```text
price = cost * (1 + markup / 100)
```

Margin must be less than 100%. Markup can be 100% or higher.

## Local Preview

Open `index.html` directly in a browser. No build step or server is required.

## Notes

All calculations happen in the browser. The page does not send values anywhere and does not require external services.
