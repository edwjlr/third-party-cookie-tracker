# Third-Party Cookie Tracker

## Overview
This project is a Google Chrome extension that tracks and logs third-party cookies from websites. It provides insights into how third-party cookies are used for tracking user activities online.

## Features
- Tracks third-party cookies from websites in the current tab.
- Provides a user-friendly interface to display cookie data.
- Logs cookies using Chrome's `cookies` API.
- Includes icons and UI for seamless extension integration.

## Files
- **`manifest.json`**: Configuration file for the Chrome extension.
- **`popup.html`**: Frontend of the Chrome extension's popup interface.
- **`popup.js`**: JavaScript to handle interactions within the popup.
- **`background.js`**: Manages background tasks and handles cookie retrieval.

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/edwjlr/third-party-cookie-tracker.git
   cd third-party-cookie-tracker
   ```
2. Open Google Chrome and navigate to `chrome://extensions`.
3. Enable **Developer Mode**.
4. Click **Load unpacked** and select the project folder.

## Screenshots
![Extension UI](images/icon128.png)

## Documentation
For a detailed explanation, read the [Third Party Cookies and Online Privacy](./docs/Third%20Party%20Cookies%20and%20Online%20Privacy.txt).

## Challenges
- Limited cross-domain cookie access due to Chrome API restrictions.
- Upcoming deprecation of third-party cookies by browsers like Google Chrome.

## Future Features
- Tracking pixel detection.
- Browser fingerprinting analysis.
- Ultrasound cross-device tracking detection.

## License
This project is licensed under the MIT License.
