# IPTV Player Web App

IPTV Player Web App is a simple web-based application that allows you to load and play IPTV (Internet Protocol Television) channels from an M3U playlist. You can search for channels, view their details, and easily play them in a built-in video player.
Demo: https://afzafri.github.io/IPTV-Player-Web-App

## Features

- Load IPTV channels from an M3U URL.
- Search for channels within the playlist.
- View channel details with logos.
- Play channels in a user-friendly video player.
- Your M3U playlists URL are automatically saved to your browser local storage and auto load the next time you visit the page.

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Prerequisites

You need a modern web browser and a web server (for serving static files).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/IPTV-Player-Web-App.git
   ```

2. Open the project folder in your code editor.

3. Run a web server, or you can use Python's built-in HTTP server:

    ```bash
   python -m http.server
   ```

4. Open a web browser and access the project by visiting `http://localhost:8000` (or your server's URL).

### Usage

1. Enter the M3U URL of your IPTV playlist in the "Enter M3U URL" input field.

2. Click the "Go" button to load the playlist.

3. You can search for channels by entering keywords in the "Search Channel" input field.

4. Click on a channel in the playlist to start playing it in the video player.

5. Enjoy your favorite IPTV channels!

### Saving M3U URL

- **M3U URL**: If you enter an M3U URL and load the playlist, the URL will be saved to local storage. When you return to the application, the URL will be prepopulated in the input field for your convenience.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [HLS.js](https://github.com/video-dev/hls.js) for enabling HLS video streaming.
- [Bootstrap](https://getbootstrap.com/) for styling and layout.

## Contributing

Feel free to contribute to this project. You can submit issues, feature requests, or pull requests to help improve this IPTV Player Web App.

## Authors

- Afif Zafri