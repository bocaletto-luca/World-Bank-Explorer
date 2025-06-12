# World Bank Explorer | API Free | WEBAPP | Database
#### Author: Bocaletto Luca

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)  
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)  
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chart.js&logoColor=white)](https://www.chartjs.org/)  
[![GPLv3 License](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)

[![Test Online](https://img.shields.io/badge/Test%20Online-Click%20Here-brightgreen?style=for-the-badge)](https://bocaletto-luca.github.io/World-Bank-Explorer/)

---

## World Bank Explorer

World Bank Explorer is an interactive and responsive web application that retrieves, visualizes, and compares global development indicators sourced from the [World Bank Open Data API](https://data.worldbank.org/). The application allows users to explore data on multiple scales:

- **Country:** View data for one of 20 pre-selected nations.
- **Continent/Region:** Select a specific region (with user-friendly labels such as "Europe" or "Asia & Pacific") and view the aggregated data for that region.
- **World:** View global aggregated data.

---

## Features

- **Multi-Scale Data Visualization**
  - **Country:** Choose a country from a list for individual data.
  - **Region:** Options include:
    - Asia & Pacific
    - Europe
    - Latin America & Caribbean
    - Middle East & North Africa
    - North America
    - South Asia
    - Sub-Saharan Africa
  - **World:** Display the aggregated global data.
- **Wide Range of Indicators:** Compare up to 18 economic, social, and environmental indicators such as:
  - GDP (current US$) & GDP per capita (current US$)
  - Population, Life Expectancy at Birth, and Infant Mortality Rate (per 1,000 live births)
  - Unemployment Rate (%)  
  - Primary, Secondary, and Tertiary Enrollment Rates (%)
  - Health Expenditure (% of GDP)
  - CO₂ Emissions (kt)
  - Urban and Rural Population (%)
  - Net FDI (current US$), Inflation (Consumer Prices Annual %)
  - Mobile Cellular Subscriptions (per 100 people)
  - Access to Electricity (% of population)
  - R&D Expenditure (% of GDP)
- **Interactive Time Series Charts:**  
  Data is fetched live from the World Bank API and rendered as interactive line charts using Chart.js.
- **Customizable Time Range:**  
  Choose any period between 1960 and 2025.
- **Responsive & Modern Design:**  
  Built with HTML5, CSS3, and JavaScript for optimal performance on all devices.
- **GPLv3 Licensing:**  
  Open source and free to use under the GNU GPLv3.

---

## Usage

1. **Select Data Scope:**
   - Use the **Select Data Scope** dropdown to choose one of:
     - **Country:** Displays a country selection dropdown.
     - **Continent/Region:** Displays a dropdown with explicit region names (e.g., "Europe", "Asia & Pacific", etc.).
     - **World:** Displays global data (using the "WLD" code); no additional selection is needed.
2. **Configure Parameters:**
   - If “Country” is selected, choose your desired nation.
   - If “Continent/Region” is selected, choose your desired region.
   - Specify the start and end year for the data series.
   - Select one or more indicators from the multi-select control.
3. **Click "Load Data":**
   - The application will fetch the corresponding time series data from the World Bank Open Data API and render an interactive line chart.

---

## Technologies Used

- **HTML5** – Provides the markup structure.
- **CSS3** – Handles responsive design and styling.
- **JavaScript** – Drives application logic and API interactions.
- **Chart.js** – Renders dynamic, interactive time series charts.
- **World Bank Open Data API** – Supplies global development data.
- **Git & GitHub** – Used for version control and repository hosting.

---

## Contributing

Contributions are welcome!  
Please open an issue or submit a pull request for improvements or bug fixes. For major changes, open an issue first to discuss your ideas.

---

## License

This project is licensed under the GNU General Public License v3.0.  
See the [LICENSE](LICENSE) file for more details.

---

## Contact

**Bocaletto Luca**  
GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)

For any inquiries or further information, please feel free to contact me.
