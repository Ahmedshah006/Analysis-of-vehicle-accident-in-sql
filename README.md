# Analysis-of-vehicle-accident-in-sql
This SQL script consists of several queries aimed at analyzing different aspects of accident data stored in a database. 
Question 1: Accidents in Urban vs. Rural Areas:
This query counts the number of accidents that have occurred in urban and rural areas. It selects the 'Area' column from the 'accident' table and groups the data by 'Area', then counts the total number of accidents in each area.
Question 2: Day of the Week with the Highest Number of Accidents:
This query determines which day of the week has the highest number of accidents. It selects the 'Day' column from the 'accident' table, counts the total number of accidents for each day, and orders the result by the total number of accidents in descending order.
Question 3: Average Age of Vehicles Involved in Accidents by Vehicle Type:
This query calculates the average age of vehicles involved in accidents based on their type. It selects the 'VehicleType' column, counts the total number of accidents for each vehicle type, and calculates the average age of vehicles, filtering out null values for vehicle age.
Question 4: Trends in Accidents Based on Vehicle Age:
This query identifies trends in accidents based on the age of vehicles involved. It categorizes vehicles into age groups ('New', 'Regular', 'Old') based on their age, counts the total number of accidents and calculates the average age of vehicles in each age group.
Question 5: Specific Weather Conditions Contributing to Severe Accidents:
This query identifies specific weather conditions that contribute to severe accidents. It selects weather conditions and counts the total number of accidents with a specific severity level (e.g., 'Fatal') under those conditions, ordering by the total number of accidents in descending order.
Question 6: Impacts on the Left-hand Side of Vehicles:
This query examines whether accidents often involve impacts on the left-hand side of vehicles. It selects the 'LeftHand' column from the 'vehicle' table and counts the total number of accidents for each case where information about the left-hand side impact is available.
Question 7: Relationships Between Journey Purposes and Accident Severity:
This query explores relationships between journey purposes and the severity of accidents. It joins the 'accident' and 'vehicle' tables, groups the data by journey purpose, and categorizes the severity level of accidents, then counts the total number of accidents for each purpose and severity level.
Question 8: Average Age of Vehicles Involved in Accidents Considering Daylight and Point of Impact:
This query calculates the average age of vehicles involved in accidents considering daylight and the point of impact. It selects the 'LightConditions' and 'PointImpact' columns, calculates the average age of vehicles, and filters the data based on specific conditions for point of impact and light conditions.
Overall, these queries provide insights into various aspects of accidents, such as their frequency, severity, contributing factors, and patterns related to time, location, vehicle characteristics, weather conditions, and journey purposes.











