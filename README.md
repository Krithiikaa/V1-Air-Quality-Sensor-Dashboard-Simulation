#
*V1-Air-Quality-Sensor-Dashboard-Simulation*
# 📊 Real-Time Sensor Dashboard (Simulated Data Version)

A clean, responsive, and professional dashboard for visualizing simulated air quality data (PM2.5). This client-side application demonstrates real-time data handling, dynamic charting, tabular display, and Excel export—all in one seamless interface. Ideal for pitching concepts, validating dashboards, or working offline.

---

## 🔧 Features

- 🎯 Simulated real-time PM2.5 data generation (every 5 seconds)
- 📈 Dynamic line chart using Chart.js
- 🧾 Tabular view of the last 10 minutes of readings
- 📤 One-click export to Excel via SheetJS
- 🎨 Elegant UI with Bootstrap styling and smooth animation
- 💻 100% client-side — no server or backend required

---

## 🚀 Usage Instructions

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/your-username/sensor-dashboard-demo.git
   ```

2. **Open `index.html`** in any modern web browser (Chrome, Firefox, Edge).

3. The dashboard will:
   - Auto-generate a new simulated sensor reading every 5 seconds.
   - Plot the data on a real-time line chart.
   - Maintain a 10-minute rolling window of historical data.

4. **Export to Excel**:
   - Click the `Export Last 10 Minutes to Excel` button to instantly download the current data buffer in `.xlsx` format.

---

## 🌐 Deployment

You can easily deploy this dashboard to any static site host. Here’s how to publish via GitHub Pages:

1. Push the contents of this project to a public GitHub repository.
2. Go to your repository’s `Settings > Pages`.
3. Under **Source**, select the `main` branch and root (`/`) directory.
4. Your live dashboard will be accessible at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

---

## 🛠️ Customization

- **Adjust Simulation Frequency**:
  Modify the interval duration in JavaScript:
  ```js
  setInterval(updateDashboard, 5000); // 5000 ms = every 5 seconds
  ```

- **Extend Data Model**:
  Add other sensor parameters like temperature or humidity by updating the `generateSampleData()` function.

- **Integrate Firebase**:
  Swap the data source logic with Firebase listeners for real sensor integration (see Firebase version).

---

## 🧱 Built With

- [Chart.js](https://www.chartjs.org/) – beautiful, responsive charts
- [SheetJS (xlsx)](https://sheetjs.com/) – Excel export made easy
- [Bootstrap 4](https://getbootstrap.com/docs/4.6/) – clean and responsive styling

---

## 📄 License

MIT License — Free to use, modify, and distribute.

> Designed for clarity, reliability, and adaptability. Ideal for IoT dashboards, air quality apps, or data-driven demos.

