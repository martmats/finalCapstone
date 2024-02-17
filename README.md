# Sentiment Analysis of Product Reviews

## Description
This project utilizes the powerful spaCy library alongside SpacyTextBlob to conduct sentiment analysis on product reviews. By analyzing the sentiment of customer feedback, businesses and developers can gain insights into the overall customer satisfaction, identify areas for improvement, and tailor their strategies to enhance product quality and service. This automated analysis helps in quickly processing large volumes of data to determine general sentiment trends without manual review.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation
To run this sentiment analysis project locally, you'll need to have Python installed along with several dependencies including spaCy, SpacyTextBlob, and pandas. Follow these steps to set up your environment:

1. Clone this repository to your local machine.
2. Ensure you have Python installed. If not, download and install Python from [python.org](https://www.python.org/).
3. Install the required libraries using pip:

```bash
pip install spacy spacytextblob pandas
```

4. Download the necessary spaCy language model:

```bash
python -m spacy download en_core_web_sm
```

## Usage
After installing the necessary dependencies, you can run the script to perform sentiment analysis on your dataset. Ensure you have a dataset of product reviews in CSV format with at least one column containing the review texts.

1. Place your dataset in the same directory as the script, or modify the script to point to your dataset's location.
2. Run the script:

```bash
python sentiment_analysis.py
```

3. The script will output the sentiment analysis results, categorizing each review as Positive, Negative, or Neutral based on its sentiment polarity.

*Note: For demonstration purposes, screenshots and more detailed usage instructions would be provided here based on the actual UI or output of the script.*

## Credits
This project was developed by [Marta](https://github.com/martmats) as part of her data science portfolio. The use of the spaCy library and SpacyTextBlob extension for sentiment analysis demonstrates the application of NLP techniques in real-world scenarios.