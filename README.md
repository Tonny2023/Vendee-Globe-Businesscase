# Vendee-Globe-Businesscase
A businesscase to build a Lambda architecture in Azure and create a Dashboard in Power BI with real-time data

## The business case
In this business case, we created a PowerBI Dashboard that showed the position and the ranking of the sailing boats in the Vendee Globe Race. 
Since there was no Vendee Globe race when we created this project, an app was used that imitates the real-time data from this race. The app was created by M.D. Farrager and can be found here:https://github.com/mdfarragher/TCS/blob/main/race_simulator.py

## Our architecture in Azure
We built a cloud-based Lambda Architecture in Azure to process the telemetry data from the
sailing boats. It contains a real-time path for processing data about the position and a batch-processing path
for collecting data for calculating the ranking of the boats
