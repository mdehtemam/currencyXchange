# CurrencyXchange

A simple web-based currency converter that fetches real-time exchange rates and displays country flags for selected currencies.

## Features

- Convert between major world currencies
- Real-time exchange rates using [Frankfurter API](https://www.frankfurter.app/)
- Country flags displayed for selected currencies
- Responsive and user-friendly interface

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/mdehtemam/currencyXchange.git
   cd currencyXchange
   ```

2. **Open `index.html` in your browser:**
   - No build step is required. Just open the `index.html` file directly in your web browser.

## Project Structure

```
currencyXchange/
├── index.html
├── style.css
├── app.js
└── codes.js
```

- `index.html` – Main HTML file
- `style.css` – Styles for the app
- `codes.js` – Currency code and country mapping
- `app.js` – Main app logic

## Dependencies

- [Font Awesome](https://cdnjs.com/libraries/font-awesome) (CDN)
- [Frankfurter API](https://www.frankfurter.app/) (for exchange rates)
- [FlagsAPI](https://flagsapi.com/) (for country flags)
