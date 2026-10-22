# AI-Based Phishing Email Detector

**IBM SkillsBuild Cyber Security 2026**  
**Student:** Mohammed Arsalan  
**Project level:** Beginner

## Overview
This educational project trains a simple machine-learning text classifier to label short email messages as `phishing` or `legitimate`. It uses a small synthetic dataset, TF-IDF text features, and Logistic Regression.

## Project files
- `MohammedArsalan_AI_Based_Phishing_Email_Detector.ipynb` — complete notebook, including sample data, training, evaluation, and predictions.
- `requirements.txt` — Python dependencies.
- `MohammedArsalan_ProjectReport.docx` — project documentation and report.
- `README.md` — this guide.

## Dataset
The notebook includes 24 fictional example messages directly in the code, so no external dataset download is required. The examples are for demonstration only and should not be treated as a representative real-world dataset.

## Technologies
- Python 3
- Jupyter Notebook
- pandas
- scikit-learn
- TF-IDF vectorization
- Logistic Regression

## Setup and run

### Option A: Run locally
1. Install Python 3.10 or newer.
2. Download or clone this project folder.
3. Open a terminal in the project folder.
4. Create and activate a virtual environment (recommended):
   - Windows: `python -m venv .venv` then `.venv\Scripts\activate`
   - macOS/Linux: `python3 -m venv .venv` then `source .venv/bin/activate`
5. Install dependencies: `python -m pip install -r requirements.txt`
6. Start Jupyter: `jupyter notebook`
7. Open `MohammedArsalan_AI_Based_Phishing_Email_Detector.ipynb` and choose **Run All**.

### Option B: Google Colab
1. Open Google Colab.
2. Upload the `.ipynb` file.
3. Run the notebook cells from top to bottom. If a package is missing, run `!pip install -r requirements.txt` after uploading `requirements.txt`, or install the missing package directly.

## How it works
1. Load the illustrative messages and labels.
2. Split the examples into training and testing sets.
3. Convert text into TF-IDF numerical features.
4. Train a Logistic Regression classifier.
5. Evaluate it using accuracy, a classification report, and a confusion matrix.
6. Predict the label for a sample message.

## Limitations and responsible use
This is a beginner educational prototype, not a production email-security system. The dataset is tiny and synthetic, so evaluation results are not evidence of real-world performance. The model may incorrectly classify messages. Its score is not a guarantee that a message is safe. It does not inspect attachments, verify sender identity, or open/check links. Do not enter private or confidential emails. Always verify suspicious requests through a trusted channel and never disclose passwords or OTPs.

## Future improvements
- Train and evaluate on a larger, ethically sourced and properly labelled dataset.
- Add validation and cross-validation.
- Track false positives and false negatives.
- Explore URL features safely without visiting suspicious links.
- Build a simple interface after testing and privacy review.

## Dataset source
No external dataset is used; the small demonstration dataset is embedded in the notebook and was written for this educational project.
