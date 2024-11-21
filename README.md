# 🗺️ Audit Map Application

A web-based application for planning and visualizing audit routes with interactive Google Maps integration.

## 📋 Features

- **Interactive Map**: Visualize locations with custom markers (A, B, C...)
- **Dynamic Route Planning**: Calculate optimal routes between selected locations
- **Travel Time Calculation**: Display and sum up travel times between locations
- **Flexible Input**: Add/remove locations dynamically with name and address
- **Route Optimization**: Automatically calculate the best route between selected points
- **Visual Feedback**: Click markers to see location details
- **Easy Reset**: Clear all data with a single click

## 🚀 Getting Started

### Prerequisites

- Google Maps JavaScript API key

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/audit-map.git
```

2. Replace `YOUR_API_KEY` in the HTML file with your Google Maps API key:

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=initMap" async defer></script>
```

3. Open `index.html` in your web browser

## 🎯 Usage

1. **Add Locations**:
   - Click "Add Row" to add new location entries
   - Enter name and address for each location
   - Address will be automatically geocoded when you leave the input field

2. **Plan Route**:
   - Select checkboxes for locations you want to include
   - Click "Calculate Route" to generate the optimal path
   - Markers will show the order (A, B, C...)
   - Travel times will be displayed and totaled

3. **Reset**:
   - Click the reset button (↻) to clear all data and start fresh

## 🛠️ Technical Details

- Built with vanilla JavaScript
- Uses Google Maps JavaScript API
- Implements:
  - Geocoding
  - Directions Service
  - Custom Markers
  - InfoWindows
  - Route Optimization

## 🎨 Customization

You can customize the appearance by modifying the CSS variables in the style section:
- Map dimensions
- Color scheme
- Font styles
- Layout spacing

## ⚠️ Important Notes

- Requires a valid Google Maps API key
- API key must have the following services enabled:
  - Maps JavaScript API
  - Geocoding API
  - Directions API

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details

## 👨‍💻 Author

Made with ❤️ by Massimo Olivieri 🪂