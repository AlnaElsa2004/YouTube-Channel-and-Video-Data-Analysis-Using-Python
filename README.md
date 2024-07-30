# YouTube Channel and Video Data Analysis Project

This project aims to extract and analyze data from YouTube channels and their videos using the YouTube API. The analysis includes comparing multiple channels based on their statistics and visualizing the data using Python libraries like Pandas and Seaborn.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Setup](#setup)
  - [Creating a YouTube API Key](#creating-a-youtube-api-key)
  - [Setting up the Virtual Environment](#setting-up-the-virtual-environment)
  - [Installing Required Packages](#installing-required-packages)
- [Project Structure](#project-structure)
- [Part 1: Extracting Channel Details](#part-1-extracting-channel-details)
- [Part 2: Extracting Video Details](#part-2-extracting-video-details)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Python 3.7+
- Anaconda
- Jupyter Notebook

## Setup

### Creating a YouTube API Key

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing one.
3. Navigate to **APIs & Services** > **Dashboard**.
4. Click on **Enable APIs and Services**.
5. Search for **YouTube Data API v3** and enable it.
6. Go to **Credentials** and click on **Create Credentials**.
7. Select **API key**. Copy and save the API key.

### Setting up the Virtual Environment

1. Open Anaconda Prompt.
2. Create a new virtual environment:

    ```bash
    conda create -n youtube-data-analysis python=3.8
    ```

3. Activate the virtual environment:

    ```bash
    conda activate youtube-data-analysis
    ```

### Installing Required Packages

1. Install the required packages:

    ```bash
    conda install jupyter
    pip install google-api-python-client pandas seaborn
    ```

## Project Structure


## Part 1: Extracting Channel Details

1. Use the YouTube API to extract details such as channel name, total number of subscribers, total views, and total number of videos posted by each channel.
2. Load this data into a Pandas DataFrame.
3. Analyze and visualize the data to compare different channels.

## Part 2: Extracting Video Details

1. Use the YouTube API to extract details such as video title, total views, likes, dislikes, and comments for all videos of a particular channel.
2. Load this data into a Pandas DataFrame.
3. Analyze and visualize the data using Seaborn.

## Usage

1. Open `youtube_data_analysis.ipynb` in Jupyter Notebook.
2. Follow the steps provided in the notebook to execute the code.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This project serves as a starting point for anyone aspiring to become a Data Analyst, providing hands-on experience with real-world data extraction, analysis, and visualization.
