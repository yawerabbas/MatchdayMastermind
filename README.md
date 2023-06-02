# MatchdayMastermind

This project evaluates the performance of two football teams, Manchester City and Inter Milan, based on player performance, team strategies, and past records. It utilizes web scraping techniques to gather data from various sources and applies evaluation algorithms to determine the better team.

## Features

- Scrape player performance data from [fbref.com](https://fbref.com/) to evaluate individual player contributions.
- Evaluate team strategies based on formation and playing style.
- Analyze past records including wins, draws, and losses to assess team performance.
- Consider head-to-head results for a comprehensive evaluation.
- Visualize data using bar plots and football field diagrams.

## Setup

1. Clone the repository:

git clone https://github.com/your-username/football-team-evaluation.git

2. Install the required libraries:

pip install requests
pip install beautifulsoup4
pip install pandas
pip install seaborn
pip install matplotlib


3. Run the main Python script:

python prediction.py


## Results

The evaluation algorithm assigns scores to each team based on player performance, team strategies, and past records. The team with the higher score is considered the better team. The final prediction will be displayed in the console.

## Credits

- [fbref.com](https://fbref.com/) - Data source for player performance and head-to-head results.
- [uefa.com](https://www.uefa.com/) - Data source for head-to-head results.

## License

This project is licensed under the [MIT License](LICENSE).

