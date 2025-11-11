F1 Analytics

Analyze Formula 1 racing like a pro. This project offers tools to explore driver performance, team comparisons, car behavior, pit strategy, and overall race trends using real F1 datasets.

Whether you're just starting with data analysis or you're scaling up for deep competitive insights, this package helps you load data, run custom analytics, and create clean visualizations.

🚗 Features

Driver performance tracking
Lap times, position changes, session consistency.

Team and car comparisons
Pace, reliability, sector strengths, and seasonal trends.

Race trend analysis
Pit windows, tire strategies, stint pace evolution.

Visualization tools
Speed charts, pit stop overlays, lap-time deltas.

Flexible data loading
Works with CSV files or online datasets depending on configuration.

📦 Installation
1. Clone the repository
git clone https://github.com/your-username/f1-analytics.git
cd f1-analytics

2. Install dependencies

Make sure you have Python 3.9+ installed.

pip install -r requirements.txt

3. (Optional) Create a virtual environment
python -m venv venv


Activate it:

macOS/Linux

source venv/bin/activate


Windows

venv\Scripts\activate

🏁 How to Run the Project
1. Prepare Your Data

Place your datasets inside the data/ folder.

Common files include:

race_results.csv
lap_times.csv
drivers.csv
constructors.csv

2. Run Basic Analyses
Analyze driver performance
python analyses/analyze_driver.py --driver "Lewis Hamilton"

Compare two teams
python analyses/compare_teams.py --team1 Mercedes --team2 Ferrari

3. Run Visualizations
python visualizations/visualize_lap_times.py --race "Italian GP"


Plots are saved automatically in the outputs/ folder.

📂 Project Structure
f1-analytics/
│
├── data/                 # Raw & cleaned datasets
├── scripts/              # Data parsers & utilities
├── analyses/             # Core analysis modules
│   ├── analyze_driver.py
│   └── compare_teams.py
│
├── visualizations/       # Plotting utilities
│   └── visualize_lap_times.py
│
├── outputs/              # Auto-generated plots/reports
├── requirements.txt      # Dependencies
└── README.md             # Documentation

🧪 Example Analyses You Can Run

Find the fastest driver in a race

Compare qualifying pace vs race pace

Analyze overtake patterns and pit timing

Evaluate car consistency over a season

Study sector-level performance

🧩 Contributing

Pull requests are welcome!

If you'd like to add:

new metrics

new visualization types

support for new datasets

please open an issue first so we can discuss the idea.

📜 License

This project is released under the MIT License.
