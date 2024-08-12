## Overview
This project focuses on analyzing hotel booking cancellations using advanced Excel techniques.The analysis was conducted on a dataset 
containing over 119,000 bookings, with a specific focuson understanding the patterns and reasons behind the 44,224 cancellations recorded.
A comprehensive dashboard was created to visualize the key insights and provide an interactive tool for further exploration.

## Project Highlights
### 1. **Data Cleaning and Preparation**
   - **Initial Data Overview:** The raw data was inspected for any inconsistencies, missing values, and duplicates. 
   - **Handling Missing Data:** Missing values were either filled or removed based on the context to ensure the accuracy of the analysis.
   - **Creation of New Columns:**
     - **Room Status:** A new column `room_status` was created using nested IF formulas to determine whether the guests received their desired room type or not.
     - **Guest Type:** Another column `guest_type` was added using IF statements to categorize bookings into `Single`, `Couples`, or `Family`.

### 2. **Dashboard Creation**
   - **Interactive Dashboard:** The final dashboard was designed to provide an intuitive and insightful representation of the data.
     Key metrics such as the total number of bookings,total cancellations, and their breakdown by hotel type, guest type, and room status are all included.
     
   - **Slicers for Dynamic Analysis:** Slicers were added for easy filtering based on:
     - **Year of Arrival**
     - **Month of Arrival**
     - **Country of Origin**
     - **Guest Type (Single, Couples, Family)**
   - **Visualizations:**
     - **Pie Charts:** Illustrating the distribution of bookings and cancellations by hotel type.
     - **Bar Charts:** Displaying cancellations by guest type, room status, and monthly trends.

### 3. **Key Insights**
   - **Hotel Type:** City hotels had a higher number of total bookings and cancellations compared to resort hotels.
   - **Guest Type:** Couples accounted for the highest number of bookings and cancellations, followed by families.
   - **Room Status:** A significant portion of cancellations occurred when guests did not receive their desired room type.
   - **Monthly Trends:** August recorded the highest number of cancellations, possibly due to seasonal factors.

## Technical Details

- **Tools Used:**
  - **Excel:** For data cleaning, preparation, and analysis.
  - **Advanced Excel Formulas:** Utilized for creating new columns and calculating key metrics.
  - **Data Visualization:** Excel's built-in charting tools were used to create the dashboard.

- **Formulas and Functions:**
  - **IF Statements:** Used to create the `guest_type` and `room_status` columns.
  - **Nested IF Statements:** Implemented to handle complex conditions for data categorization.

## Conclusion

This project showcases the power of Excel in handling and analyzing large datasets. The interactive dashboard serves as a valuable tool for 
understanding the factors influencing hotel booking cancellations. The combination of data cleaning, advanced formulas, and dynamic visualizations 
highlights the depth and complexity of the analysis performed.

## Files in Repository

- **`Hotel Cancellation Final.xlsx`**: The Excel file containing the cleaned data, newly created columns, and the final dashboard.
- **`Project Dashboard.png`**: A snapshot of the final dashboard summarizing the analysis.
- **`hotel_booking_raw.csv`**: file is the unprocessed dataset containing all original booking records, used as the basis for analysis.

## How to Use

1. **Download the Excel File**: Open the `Hotel Cancellation Final.xlsx` file to explore the data and the dashboard.
2. **Interact with the Dashboard**: Use the slicers to filter the data by year, month, country, and guest type for a more focused analysis.
3. **Review the Insights**: Refer to the charts and summaries to gain a better understanding of the booking and cancellation trends.
