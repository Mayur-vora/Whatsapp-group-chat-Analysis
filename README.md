# WhatsApp Chat Data Analysis

This project involves analyzing WhatsApp chat data using Python. The primary goal is to extract insights from the chat history, including message frequencies, word cloud generation, and time-based analysis.

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Setup](#setup)
4. [Usage](#usage)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

The analysis involves the following steps:

- Importing necessary libraries for data manipulation and visualization.
- Parsing the WhatsApp chat file to extract messages, timestamps, and other relevant information.
- Preprocessing the data, including cleaning and formatting.
- Analyzing message frequencies, popular words, and emojis.
- Visualizing the data using matplotlib and seaborn.
- Extracting insights regarding chat activity patterns and trends.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- Wordcloud
- Emoji

## Setup

1. Clone this repository to your local machine.
2. Install the required libraries using pip:
    ```
    pip install -r requirements.txt
    ```
3. Place your WhatsApp chat export file (in text format) in the project directory.

## Usage

1. Open the Jupyter Notebook file (`WhatsAppGroupChatAnalysis.ipynb`) in your Jupyter environment.
2. Update the `file` variable with the name of your WhatsApp chat export file.
3. Customize the `key` variable to specify the time format used in the chat export file (12-hour or 24-hour format).
4. Run the cells in the notebook to execute the analysis.

## Results

The analysis will provide insights such as:

- Message frequency over time.
- Word cloud visualization of popular words.
- Emoji distribution.
- Time-based analysis of chat activity.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
