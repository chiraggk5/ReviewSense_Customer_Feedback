# ReviewSense Customer Feedback

ReviewSense cleans customer feedback, assigns sentiment scores, extracts keyword frequencies, and presents the results in a Streamlit dashboard.

## Setup

```text
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

TextBlob may need its language data on a new environment:

```text
python -m textblob.download_corpora
```

## Run the pipeline

Run these commands from this directory:

```text
python module1.py
python module2.py
python module3.py
streamlit run reviewsense_app.py
```

The pipeline reads `ReviewSense_Customer_Feedback_5000.xlsx` and produces the Module 1-3 CSV files used by the dashboard. The `milestone_*.py` scripts and `Milestone*.csv` files are retained as the earlier milestone versions.

## License

This project is licensed under the MIT License.
