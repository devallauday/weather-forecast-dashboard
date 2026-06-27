# 🌤️ Weather App with Search History

A beautiful, fully functional weather application that displays real-time weather data with a built-in search history tracker. The app automatically saves your searches and allows you to quickly revisit any city's weather.

## ✨ Features

### 🌤️ Weather Display
- Real-time temperature (Celsius)
- Weather description with emoji icons
- Humidity percentage
- Wind speed (km/h)
- Atmospheric pressure (hPa)
- City and country display

### 📋 Search History Tracker
- Auto-save every search
- Persistent storage using localStorage
- Timestamps (Just now, 5m ago, Yesterday)
- Click any history item to re-search
- Remove individual items with ✕ button
- Clear all history with confirmation
- Shows total search count
- Maximum 20 saved items

### 🎨 User Interface
- Modern gradient design
- Smooth animations and transitions
- Fully responsive (mobile/tablet/desktop)
- Loading states
- User-friendly error messages
- Hover effects on interactive elements

### 📍 Location Features
- Automatic location detection
- Smart fallback to London if location denied

## 🚀 Quick Start

### Method 1: Direct Download
1. Download `weather-app.html`
2. Double-click to open in browser
3. Start searching!

### Method 2: Create File
1. Open Notepad (Windows) or TextEdit (Mac)
2. Copy the complete code
3. Save as `weather-app.html`
4. Double-click to open

### Method 3: Online Editor
1. Go to [CodePen](https://codepen.io/pen/)
2. Paste the code
3. Run immediately

## 📖 How to Use

### Searching for Weather
1. Type a city name (e.g., "New York", "Tokyo", "Paris")
2. Click **Search** or press **Enter**
3. Weather information appears instantly

### Using Search History
1. **View** - Scroll down to see history
2. **Re-search** - Click any city name
3. **Remove** - Click ✕ on any item
4. **Clear all** - Click "Clear All" and confirm

### Understanding Timestamps
- **"Just now"** - Less than 1 minute ago
- **"5m ago"** - Minutes ago
- **"2h ago"** - Hours ago
- **"Yesterday"** - Within last 48 hours
- **Date format** - Older than 2 days

## 🛠️ Technical Details

### Architecture
- 100% client-side - No server required
- Single HTML file - All CSS and JavaScript included
- No dependencies - No external libraries
- API: [wttr.in](https://wttr.in/) (Free, no API key)

### Storage
```json
{
  "storageKey": "weatherSearchHistory",
  "data": [
    {
      "city": "New York, US",
      "timestamp": "2026-06-27T10:30:00.000Z"
    }
  ]
}
