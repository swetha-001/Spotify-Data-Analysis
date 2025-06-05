# Spotify-Data-Analysis

This project explores a dataset of the most streamed songs across major platforms like Spotify and more. The goal is to uncover insights about artist performance, song popularity trends, and cross-platform success.

## Data Overview 
The dataset includes the following key columns Track Name, Album Name, Artist, Release Date, ISRC, Spotify and other platform Metrics, Explicit Track flag. 

## 1. Data Loading & Understanding
* Loaded dataset using Pandas
* Checked shape, info, and column types
* Previewed top and bottom rows

## 2. Data Cleaning
* Handled missing and duplicate values
* dropping irrelevant columns
* Converted data types

## 3. Analysis
EDA is conducted to unveil patterns and trends. It includes displaying overall statistics, identifying trends of Spotify popularity by year, determining artist with most Spotify streams, identifying most popular song on Spotify etc.

![image](https://github.com/user-attachments/assets/2162aca9-ff51-40e0-8fcb-85ade3a35f08)

![image](https://github.com/user-attachments/assets/6d16aceb-01ea-477e-a0ad-9dad0ac8cb3f)

![image](https://github.com/user-attachments/assets/9a5a3043-290e-4997-b528-7d08975beb95)

## Other Insights :
* Content filter is performed by identifying Number of songs with explicit content.
* Correlation of Spotify Popularity with Track Score and All-Time Rank which suggests Spotify Popularity alone doesn't strongly determine rank or score.
* Artist-Level Analysis is performed identifying Artist with highest average track score and most songs above Spotify Popularity 90.
* Songs with the highest YouTube likes which measures Engagement. 

## Most Popular song across all platforms:
1. Selected popularity metrics from multiple platforms (Spotify, YouTube, TikTok, etc.)

2. Handled missing values and normalized the data using MinMaxScaler.
   - Normalizes each metric, so one metric doesn’t overpower others

3. Calculated a combined popularity score by summing or weighting the normalized values.
   - Sums them into one composite score

4. Identified the song with the highest combined score as the most popular across all platforms.



