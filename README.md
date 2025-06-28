# MotorPerformanceCalc18RLoad

## 18Ω Load Performance Calculator

This web-based application calculates and visualizes motor performance under an 18Ω load condition. Users can adjust RPM with a slider or input field, and view real-time calculations of voltage, current, power, torque, and efficiency.

### Key Features

* **Interactive RPM Control:** Slider and numeric input (1,000-12,000 RPM). Real-time updates.
* **Comprehensive Outputs:** Voltage (V), Current (A), Power (W), Torque (N·m), Efficiency (%).
* **Visualization Tools:** Four interactive charts:

  * Voltage vs RPM
  * Power vs RPM
  * Torque vs RPM
  * Efficiency vs RPM
* **Safety Features:** Warning displayed when RPM exceeds 9,000.
* **Technical Implementation:** Pure HTML/CSS/JS. Uses Chart.js. Mobile-responsive design.

### How to Use

1. Open `index.html` in a browser.
2. Adjust RPM using the slider or type a value.
3. View calculated parameters and interactive charts.
4. Switch chart tabs to see different relationships.
5. Watch for warnings when RPM exceeds tested limits (>9,000).

### Technologies Used

* HTML / CSS / JavaScript
* [Chart.js](https://www.chartjs.org/) for data visualization
* npm install chart.js

### License

MIT License.

### Note

You can run this tool by simply opening the HTML file in any modern browser—no server required. To share or deploy, consider using GitHub Pages or Netlify.
