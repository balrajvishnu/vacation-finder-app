# 🗺️ Vacation Finder & Planner

An AI-powered Streamlit application that helps you find travel deals and create detailed vacation itineraries with personalized recommendations.

## ✨ Features

- **🔍 Travel Deal Search**: Searches for the best travel deals from your starting location to any destination
- **📅 Smart Itinerary Planning**: Generates detailed day-by-day vacation plans with optimized routes
- **🍽️ Restaurant Recommendations**: Suggests highly-rated Indian, Thai, and Mexican restaurants (or customized preferences)
- **🏨 Hotel Suggestions**: Recommends hotels around $200/night with great reviews and free breakfast
- **💬 Vacation Assistant**: Interactive chatbot to answer questions about places, distances, and travel tips
- **📄 Export Options**: Download your vacation plan as a DOCX document

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/balrajvishnu/vacation-finder-app.git
   cd vacation-finder-app
   ```

2. **Set up environment variables:**
   Create a `.streamlit/secrets.toml` file or set environment variables:
   ```toml
   OPENAI_API_KEY = "your_openai_api_key_here"
   SERP_API_KEY = "your_serpapi_key_here"
   ```

   Or set environment variables:
   ```bash
   export OPENAI_API_KEY="your_openai_api_key_here"
   export SERP_API_KEY="your_serpapi_key_here"
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app:**
   ```bash
   streamlit run vacation_finder_planner.py
   ```

## ☁️ Deployment on Streamlit Cloud

1. Push this repository to your GitHub account
2. Go to [Streamlit Community Cloud](https://share.streamlit.io/)
3. Click "**New app**" and select this repository
4. Set the main file path to: `vacation_finder_planner.py`
5. In "**Secrets**", add:
   ```toml
   OPENAI_API_KEY = "your_openai_api_key_here"
   SERP_API_KEY = "your_serpapi_key_here"
   ```
6. Click "**Deploy!**"

## 📋 Requirements

- Python 3.7+
- OpenAI API key
- SerpAPI key (for travel deal search)
- See `requirements.txt` for Python package dependencies

## 🎯 Usage

1. Enter your starting location (city or airport)
2. Enter your destination (or leave blank for "anywhere")
3. Select your travel dates and number of days
4. Add any preferences (cruise, city, nature, food, etc.)
5. Click "Find & Plan Vacation" to generate your personalized itinerary
6. Use the "Vacation Assistant" tab to ask questions about your trip
7. Download your plan as a DOCX file

## 📝 License

See LICENSE.txt for license information.
