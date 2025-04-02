# Hydro-Aether Sentinel

A web-based monitoring system for water quality and environmental parameters in educational institutions.

## Features

- Real-time monitoring of water parameters
  - Temperature
  - Humidity
  - Turbidity
  - TDS (Total Dissolved Solids)
  - Gas Levels
  - Air Quality

- Interactive Dashboard
  - Live data visualization
  - Historical data analysis
  - Location-based monitoring
  - Weather comparison

- Multi-location Support
  - Multiple blocks
  - Different floors
  - Multiple water coolers

## Tech Stack

- Frontend: HTML5, CSS3, JavaScript
- Data Visualization: Chart.js
- Icons: Font Awesome
- HTTP Client: Axios

## Project Structure

```
hydro-aether-sentinel/
├── css/
│   ├── styles.css
│   └── dashboard.css
├── js/
│   ├── dashboard.js
│   └── contact.js
├── index.html
├── dashboard.html
├── data-analysis.html
├── about.html
├── contact.html
└── login.html
```

## Development Requirements

- Node.js 14.x or higher
- NPM 6.x or higher
- Modern web browser
- Text editor (VS Code recommended)

## Environment Setup

1. Create a `.env` file in the root directory:
```env
THINGSPEAK_API_KEY=your_thingspeak_api_key
WEATHER_API_KEY=your_weather_api_key
CHANNEL_ID=your_channel_id
CITY_NAME=your_city_name
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/CodeSasuke/Hydro-Aether-Sentinel-Website.git
```

2. Navigate to the project directory:
```bash
cd Hydro-Aether-Sentinel-Website
```

3. Create and configure environment variables:
   - Copy `.env.example` to `.env`
   - Update the `.env` file with your API keys and configuration

4. Install dependencies (if using npm):
```bash
npm install
```

5. Start the development server:
```bash
npm start
# or using Python's built-in server
python -m http.server 8000
```

6. Access the application at `http://localhost:8000`

## Security Considerations

- Never commit the `.env` file to version control
- Keep API keys private and secure
- Regularly rotate API keys
- Use environment variables for sensitive data
- Enable CORS protection in production

## Deployment

1. Build the project (if using a build system):
```bash
npm run build
```

2. Configure your environment variables on your hosting platform
3. Deploy the built files to your web server

## Browser Compatibility

- Chrome (recommended) v90+
- Firefox v88+
- Safari v14+
- Edge v90+

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Project Link: [https://github.com/CodeSasuke/Hydro-Aether-Sentinel-Website](https://github.com/CodeSasuke/Hydro-Aether-Sentinel-Website)
- Issue Tracker: [GitHub Issues](https://github.com/CodeSasuke/Hydro-Aether-Sentinel-Website/issues)

## Acknowledgments

- [Chart.js](https://www.chartjs.org/)
- [Font Awesome](https://fontawesome.com/)
- [Axios](https://axios-http.com/)