# 🌍 Where Am I? - Location & Multi-Neighbour Finder App

This web application identifies your current location and provides detailed information about your country and all its neighboring countries. It leverages the Geolocation API to get your position, reverse geocodes your coordinates into a human-readable address, and fetches country data from a REST API, including information about multiple neighboring countries.

## 📋 Features

- **Geolocation:** Retrieves the user's latitude and longitude using the Geolocation API.
- **Reverse Geocoding:** Converts geographic coordinates into a readable location (city, country) with BigDataCloud's Reverse Geocoding API.
- **Country & Multi-Neighbour Information:** Displays country information, including:
  - Flag
  - Population
  - Language
  - Currency
  - All Neighboring Countries
- **Error Handling:** Manages potential errors such as location access denial or API failures and displays appropriate error messages.

## 🚀 Getting Started

### Prerequisites

You only need a web browser to run this application.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/where-am-i-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd where-am-i-app
   ```
3. Open the `index.html` file in your web browser.

### Usage

1. Click the "Find My Location" button.
2. Allow the browser to access your location.
3. View detailed information about your current country and all neighboring countries.

## 🛠️ Technologies Used

- **JavaScript (ES6+):** Core programming language used to build the app.
- **Fetch API:** For making asynchronous requests to the reverse geocoding and country data APIs.
- **Geolocation API:** To obtain the user's current geographic location.
- **BigDataCloud Reverse Geocoding API:** For converting geographic coordinates into a readable address.
- **REST API for Country Data:** Provides detailed information about the country and its neighbors based on its name.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/where-am-i-app/issues) if you have any suggestions or find any bugs.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

## 📧 Contact

For any inquiries or questions, please reach out to [nakulk2003@gmail.com](mailto:your-email@example.com).
