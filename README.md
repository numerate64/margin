# Price Calculator

A simple, responsive web application for calculating product prices and managing inventory costs with margin calculations.

## Features

### Single Entry Mode
- Calculate selling price based on cost and desired margin percentage
- Simple, intuitive interface with real-time price display
- Ideal for quick price calculations

### Spreadsheet Mode
- Manage multiple items with detailed price calculations
- Track item name, list price, cost, discount percentage, and margin
- Automatic calculation of:
  - Discount amount
  - Selling price based on margin
  - Profit margin
- Add or remove rows as needed
- Total summary across all items

## How to Use

1. **Single Entry Mode**:
   - Enter the cost of your item
   - Specify your desired margin percentage
   - Click "Calculate Price" to see the result

2. **Spreadsheet Mode**:
   - Click "Spreadsheet" tab to switch modes
   - Add rows for each item you want to track
   - Enter item description, list price, cost, and margin
   - The discount percentage field is optional for discount calculations
   - Row calculations update automatically as you type
   - View totals at the bottom of the table

## Formula

The price calculation uses the following formula:

```
Price = Cost / (1 - Margin% / 100)
```

## Technology

- Single HTML file with embedded CSS and JavaScript
- No external dependencies
- Responsive design that works on desktop and mobile
- Modern gradient UI with smooth animations

## Files

- `index.html` - Main application file (contains HTML, CSS, and JavaScript)

## Browser Compatibility

Works in all modern browsers that support HTML5, CSS3, and ES6 JavaScript.

## License

This is a simple utility tool for price calculations.