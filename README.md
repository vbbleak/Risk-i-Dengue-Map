# Risk-i Dengue Risk Mapping App

Risk-i is an interactive web-based application designed to help users identify, document, and share dengue risk locations using a map interface. Originally built as a local demo, Risk-i can be hosted on a simple Node.js server and accessed from any device on the same network.

## Features

* 🌙 **Enhanced Dark Mode** with premium gradients, smooth animations, and comprehensive UI coverage
* 🖱️ **Customizable Cursors** with 6 different styles and persistent settings
* 📍 **Interactive Leaflet map** with street, satellite, and terrain views
* ♿ **Accessibility Features** with ARIA labels, keyboard navigation, and screen reader support
* 🧭 **Search & navigation** (including current location tracking)
* 🛠️ **Add / edit / delete markers** with description, photo (URL or upload)
* 📁 **LocalStorage persistence** keeps markers between sessions
* 🔄 **Responsive design** optimized for desktop, tablet, and mobile
* 📊 **Risk-level information** and integrated educational content
* 🌐 **Network sharing** – run on a local server and access via phone or other devices

## Getting Started

1. Clone or download the repository:
   ```bash
   git clone https://github.com/vbbleak/Risk-i.git
   cd Risk-i
   ```
2. Install Node.js if you haven't already (version 14+ recommended).
3. Start the server:
   ```bash
   node app.js
   ```
4. Open `http://localhost:8080` in your browser, or use another device on the same network:
   ```
   http://<your-ip-address>:8080
   ```

## Usage

* Click on the map to select a location before submitting the form.
* Provide a name, choose a risk level (predefined descriptions will auto-fill), add optional info or upload/take a photo, then click **Add Marker**.
* Click a marker to view its details; use **Edit** to update or **Delete** to remove.
* Use the **Satellite** button in the lower-left corner to toggle between street, satellite, and terrain views.
* **Dark Mode**: Click the moon/sun icon in the header to toggle between light and dark themes (preference is saved).
* **Cursor Customization**: Use the dropdown in the header to choose from 6 different cursor styles (preference is saved).
* **Sidebar Toggle:** Click the chevron button to collapse/expand the sidebar (state is remembered)
* **Keyboard Navigation:** Use arrow keys to pan, +/- to zoom, Home to reset view
* Markers are stored locally in the browser; clearing browser storage will erase them.

## Deployment

For wider access, deploy Risk-i to a cloud provider or enable port forwarding/VPN and update `app.js` to listen on the appropriate interface/port.

## License

This project is open-source; include your preferred license details here (e.g., MIT).

## Credits

Built with [Leaflet](https://leafletjs.com/), [Chart.js](https://www.chartjs.org/), and other open-source libraries. Designed as an educational tool to raise awareness about dengue risks.

---
*Project created by Mary (GitHub: [vbbleak-create](https://github.com/vbbleak-create))*

