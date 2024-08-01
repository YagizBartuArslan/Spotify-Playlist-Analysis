# Spotify Playlist Analysis

This repository contains a project on analyzing Spotify playlists. The analysis involves web scraping, data processing, and visualization to extract meaningful insights from the playlist data.

## Project Structure

- **notebook**: Contains the Jupyter notebook (`Spotify_Playlist_Analysis.ipynb`) with the entire analysis process.
- **data**: Includes any datasets or HTML files used for scraping and analysis.
- **results**: Stores the output visualizations and findings from the analysis.

## Setup and Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/Spotify_Playlist_Analysis.git
    cd Spotify_Playlist_Analysis
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Running the Analysis

1. **Open the Jupyter notebook:**
    ```bash
    jupyter notebook
    ```
2. **Navigate to the `Spotify_Playlist_Analysis.ipynb` notebook and run the cells to see the analysis and visualizations.**

## Analysis Overview

The notebook contains the following sections:

1. **Introduction:**
    - Overview of the project and objectives.
    
2. **Web Scraping:**
    - Scrapes data from a Spotify playlist using BeautifulSoup.
    
3. **Data Processing:**
    - Cleans and processes the scraped data for analysis.
    
4. **Exploratory Data Analysis (EDA):**
    - Visualizes various aspects of the playlist data, such as song popularity, BPM, genres, etc.
    
5. **Results:**
    - Presents the findings from the analysis with visualizations.

## Visualizations

Here are some sample visualizations included in the notebook:

- **Song Popularity Distribution:**
    ![Popularity Distribution](results/popularity_distribution.png)
    
- **BPM vs. Danceability:**
    ![BPM vs Danceability](results/bpm_vs_danceability.png)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
