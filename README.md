# Malaysia Daily Snapshot

A live dashboard showing weather, air quality and ringgit exchange rates for all 13 Malaysian states and 3 federal territories, using free open data.

🔗 **Live demo:** https://derekkered044.github.io/malaysia-dashboard/

![Screenshot of the dashboard](screenshot.png)

## What it shows
- Current weather and a 7-day forecast for each state capital and federal territory
- Air quality (US AQI, PM2.5, PM10, ozone) with a colour-coded rating
- Ringgit exchange rates against USD, SGD, EUR, GBP and JPY, plus a 30-day USD trend chart
- A comparison table ranking all 16 places by air quality and expected rainfall

## Data sources
- [Open-Meteo](https://open-meteo.com/) for weather and air quality (CC BY 4.0, free for non-commercial use)
- [Frankfurter](https://frankfurter.dev/) for exchange rates (central bank reference rates, updated daily)

## Built with
HTML, CSS and JavaScript, Chart.js for the chart, and GitHub Pages for hosting. There is no backend, and no API keys are needed.

## Limitations
- Air quality values are modelled estimates, not official readings from Malaysia's Department of Environment.
- Exchange rates are daily reference rates, not live trading prices.
- Each place is represented by one point, usually the state capital.

## What I learned
- [One or two things you learned, e.g. how to call web APIs with fetch, handle errors and loading states, or deploy with GitHub Pages]

## Run it locally
Download `index.html` and open it in a browser. It needs an internet connection to load the data.

## Credits
Built with AI assistance (Anthropic Claude). Data by Open-Meteo and Frankfurter.
