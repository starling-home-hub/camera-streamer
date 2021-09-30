# camera-streamer
Starling Developer Connect API: Nest Camera Web Streamer Example. Demonstrates connecting to the SDC API, and displaying live
streams of all your cameras. (The SDC streaming API supports 2021 model cameras only.)

This example is compatible with Chrome and Safari (desktop and mobile), but at this time it does not work with
Firefox on desktop, due to incompatibilities between the WebRTC implementations of Firefox and the Nest cameras.

Requires a [Starling Home Hub](https://starlinghome.io) with firmware 10.0 or above.

# Create an SDC API key for this app
1. Go to `setup.starlinghome.io` in your browser
2. Go to the *Starling Developer Connect* section, and make sure the HTTP server is enabled
3. Press *Create New API Key*, and give your key *Read* and *Camera* permissions

# Build and Run
1. `git clone https://github.com/starling-home-hub/camera-streamer.git`
2. `cd camera-streamer`
3. `npm install`
4. Edit `src/components/Streamer.vue`, and add your hub's IP address and API key
5. `npm run serve`
6. Open a web browser, go to `http://localhost:8080` and enjoy!

# Output
The web app shows a grid of all connected Nest cameras, with live video and audio.
