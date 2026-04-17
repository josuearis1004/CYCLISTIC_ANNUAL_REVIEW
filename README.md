# CYCLISTIC_ANNUAL_REVIEW 2025-2026
In this case study we analize the annual movement of CYCLISTIC, a fully established company that wanted to evolve thier sales and change the way users used their bicycles, using the first real question of the project: How do annual members and casual riders use Cyclistic bikes differently?
## RESORUCES USED 
- Google Sheets/Excel: Data cleaning, Dinamic tables, Formulas and Vizualisations
- BigQuery & SQL
- Connected sheets
## DATA PROCESSING AND CHALLENGES
The project involved analyzing a full year of activity (April 2025 - March 2026). Due to the high volume of data, I faced several technical challenges:
- Big Data Management:Several monthly files exceeded the row limits of standard spreadsheets. I utilized BigQuery to manage these datasets and created Shared Sheets to bridge the gap between SQL and Spreadsheet analysis.
- Data Extraction: Performed targeted extractions of 100,000 rows to maintain performance while ensuring a statistically significant sample for deep-dive analysis.
- Data Cleaning: Removed duplicate entries and null values.
- Feature Engineering: Created new variables to drive insights:
    * `ride_length`: Total duration of the trip.
    * `day_of_week`: Day the trip started.
    * `mean_ride_length`, `max_ride_length`, and `mode_ride_length` to establish behavior benchmarks.
## ANALYSIS AND PIVOT TABLES
I developed comprehensive Pivot Tables for each of the 12 months to compare user activity across every day of the week. Key metrics analyzed include:
- Average trip duration by user type.
- Total number of trips per day.
- Peak usage times for members vs. casual riders.
## VIZ AND KEY FINDINGS
<img width="1250" height="468" alt="image" src="https://github.com/user-attachments/assets/35895cc0-d1e6-4693-ab97-515b1c44c3af" />

