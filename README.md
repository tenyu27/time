# Modern Clock Overlay

A premium, modern, and lightweight clock overlay for OBS. Designed for clarity and aesthetic appeal with a glassmorphism effect. Supports global timezones and deep customization.

Hosted at: [time.tenyu.gg](https://time.tenyu.gg)

## Setup in OBS
1. Create a new **Browser Source** in OBS.
2. URL: `https://time.tenyu.gg` (defaults to PST)
3. Width: `300`
4. Height: `100`

## URL Parameters
Customize the clock by appending these to the URL (combine using `&`):

- `?tz=America/Los_Angeles`: Set the timezone using a full **IANA Timezone Name**.
  - [List of all IANA Timezones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)
  - Defaults to `America/Los_Angeles` if not specified.
- `?12h=true`: Switches to 12-hour format with AM/PM indicator.
- `?scale=1.5`: Change size without losing quality (e.g., 2 for double size).
- `?transparent=true`: Removes the glass background and border.
- `?style=color:red;`: Apply custom CSS directly to the widget.

### Examples
- **NYC Time (12h):** `https://time.tenyu.gg?tz=America/New_York&12h=true`
- **Tokyo Time:** `https://time.tenyu.gg?tz=Asia/Tokyo`
- **London Time:** `https://time.tenyu.gg?tz=Europe/London`
- **Minimalist UTC:** `https://time.tenyu.gg?tz=UTC&transparent=true`
