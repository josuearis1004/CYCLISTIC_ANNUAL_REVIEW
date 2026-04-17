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
## Strategic Question: How do members and casual riders differ?
- Finding 1: Casual riders are predominantly weekend users. The data reveals that while total ride volume peaks on weekends (especially Saturdays), it's the casual riders who drive this trend. They use bikes significantly more during these two days than on weekdays.
- Members are consistent commuters, dominating weekday activity. In contrast to casual riders, annual members have stable, predictable usage throughout the workweek (Monday to Friday). Their activity patterns align clearly with daily work commute schedules, suggesting they use Cyclistic primarily for transportation, not leisure.
- Casual riders take much longer trips, hinting at different ride purposes. Although they make fewer trips in total, casual riders' average ride duration is consistently more than double that of annual members across all days. This suggests that casual rides are less about point-to-point transit and more focused on recreation, exercise, or exploration.
## RECOMMENDATIONS
- Targeted Weekend Memberships: Since casual riders are most active on weekends, create a "Weekend-Only" or "Leisure Pass" membership. This acts as a "gateway" product, introducing them to the benefits of membership during their peak usage times without the commitment of a full annual fee.
- Seasonal Conversion Campaigns: Data shows casual usage peaks during specific months (likely summer/spring). Launch "Early Bird" annual membership discounts right before these peak seasons to capture casual riders before they start their high-frequency riding period.
- Highlight "Ride Length" Value: Casual riders take significantly longer trips. Marketing materials should emphasize that annual memberships are more cost-effective for long-duration rides compared to single-trip or 24-hour passes, which often have overage fees or higher hourly rates.
- Commuter Challenges: To encourage casual riders to use bikes for commuting (the behavior seen in members), implement a "Ride to Work" rewards program. Offer points or discounts to casual riders who use bikes during weekday morning and evening rush hours.
