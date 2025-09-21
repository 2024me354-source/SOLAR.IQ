# SOLAR.IQ

A web app that helps users estimate their **solar energy needs, costs, savings, and environmental impact** based on their appliances and location (latitude & longitude).  
Built with **Flask + SQLite + Chart.js** for a simple, interactive dashboard.

---

## ✨ Features

- 📍 **Location-based analysis** using latitude & longitude  
- 🔌 **Appliance input panel** to calculate daily energy consumption  
- ☀️ **Solar panel requirements** estimation  
- 📊 **Interactive charts** for:
  - Energy production vs consumption
  - Cost breakdown & ROI
  - Environmental benefits (CO₂ savings, trees planted)
  - Grid dependency
  - System size comparison
  - Degradation forecast
- 🔋 **Battery sizing** with backup days  
- 💰 **Cost & ROI calculator** (panels, inverter, installation, battery)  
- 🌱 **Environmental impact analysis** (CO₂ savings, trees equivalent)  
- 🛠 **Maintenance schedule** guidelines  

---

## 🖼 Preview

Main heading inside the app:  
☀️ Solar Energy Calculator
Complete solar system calculator with monitoring and analysis

yaml
Copy code

---

## 🛠 Tech Stack

- **Backend**: Flask (Python)  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: SQLite  
- **Charts**: Chart.js  
- **APIs**: 
  - NASA POWER API (solar irradiance data)  
  - OpenWeatherMap API (weather adjustments)  

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/solar-energy-calculator.git
cd solar-energy-calculator
2. Install dependencies
bash
Copy code
pip install flask requests
3. Run the app
bash
Copy code
python app.py
App will be live at: http://localhost:7860

⚙️ Configuration
Weather API: Add your free OpenWeatherMap API key in environment variable:

bash
Copy code
export OPENWEATHER_API_KEY=your_api_key_here
Default fallback values are provided if API calls fail.

📖 How It Works
Enter your latitude & longitude (e.g., 31.4504, 73.1350 for Faisalabad).

Add your appliances with wattage, usage hours, and quantity.

Click "Calculate System".

Get instant results:

Recommended system size

Number of panels

Battery capacity

Yearly energy production

Cost & payback period

Environmental savings

🌍 Why Latitude & Longitude?
Latitude → north/south position from the equator.

Longitude → east/west position from the prime meridian.

They pinpoint your exact location so the calculator can fetch accurate solar data.

🏆 Use Case
Homeowners exploring solar

Students learning renewable energy

Hackathon/demo projects

📜 License
MIT License. Free to use and modify.

🙌 Credits
NASA POWER API – solar irradiance data

OpenWeatherMap – weather data

Chart.js – interactive graphs

vbnet
Copy code
