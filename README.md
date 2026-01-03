# 🌡 Temperature Converter (°C ⇄ °F)

A beautifully styled, browser-based temperature converter that goes beyond basic Celsius ↔ Fahrenheit conversion.

Includes **Dew Point (aka “dew index”)**, **Heat Index**, and **Humidex** calculations using optional relative humidity — all in a single, dependency-free HTML file.

Made with ❤️ by **[DILLIGAF.FYI](https://dilligaf.fyi)**

---

## ✨ Features

- 🔁 **Celsius ⇄ Fahrenheit** conversion
- 💧 **Dew Point** calculation (Magnus approximation)
- 🔥 **Heat Index** (NOAA-style “feels like” temperature)
- 🌫 **Humidex** (Environment Canada model)
- 🧠 Simple **comfort notes** based on dew point
- 🎨 Clean, modern dark UI with subtle glow
- ⚡ Instant results, no page reloads
- 🧩 Single-file, zero dependencies
- 🔒 Runs entirely in your browser (no tracking, no data collection)

---

## 🚀 How to Use

### Option 1: Use it online (GitHub Pages)
If GitHub Pages is enabled for this repo, open the Pages URL and start converting instantly.

### Option 2: Run locally
1. Download or clone this repository
2. Open `index.html` in any modern browser
3. Enter a temperature
4. (Optional) Enter relative humidity
5. Click **Convert**

That’s it.

---

## 🧪 What the numbers mean

### 🌡 Temperature
Standard Celsius (°C) and Fahrenheit (°F) conversion.

### 💧 Dew Point
The temperature at which air becomes saturated and moisture begins to condense.
A great indicator of how “muggy” the air feels.

General guide:
- `< 10°C` → Dry / comfortable  
- `10–16°C` → Comfortable  
- `16–18°C` → Slightly humid  
- `18–21°C` → Humid  
- `> 21°C` → Very humid / oppressive  

### 🔥 Heat Index
“How hot it feels” when humidity is factored in.  
Best suited for **warm temperatures** and **higher humidity**.

### 🌫 Humidex
A Canadian-developed comfort index based on dew point.
Commonly used to describe perceived heat in hot, humid conditions.

---

## 🧮 Formulas Used

**Celsius ⇄ Fahrenheit**
