# Natural Language Processing | Final Exam

## Description
This project aims at developing a proof-of-concept NLP application based on Spotify reviews data obtained from [Kaggle](https://www.kaggle.com/datasets/mfaaris/spotify-app-reviews-2022/data).
This repository should be read in conjunction with the respective report.

## Structure
The src folders contain the necessary jupyter notebooks which contain the code to execute the analysis.

## Instructions
Please follow these steps to properly set up the repository:
* Create a virtual environment, activate it, and run install the dependencies:
```bash
python -m venv .venv
```
```bash
pip3 install -r requirements.txt
```
```bash
source .venv/bin/activate

```
Please note: Depending on your local setup, you might need to use `pip` instead of `pip3`.

* Duplicate `template.env`, rename to `.env` and add private OpenAI API key. Do not change the name of the environment variable.

* If not available yet, add a folder called `data` to the base repository and download the `spotify_reviews.csv` file in there.