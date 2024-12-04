# Solar Tracker Simulation

## Setup Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/solar-tracker-simulation.git
    ```

2. Install dependencies:
    - For **Node.js**:
      ```bash
      npm install
      ```
    - For **Python**:
      ```bash
      pip install -r requirements.txt
      ```

3. Run the simulation:
    - For **Node.js (Web-based Simulation)**:
      ```bash
      npm start
      ```
    - For **Python (Backend API)**:
      ```bash
      python app.py
      ```

4. Access the simulation interface at:
    - **Web UI**: Open `http://localhost:3000` in your browser.
    - **API Documentation**: Visit `http://localhost:3000/docs`.

## Dependencies

- **Three.js**: For 3D rendering and visualization.
- **dat.GUI**: For UI controls and interaction.
- **Chart.js**: For performance analysis charts.
- **Node.js**: Backend for real-time data fetching.

## How it Works
The solar tracker simulation consists of a 3D model of solar panels that move based on the time of day, sun’s position, and weather conditions. It is integrated with a performance dashboard for real-time metrics.
