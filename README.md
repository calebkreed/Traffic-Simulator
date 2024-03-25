# Traffic-Simulator

## Feature Wish-List

- Customizable Maps
  - Pre-built Templates
  - Potential Maze Gen?
  - Real Life City Blocks
  - Suburbs, City Centers
- Data Visualization
  - Average Speed
  - Congestion Levels
  - Customizable Reports
- Traffic Simulation Control
  - Traffic Signal Timing
  - Driving Behaviors
  - Crash Response Simulation

## File Tree

```
traffic-simulator/
│
├── backend/                  # All backend-related files
│   ├── app/                  # Flask application
│   │   ├── __init__.py       # Initializes Flask app
│   │   ├── routes.py         # Defines routes for your API
│   │   └── simulation/       # Simulation logic
│   │       ├── __init__.py
│   │       └── simulator.py  # Core simulation logic
│   │
│   ├── tests/                # Tests for your backend code
│   │   └── test_simulator.py
│   │
│   ├── requirements.txt      # Python dependencies
│   └── run.py                # Entry point to run the Flask app
│
├── frontend/                 # All frontend-related files
│   ├── src/                  # Source files for the frontend
│   │   ├── js/               # JavaScript files
│   │   │   └── app.js        # Main JS file for the app
│   │   ├── css/              # CSS files
│   │   │   └── style.css     # Main stylesheet
│   │   └── index.html        # Entry HTML file
│   │
│   ├── assets/               # Static assets like images, fonts, etc.
│   │
│   └── package.json          # Node.js project manifest
│
├── .gitignore                # Specifies intentionally untracked files to ignore
├── README.md                 # Project overview and setup instructions
└── LICENSE                   # The license for your project
```

## Car Class

- Greedy Algorithm
