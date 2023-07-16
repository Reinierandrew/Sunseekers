# Sunseekers

About this project:

The objective for this project was to analyse data in the solar energy industry and identify regions of Australia with the highest potential for growth in the solar panel installation business. We have created a website that reviews APVI’s solar panel data for postcodes, regions and states and showcase’s our findings.

This project utilizes data sourced from the Australian PV Institute's website and integrates it with Australian Postcodes found using the Geoapify API via Jupyter Notebook.. 

The purpose of the data collection was to review:  
* 	 Top 10 suburbs with potential capacity in each state
<img width="1086" alt="Screenshot 2023-07-16 at 1 14 53 pm" src="https://github.com/Reinierandrew/Sunseekers/assets/112833174/e1216673-8747-4ed0-8cc4-7e3b218adc03">
* 	 Overall number of dwellings installations available for in each state
<img width="1086" alt="Screenshot 2023-07-16 at 1 15 35 pm" src="https://github.com/Reinierandrew/Sunseekers/assets/112833174/7e89aca7-d61f-4e6c-b8ef-1b55af7077ac">
* 	 Current capacity vs potential kw capacity in each state & postcode
<img width="1086" alt="Screenshot 2023-07-16 at 1 16 09 pm" src="https://github.com/Reinierandrew/Sunseekers/assets/112833174/f1322079-a796-420e-bbe8-748e229e553c"> 
* 	 Show number of installations in each postcode & region
* 	 <img width="1086" alt="Screenshot 2023-07-16 at 1 15 55 pm" src="https://github.com/Reinierandrew/Sunseekers/assets/112833174/a842f901-aad8-4540-82ca-61b243a4e4d2">
* 	 Show average capacity per dwelling & installation in each postcode 
<img width="1458" alt="Screenshot 2023-07-16 at 1 13 40 pm" src="https://github.com/Reinierandrew/Sunseekers/assets/112833174/be820f74-91a7-44cd-a312-9020e1908ff1">

The user can also select a postcode and the capacity and potentials for the selected postoce and compare to the Australian average.

<img width="1283" alt="Screenshot 2023-07-16 at 1 12 48 pm" src="https://github.com/Reinierandrew/Sunseekers/assets/112833174/df51da24-f0f7-45d0-b000-c42dbb7ec818">


# Technologies used:
SQL was used to create the database, then power our website using a Python Flask API, and build the website using HTML, CSS, JavaScript & various JavaScript libraries.

     SQL
     Python
     Flask
     Javascript
     JavaScript libraries: Leaflet, Plotly & Chart 

# This is the navigation to read our project:

     Firstly clone the file from repositories to your machine, and run the following command
     chmod a+x run.sh
     Then you can test the application by running the following in your command line.
     ./run.sh
     Second copy the link and paste in browser.
     Finally you can see the homepage.  Click in the navigation bar to see the map and regional chart information.
