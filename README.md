# ETL-Pipeline-Project
Develop a pipeline that extracts data from social media APIs (e.g., Twitter, Facebook) performs sentiment analysis on customer feedback, transforms the data for insights, and loads it into a PostgreSQL database

## Setup Instructions

1. **Environment Setup**:
   - Ensure Python 3.8+ is installed.
   - Create a virtual environment: `python3 -m venv sa_env` and activate it.
   - Install required dependencies: `pip install -r requirements.txt` (create this file based on provided packages).

2. **Database Configuration**:
   - Install PostgreSQL and create a database named `sentiment_analysis`.
   - Update `database.py` with your PostgreSQL credentials.

3. **API Credentials**:
   - Obtain Twitter API credentials and update `twitter.py` accordingly.

4. **Running the Project**:
   - Execute `main.py` to start the data extraction, analysis, and visualization process.

## How to Use

- Update search keywords or parameters as needed in `main.py` or the respective data extraction scripts.
- Run `main.py` to execute the entire pipeline or individual scripts for specific tasks.

## Contributing

We welcome contributions! Please read `CONTRIBUTING.md` for how to contribute to this project.

## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments

- Thanks to the developers and contributors of Tweepy, NLTK, TextBlob, and other used libraries.
