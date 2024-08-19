# Transjakarta Public Transportation Data Analysis

## Project Overview

This project is part of my learning journey in data analysis using Google Colab. The objective of this project is to analyze transaction data from Transjakarta, a public transportation system in Jakarta, Indonesia. Through this analysis, I aimed to uncover insights about customer behavior, route efficiency, and transaction patterns.

## Dataset

The dataset consists of transaction records with the following structure:
- **transID**: Unique transaction ID.
- **payCardID**: Customer's main identifier (ticket card ID).
- **payCardBank**: Bank issuer of the customer's card.
- **payCardName**: Customer's name as embedded on the card.
- **payCardSex**: Customer's gender.
- **payCardBirthDate**: Customer's birth year.
- **corridorID**: Corridor or route ID.
- **corridorName**: Name of the corridor or route.
- **direction**: Route direction (0 for Go, 1 for Back).
- **tapInStops**: ID of the stop where the customer tapped in.
- **tapInStopsName**: Name of the stop where the customer tapped in.
- **tapInStopsLat**: Latitude of the tap-in stop.
- **tapInStopsLon**: Longitude of the tap-in stop.
- **stopStartSeq**: Sequence of the stops related to direction.
- **tapInTime**: Date and time of tap-in.
- **tapOutStops**: ID of the stop where the customer tapped out.
- **tapOutStopsName**: Name of the stop where the customer tapped out.
- **tapOutStopsLat**: Latitude of the tap-out stop.
- **tapOutStopsLon**: Longitude of the tap-out stop.
- **stopEndSeq**: Sequence of the stops related to direction.
- **tapOutTime**: Date and time of tap-out.
- **payAmount**: Amount paid by the customer.

The dataset can be accessed [here](https://drive.google.com/drive/folders/1S04hk5uHfHYe6J1S6fVqDunuja1Lk1Lo?usp=sharing).

## Analysis and Visualizations

In this project, I conducted several analyses and visualizations to understand different aspects of the data:

1. **Tap-In Time Distribution**: Analysis of the distribution of tap-in times throughout the day, identifying peak hours and off-peak times.
  
2. **Comparison of Tap-In and Tap-Out by Location**: Visualization comparing the locations where customers tap in and tap out, providing insights into popular routes and stops.
  
3. **Average Payment Amount by Gender**: Analysis of the average amount paid by gender, exploring any potential differences in payment behavior.
  
4. **Transaction Frequency by Age**: Visualization of transaction frequency based on customer age, providing insights into the demographics of the users.

## Key Findings

- **Peak Hours**: The highest concentration of tap-ins occurred during morning and evening rush hours.
- **Popular Routes**: Certain routes and stops were more frequently used, indicating higher traffic areas.
- **Gender Differences**: There was a noticeable difference in the average payment amounts between genders.
- **Age Distribution**: Younger customers tended to use the service more frequently than older age groups.

## Tools and Technologies

- **Google Colab**: For coding and data analysis.
- **Pandas & NumPy**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **GitHub**: For version control and project sharing.

## How to Run

To replicate the analysis:
1. Clone this repository.
2. Open the Jupyter Notebook file in Google Colab.
3. Follow the instructions within the notebook to load the dataset and execute the analysis.
