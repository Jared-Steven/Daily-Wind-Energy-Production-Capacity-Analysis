# Daily Wind Energy Production Capacity Analysis

This Jupyter Notebook contains analysis and visualization of daily wind energy production capacity in Australia. The data used in this project is scraped from Aneroid Energy website.
Project Overview

    This project involves scraping data from the public domain using a web scraper.
    The scraped data is analyzed and visualized to provide insights into daily wind energy production capacity in Australia.
    The project allows for live visualization of data whenever the website is updated by running the provided code cells.

Project Structure

    Data Scraping
        The project starts with importing necessary libraries such as Matplotlib, BeautifulSoup, Plotly Express, Pandas, Requests, and CSV.
        A web scraper is implemented to fetch data from the Aneroid Energy website.

    Data Collection and CSV Handling
        The scraped data is organized into different categories based on Australian states such as New South Wales, Queensland, South Australia, Tasmania, and Victoria.
        Functions are defined to write the collected data into CSV files and to read the generated CSV files.

    Visualization
        Plotly Express is used to create interactive visualizations such as line graphs and bar charts.
        Visualizations are generated to represent total wind energy capacity in Australia and energy capacity in each Australian state.

    Results Presentation
        The visualizations provide insights into the wind energy production capacity at various wind farms across Australia.
        Separate visualizations are provided for each state for detailed analysis.

Running the Notebook

    To run the notebook:
        Ensure all necessary libraries are installed.
        Run each cell sequentially to execute the code and generate visualizations.
        Optionally, modify the code to scrape data from specific regions or customize visualization parameters.
