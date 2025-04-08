
# ✈️ Flight Tracker & Analysis Android App

A Kotlin-based Android application that tracks real-time flight information using the **AviationStack API**, displays flight details, and embeds **FlightAware** live maps and history. The app also stores flight data using **Room DB** and performs background analysis using **WorkManager**, with a modern dashboard UI built using **Jetpack components**.

---

## 🚀 Features

- 🔍 **Track Real-Time Flights:** Search by flight number and view airline, origin, destination, timing, status, and speed/altitude.
- 🌍 **Flight Map Integration:** Displays live flight map and route using a **WebView** that embeds FlightAware.
- 🗃️ **Flight History Storage:** Saves daily flight data into a local **Room database** for offline access.
- 📊 **Dashboard Analytics:** Periodically calculates and displays:
  - Average flight duration
  - Average delays
  - Flight frequencies
- 🔄 **Background Sync:** Uses **WorkManager** to fetch and update data periodically or on demand.
- ✨ **Modern UI:** Intuitive UI styled like flight tickets with **CardViews**, Material Design, and clean layout.

---

## 🧰 Tech Stack

### 🎯 **Languages & Platform**
- Kotlin
- Android Studio (Gradle + AGP 8.8.0)

### 🧱 **Architecture & Libraries**
- MVVM Architecture
- Jetpack Components: `ViewModel`, `LiveData`, `Room`, `WorkManager`
- WebView (for live map embedding)
- OkHttp (API networking)
- org.json (for JSON parsing)

### 🌐 **APIs Used**
- [AviationStack API](https://aviationstack.com/) – For real-time flight data
- [FlightAware](https://www.flightaware.com/) – For live maps and flight history (via WebView)


---

## ⚙️ Setup Instructions

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/flight-tracker-app.git
   cd flight-tracker-app
