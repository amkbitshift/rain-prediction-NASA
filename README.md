Project Raincheck
<img width="1920" height="1020" alt="Screenshot 2025-10-04 115747" src="https://github.com/user-attachments/assets/0364f755-5127-463a-9a74-6f115c2c4546" />


Challenge
Will It Rain On My Parade? - NASA Space Apps Challenge 2025

Team
Team Project Raincheck

Live Demo
[Click here to see project](https://amkbitshift.github.io/rain-prediction-NASA/)

Project Overview
Planning a future outdoor event can be challenging when weather forecasts are unreliable more than a few days out. Our project, "Project Raincheck," provides a unique solution by giving users a data-driven, long-range weather probability. Our web application uses decades of historical NASA Earth observation data to answer the question, "What is the historical chance of rain on my specific date and at my location?"

Features
User Geolocation: Automatically detects the user's latitude and longitude to provide location-specific data.

Date Selection: Allows the user to select any future date.

Historical Probability: Calculates the probability of rain on that specific day and month, based on over 40 years of NASA data.

Intuitive UI: A clean and responsive user interface makes complex data easy to understand, complete with a dynamic icon reflecting the probability.

Client-Side Execution: The entire application runs in a single HTML file, eliminating server-side costs and ensuring a fast, reliable user experience.

How It Works
The application is built as a single-page HTML file that runs entirely in the user's browser. It uses a straightforward process:

A user selects a date and clicks "Check Probability."

The browser's Geolocation API is used to get the user's current coordinates.

The JavaScript code directly calls the NASA POWER (Prediction Of Worldwide Energy Resources) API.

The app processes the returned JSON data, analyzing all historical records for the specified month and day.

A simple algorithm calculates the percentage of historical days with precipitation.

The result is then beautifully displayed on the page with a clear percentage and a corresponding weather icon.

NASA Data Used
NASA POWER (Prediction Of Worldwide Energy Resources) API: We used the daily point data endpoint to retrieve historical precipitation (PRECTOTCORR) for a given latitude and longitude.

Installation & Usage
This project is a single, self-contained HTML file. To run it, simply download the index.html file and open it with any modern web browser. No special installation or server is required.

Final Submission Details (For Team's Reference)
This section contains the content prepared to be used in the official submission form.

Summary:
Project Raincheck is a user-friendly web application that helps individuals make better long-term plans for outdoor events by providing historical weather probabilities. Unlike traditional forecasts, our solution uses decades of real NASA Earth data to answer the question, "What is the chance of rain on my specific date and location?" The app's elegant design makes complex scientific data accessible and actionable, empowering users to make informed decisions for everything from weddings to school trips. Our project's importance lies in its ability to transform NASA's open data into a practical, real-world planning tool for everyday life.

Use of Artificial Intelligence (AI):
AI was utilized as a tool to assist in the ideation, planning, and content creation phases of this project. Specifically, an AI assistant was used to guide the project's development workflow, debug and refine code segments, and generate the script and content for the project's submission, including the summary and video script.

Other Resources:

HTML, CSS, JavaScript: https://developer.mozilla.org/

W3C Geolocation API: https://www.w3.org/TR/geolocation-API/
