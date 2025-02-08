# MapFit

MapFit is a feature-enhanced reconstruction of the Mapty project by Jonas Schmedtmann. This web application allows users to track their workouts on an interactive map and includes the additional functionality to delete workouts, giving users greater control over their workout logs.

---

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Future Improvements](#future-improvements)
- [Acknowledgments](#acknowledgments)

---

## Features

- Log workouts with location data (running, cycling, etc.).
- View workouts on an interactive map powered by Leaflet.
- Automatically calculate distance, duration, and pace/speed based on user inputs.
- Delete individual workouts with ease.
- Persistent data storage using the browser’s local storage.

---

## Getting Started

### Prerequisites

Ensure you have the following installed on your system:

- A modern web browser (e.g., Chrome, Firefox, Edge).
- A code editor (optional for customization; e.g., VS Code).

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/SaifAbdelrazek011/mapfit.git
   ```

2. Navigate to the project directory:
   ```bash
   cd mapfit
   ```

3. Open the `index.html` file in your browser to launch the app:
   ```bash
   open index.html
   ```

### Demo

Check out the live demo of the application here: [MapFit Demo](https://dar-snake.github.io/MapFit/)

---

## Usage

1. Open the application in your browser.
2. Click on the map to add a workout.
3. Fill in the workout details (type, distance, duration, etc.) and submit the form.
4. View the workout details displayed on the map and in the sidebar.
5. To delete a workout, click the delete button next to the workout entry in the sidebar.

---

## Technologies Used

- **HTML5**: Structuring the application’s layout.
- **CSS3**: Styling the user interface.
- **JavaScript (ES6)**: Implementing application logic.
- **Leaflet.js**: Rendering interactive maps.
- **Local Storage**: Storing workout data persistently.

---

## Future Improvements

- Add the ability to edit workouts.
- Enhance the UI for better accessibility and responsiveness.
- Integrate user authentication for personalized data.
- Add graphs to visualize workout trends over time.
- Implement synchronization with external fitness apps or devices.

---

## Acknowledgments

- Jonas Schmedtmann for the original **Mapty** project, which served as the foundation for this project.
- [Leaflet.js](https://leafletjs.com/) for providing an intuitive library for interactive maps.

---

## License

This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed.

