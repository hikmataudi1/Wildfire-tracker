# Wildfire Tracker
### This project is a React web application that tracks wildfires around the world. It utilizes:

NASA Open API: Fetches real-time wildfire data.<br>
Google Maps API: Visualizes fire locations on a map.

<br> 
Features:<br>
View active wildfires on a global map.<br>
Provide an info box for every wildfire<br>


## Getting Started
Clone the repository:<br>
git clone https://github.com/your-username/wildfire-tracker.git

<br>Install dependencies:

cd wildfire-tracker
npm install
Obtain API Keys:

You'll need API keys for both NASA Open API and Google Maps API.
Register for a NASA Open API key at https://api.nasa.gov/index.html.
Create a Google Maps API project and obtain an API key at <a>https://cloud.google.com/docs/authentication/api-keys.</a>
<br>Configure API Keys:

Create a file named .env in the project root directory (ignore this file in version control).

Add the following lines to .env, replacing YOUR_NASA_API_KEY and YOUR_GOOGLE_MAPS_API_KEY with your actual keys:

REACT_APP_NASA_API_KEY=YOUR_NASA_API_KEY
REACT_APP_GOOGLE_MAPS_API_KEY=YOUR_GOOGLE_MAPS_API_KEY
Run the application:<br>
npm start.<br>
Enjoy!
