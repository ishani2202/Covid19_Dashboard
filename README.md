
# COVID-19 Dashboard 🦠📊

Welcome to the **COVID-19 Dashboard**, an interactive web app built using **Streamlit** and **Plotly**. This dashboard provides real-time insights into the COVID-19 pandemic, allowing users to explore global and country-specific statistics in a visually appealing and easy-to-understand format.

### 🌟 Key Features:
- **Real-Time Data**: View live COVID-19 stats for countries worldwide including **confirmed cases**, **deaths**, and **recoveries**.
- **Interactive Filters**: Select your country, the year, and moving average window to tailor the data.
- **Engaging Visualizations**: Enjoy dynamic **choropleth maps**, **pie charts**, and **line charts** that highlight key trends and global hotspots.
- **Worldwide Overview**: Get a global summary of the pandemic and track daily cases and deaths.

### 🚀 Live Demo:
Check out the live version of the dashboard [here](https://covid19dashboardx.streamlit.app/) 

### 💻 Technologies Used:
- **Streamlit**: For creating the interactive web interface.
- **Plotly**: For generating interactive, visually rich charts.
- **Pandas**: For data processing and manipulation.
- **PyCountry**: For mapping country names to ISO country codes.

### 🛠️ Prerequisites:
Make sure you have the following before running the app:
- Python 3.7 or higher
- Streamlit, Plotly, Pandas, and PyCountry libraries installed

### 📥 Installation:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/covid19-dashboard.git
   cd covid19-dashboard
   ```

2. **Set up a virtual environment** (recommended):
   ```bash
   python -m venv env
   source env/bin/activate   # For Linux/macOS
   .\env\Scriptsactivate    # For Windows
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**:
   Start the dashboard locally by running:
   ```bash
   streamlit run dashboard.py
   ```

5. Open your browser and visit the app at `http://localhost:8501`.

### 🧰 Configuration:
- Customize the dashboard’s theme and layout via the `.streamlit/config.toml` file.
- Adjust the title, page icon, and layout options to fit your preferences.

### 🌍 Data Source:
This dashboard uses the data from the [CSSEGISandData COVID-19 dataset](https://github.com/CSSEGISandData/COVID-19), which provides time-series data for COVID-19 cases, deaths, and recoveries globally and by country.

### 📸 Screenshots
![image](https://github.com/user-attachments/assets/dbb0065b-5e06-403b-bc86-05ef20c230a2)

---

### 📝 License:
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

Enjoy exploring the COVID-19 Dashboard! 🚀🌍

