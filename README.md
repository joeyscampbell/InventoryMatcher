# Inventory Matcher

A simple WinForms app to match item codes between a POS Excel file and an ABC Excel list.

## How to Use

1. Click "Browse" to select both files
2. Click "Compare"
3. View results and optionally filter by name or item code
4. Click "Export to Excel" to save the results

## File Requirements

- POS Excel must contain: `Default Vendor Code`, `Current Quantity`
- ABC Excel must contain: `Item Code #`, `Name`
- `SPA Price Effective` column must be formated as a valid date (In Google Sheets click SPA Price Effective Column, Click Format as Number, and choose Date)
- ABC must be in .xlsx format


