# Meteo App

Meteo App is a responsive weather application that allows users to search for and view current weather conditions and forecasts for any city. The project features a clean, modern UI and adapts seamlessly to both desktop and mobile devices.

### Screenshot

![](/img/meteo-app.jpg)

### Links

- [Live Site](https://meteo-app-brown.vercel.app/)

## Features

- **City Search**: Enter a city name to retrieve up-to-date weather data.

- **Current Weather**: Displays temperature, weather conditions, and city details.

- **Forecast**: Shows a multi-day weather forecast with icons and temperature ranges.

- **Responsive Design**: Optimized for all screen sizes, including mobile devices (see `@media` queries in style.css).

- **Modern UI**: Uses a soft color palette, rounded corners, and subtle shadows for a professional look.

## Technologies Used

- **HTML5**
- **CSS3** (see style.css for all styles and responsive rules)

- **JavaScript** (for API calls and DOM manipulation)

- **Weather API** (such as OpenWeatherMap or similar, to fetch weather data)

## Getting Started

1. **Clone the repository:**

   ```
   git clone https://github.com/dev-dimma/meteo-app.git
   cd meteo-app
   ```

2. **Install dependencies (if applicable):**

   ```
   npm install
   ```

3. **Configure API Key:**

   - Obtain an API key from your chosen weather provider.
   - Add your API key to the appropriate configuration file or environment variable.

4. **Run the app:**
   ```
   npm start
   ```
   Or simply open index.html in your browser.

## Responsive Design

The app is fully responsive. For screens up to 320px wide, the layout adapts:

- The main weather app container resizes for small screens.
- The search form and weather data stack vertically.
- The forecast switches to a two-column grid for better readability.

See the `@media (max-width: 320px)` section in style.css for details.

## Folder Structure

```
meteo-app/
├── src/
│   ├── style.css
│   ├── index.js
│   └── index.html
├── package.json
└── README.md
```

## License

This project is licensed under the MIT License.

---

## Author

- Website - [Dev Dimma](https://dev-dimma.vercel.app/)
- Twitter - [@devdimma](https://x.com/devdimma)
- Linkedin - [@Dimma Joel](https://www.linkedin.com/in/dimma-joel-technology-frontend-developer-dev-dimma-technical-writer/)

Feel free to contribute or open issues for suggestions and improvements!
