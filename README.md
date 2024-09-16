# Youtube Dashboard Analytics

This project creates an interactive dashboard to analyze YouTube channel performance using Streamlit. It offers insights into both aggregate metrics and individual video analysis.

## Features
### Aggregate Metrics:
  - Displays key performance indicators (KPIs) for the last 6 months, including views, likes, subscribers, and more.
  - Shows percentage changes compared to the previous 6-month period.
  - Presents a color-coded table of video metrics, highlighting positive and negative trends.
### Individual Video Analysis:
  - Allows users to select and analyze specific videos.
  - Visualizes viewer demographics with a bar chart showing views by subscription status and country.
  - Compares video performance against channel benchmarks using a line chart of cumulative views over the first 30 days.
### How It Works
  - The code loads and preprocesses the data from CSV files.
  - It calculates various metrics and creates different views of the data.
  - The Streamlit interface allows users to switch between aggregate and individual video analysis.
  - Interactive charts are created using Plotly for data visualization.
### Key Functions
  - load_data(): Loads and processes the CSV files.
  - audience_simple(): Simplifies country codes for easier analysis.
  - style_negative() and style_positive(): Apply color formatting to the dataframe.
### Usage
  To use this dashboard:
  - Ensure you have the required CSV files in the same directory as the script.
  - Install the necessary Python libraries (pandas, numpy, plotly, streamlit).
  - Run the script using Streamlit: streamlit run [script_name].py
  - Use the sidebar to switch between aggregate metrics and individual video analysis.
  - For individual videos, select a specific video from the dropdown menu to view its performance.

This dashboard provides a user-friendly way to analyze YouTube channel performance, offering both high-level insights and detailed video-specific analytics.
