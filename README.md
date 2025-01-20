# Weather App

This is a **Weather Application** built using **JavaScript**, **HTML**, and **CSS**. The app allows users to fetch and display real-time weather information for any city worldwide.

## Features
- **Real-time Weather Data**: Fetch current weather data using an API.
- **Search Functionality**: Search for weather details by city name.
- **Responsive Design**: Optimized for various screen sizes.
- **Dynamic UI**: Weather icons, temperature, and descriptions update dynamically.

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **API Integration**: OpenWeatherMap API (or any weather API of choice)
- **Styling**: CSS with Flexbox and animations

## Installation & Setup
To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/venujaranasinghe/weather-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```

3. Open the `index.html` file in your browser:
   ```
   open index.html
   ```

4. Add your API key:
   - Sign up on [OpenWeatherMap](https://openweathermap.org/) and get a free API key.
   - Add the API key to the `main.js` file:
     ```javascript
     const API_KEY = 'your_api_key_here';
     ```

## Folder Structure
```
├── index.html
├── css
│   └── styles.css
├── js
│   └── main.js
├── images
│   └── (Optional assets like weather icons)
```

## Future Enhancements
- Add 7-day weather forecast functionality.
- Display additional weather parameters like wind speed and humidity.
- Improve UI/UX with more animations and themes.

## Deployment
This app can be deployed to any static hosting platform, such as:
- **GitHub Pages**
- **Netlify**
- **Vercel**

### Deploying to GitHub Pages
1. Commit and push your code to a GitHub repository.
2. Go to the repository settings.
3. Enable GitHub Pages under the **Pages** section.
4. Set the branch to `main` (or your default branch) and the folder to `/root`.
5. Save, and your app will be live at `https://venujaranasinghe.github.io/weather-app/`.

## Feedback
If you have suggestions or encounter issues, feel free to open an issue in this repository or contact me.

## License
This project is licensed under the [MIT License](LICENSE).

---

Thank you for exploring the Weather App!
