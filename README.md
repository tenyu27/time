# Modern Clock Overlay

A premium, modern, and lightweight clock overlay for OBS. Designed for clarity and aesthetic appeal with a glassmorphism effect. Supports global timezones and deep customization.

Hosted at: [time.tenyu.gg](https://time.tenyu.gg) (or your deployment URL)

## Setup in OBS
1. Create a new **Browser Source** in OBS.
2. URL: `https://time.tenyu.gg` (defaults to PST)
3. Width: `300`
4. Height: `100`

## URL Parameters
Customize the clock by appending these to the URL (combine using `&`):

- `?tz=PST`: Set timezone. Supports abbreviations like `EST`, `UTC`, `JST`, `BST`, `CET`, etc., or full IANA names like `Asia/Tokyo`. (Defaults to PST)
- `?12h=true`: Switches to 12-hour format with AM/PM indicator.
- `?scale=1.5`: Change size without losing quality (e.g., 2 for double size).
- `?transparent=true`: Removes the glass background and border.
- `?style=color:red;`: Apply custom CSS directly to the widget.

### Examples
- **NYC Time (12h):** `https://time.tenyu.gg?tz=EST&12h=true`
- **Tokyo Time:** `https://time.tenyu.gg?tz=JST`
- **Minimalist UTC:** `https://time.tenyu.gg?tz=UTC&transparent=true`
