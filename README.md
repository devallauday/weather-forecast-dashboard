weather-app.html
├── <!DOCTYPE html>
├── <head>
│   ├── <meta> tags (viewport, charset)
│   ├── <title>Weather App with Search History</title>
│   └── <style>
│       ├── Global styles
│       ├── Container styles
│       ├── Search box styles
│       ├── History section styles
│       ├── Weather display styles
│       ├── Error/Loading styles
│       └── Responsive styles
├── <body>
│   ├── <div class="container">
│   │   ├── <h1>Weather App</h1>
│   │   ├── <div class="search-box">
│   │   │   ├── <input> city input
│   │   │   └── <button> search button
│   │   ├── <div class="history-section">
│   │   │   ├── <div class="history-header">
│   │   │   │   ├── <h3>Search History</h3>
│   │   │   │   ├── <button> refresh
│   │   │   │   └── <button> clear all
│   │   │   └── <div id="history-list">
│   │   │       └── History items (dynamic)
│   │   ├── <div class="loading"> loading state
│   │   ├── <div id="weather-info">
│   │   │   ├── <div class="weather-icon">
│   │   │   ├── <h2>city name
│   │   │   ├── <p>temperature
│   │   │   ├── <p>description
│   │   │   └── <div class="details">
│   │   │       ├── Humidity
│   │   │       ├── Wind speed
│   │   │       └── Pressure
│   │   └── <div id="error-message">
│   └── <script>
│       ├── SearchHistory class
│       ├── Weather fetching functions
│       ├── Display functions
│       ├── Event listeners
│       └── Initialization
└── </html>
