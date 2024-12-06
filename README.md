# 🚗 Real-Time Traffic Flow Analysis

**Real-Time Traffic Flow Analysis** is a web-based application built using Streamlit and Folium. It visualizes real-time traffic flow and congestion levels between specified start and end locations.

## Features
- Enter start and end locations to visualize traffic routes.
- Automatically detect and use the user's current location (with browser permissions).
- Generate a heatmap overlay to show simulated traffic congestion.
- Display route details and traffic congestion levels.

---

## 🛠️ Installation

Follow the steps below to set up the application on your local machine.

### 1. Clone the Repository
```bash
git clone https://github.com/SubhashGovindharaj/Geoplotting.git
cd Geoplotting

2. Install Required Packages
Run the following command to install the necessary Python packages:

bash
Copy code
pip install streamlit folium streamlit-folium openrouteservice numpy geopy
3. Get an OpenRouteService API Key
Sign up at OpenRouteService.
Obtain an API key from your account.
Replace the API_KEY in the code with your key.
🚀 Running the Application
To launch the application, use the following command:

bash
Copy code
streamlit run main.py
If the streamlit command is not recognized, try:

bash
Copy code
python -m streamlit run main.py
📚 Usage Instructions
Start the application by running the above command.
Enter the Start Location and End Location in the sidebar.
(Optional) Click Use My Current Location to auto-detect your location (requires browser permission).
View the traffic route and congestion heatmap on the main page.
🖥️ Requirements
Python 3.8+
A working internet connection
OpenRouteService API Key
