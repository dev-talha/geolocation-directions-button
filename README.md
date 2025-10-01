# Get Directions Web App

A simple web app that allows users to get Google Maps directions from their current location to your business location.  

## Features
- Uses the browser's Geolocation API to get the user's current location.
- Opens Google Maps directions in a new tab.
- Works on modern browsers that support Geolocation.
- Easy to set your business location.

## User Guide

1. **Open the App**
   - Open `index.html` in a modern browser (Chrome, Firefox, Edge, Safari).

2. **Set Your Business Location**
   - Open `index.html` in a code editor.
   - In the `<script>` section, set your business coordinates:
     ```javascript
     // Set destination coordinates as variables
     var destinationLat = 37.7565566;  // Your business latitude
     var destinationLng = -121.4642229; // Your business longitude
     ```

3. **Get Directions**
   - Click the **"Get Directions"** button.
   - Allow the browser to access your location when prompted.
   - A new tab will open with Google Maps directions from your current location to your business.

> **Note:** Users must allow location access for the functionality to work.  

## License
This project is licensed under the MIT License.
