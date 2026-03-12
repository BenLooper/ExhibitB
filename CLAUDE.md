# Claude Instructions for ExhibitB

## Timestamps

All content files use **Central Time (CT)** for timestamps.

- Format: `'YYYY-MM-DDTHH:MM:SS-06:00'` (CST) or `'YYYY-MM-DDTHH:MM:SS-05:00'` (CDT)
- **Always ask the user for the current local date and time** before creating or editing a file if unsure — do not derive time from UTC or system clock.
- The system clock may be UTC, which will be wrong. Use the time the user provides.

## Chinese Word Files

When creating a new Chinese vocabulary file:
- **Always ask the user for the example sentence** (例子) before creating the file — do not generate one yourself.
