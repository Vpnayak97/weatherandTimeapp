
# 🌤️ Weather + Time App

A simple and beautiful Flask-based web application that shows **real-time weather, local time, and condition** for any city using the [WeatherAPI](https://www.weatherapi.com/). Comes with a sleek frontend UI, background image, blur effects, and quick access city buttons.

---

## 🚀 Features

- 🌍 Fetches current weather and local time by city name
- ⚡ Built using Flask, HTML, CSS & JavaScript
- 🎨 Custom background image with blur effect for clean UI
- 🏙️ Quick-access city buttons (e.g., London, New York, Tokyo)

---

## 📁 Folder Structure

All files are in a **single folder**:

```
📁 your_project_folder
├── app.py              # Flask backend
├── index.html          # Frontend HTML
├── style.css           # CSS styling (linked in HTML)
├── script.js           # JavaScript for fetching data
├── .env                # Stores WeatherAPI key
├── vp.jpg              # Background image
└── README.md           # This file
```

---

## 🛠️ Setup Instructions

1. **Clone or Copy the Project Folder**

2. **Install Required Libraries**  
   Open terminal in the folder and run:

   ```bash
   pip install flask flask-cors python-dotenv requests
   ```

3. **Create a `.env` File**  
   Inside `.env` file, add your API key from [WeatherAPI.com](https://www.weatherapi.com/):

   ```env
   WEATHER_API_KEY=your_api_key_here
   ```

4. **Run the Flask Server**

   ```bash
   python app.py
   ```

5. **Open the App**  
   Open `index.html` directly in your browser (e.g., right-click → Open with Chrome).

---

## 📷 Screenshot

> ![Sample UI](vp.jpg)

---

## 🧠 Notes

- The background image is `vp.jpg`. Make sure it exists in the same folder as your HTML/CSS files.
- No use of Flask's template/static folders. It's a pure front-end/back-end setup in a flat structure.
- Update `background-image` in `style.css` if you move the image elsewhere.

---

## 💡 Example API Endpoint

You can test the API directly:

```
GET http://127.0.0.1:5000/weather?city=Paris
```

---

## 📜 License

MIT License. Free to use and modify.
