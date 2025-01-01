// Initialize the map and set its view to a specific location and zoom level
const map = L.map('map').setView([29.7063, 52.1147], 12);

// Add the OpenStreetMap tile layer
L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '© OpenStreetMap'
}).addTo(map);

// Add a marker to the map
L.marker([29.7063, 52.1147]).addTo(map)
    .bindPopup('Shiraz, Iran')
    .openPopup();
