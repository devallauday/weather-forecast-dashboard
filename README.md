# 🌤️ Weather App with Search History

A beautiful, fully functional weather application that displays real-time weather data with a built-in search history tracker. The app automatically saves your searches and allows you to quickly revisit any city's weather.

![Weather App Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=Weather+App+Screenshot)

## ✨ Features

### 🌤️ Weather Display
- Real-time temperature (Celsius)
- Weather description with emoji icons
- Humidity percentage
- Wind speed (km/h)
- Atmospheric pressure (hPa)
- City and country display
- Weather condition icons

### 📋 Search History Tracker
- **Auto-save** - Every search is automatically saved
- **Persistent storage** - Uses browser localStorage (survives browser restarts)
- **Timestamps** - Shows when you searched ("Just now", "5m ago", "Yesterday")
- **Quick re-search** - Click any history item to search again
- **Individual removal** - Remove specific cities with ✕ button
- **Clear all** - Clear entire history with confirmation
- **History count** - Shows total number of saved searches
- **Max 20 items** - Prevents storage bloat

### 🎨 User Interface
- Modern gradient design
- Smooth animations and transitions
- Responsive layout (works on mobile/tablet/desktop)
- Loading states
- Error handling with user-friendly messages
- Hover effects on interactive elements

### 📍 Location Features
- **Automatic location detection** - Requests geolocation permission
- **Smart fallback** - Defaults to London if location is denied or unavailable

## 🚀 Quick Start

### Method 1: Direct Download
1. Download `weather-app.html`
2. Double-click to open in your browser
3. Start searching!

### Method 2: Create File Manually
1. Open Notepad (Windows) or TextEdit (Mac)
2. Copy the complete code from this repository
3. Paste into the editor
4. Save as `weather-app.html`
5. Double-click to open

### Method 3: Online Editor
1. Go to [CodePen](https://codepen.io/pen/) or [JSFiddle](https://jsfiddle.net/)
2. Paste the code
3. Run and use immediately

## 📖 How to Use

### Searching for Weather
1. Type a city name in the search box (e.g., "New York", "Tokyo", "Paris")
2. Click the **Search** button or press **Enter**
3. Weather information appears instantly

### Using Search History
1. **View history** - Scroll down to see your search history
2. **Re-search** - Click any city name in the history list
3. **Remove** - Click the ✕ button on any history item
4. **Clear all** - Click "Clear All" and confirm

### Understanding Timestamps
- **"Just now"** - Less than 1 minute ago
- **"5m ago"** - Minutes ago
- **"2h ago"** - Hours ago
- **"Yesterday"** - Within last 48 hours
- **Date format** - Older than 2 days (e.g., "6/27/2026")

## 🛠️ Technical Details

### Architecture
- **100% client-side** - No server required
- **Single HTML file** - All CSS and JavaScript included
- **No dependencies** - No external libraries needed
- **API:** [wttr.in](https://wttr.in/) (Free, no API key required)

### Storage
- **Local Storage Key:** `weatherSearchHistory`
- **Data Structure:**
```json
[
  {
    "city": "New York, US",
    "timestamp": "2026-06-27T10:30:00.000Z"
  }
]
