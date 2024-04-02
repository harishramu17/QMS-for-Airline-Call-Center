# Generative AI-Based Quality Management System for Airline Travel Call Centers
## Problem Statement
Every day, airline travel call centers handle a large number of customer inquiries and difficulties, necessitating effective management and evaluation of call quality and agent performance. Traditional quality assessment methodologies frequently fail to capture the nuances of client interactions. Our technology tries to close this gap by using generative AI to transcribe audio files and analyze call content in depth.
## Objectives
Our main aims include:

- Create a user-friendly online application for uploading and processing MP3 audio files from call records.
- Using the Lyzr AI API to reliably and efficiently transcribe audio files.
- Transcriptions are analyzed to provide Key Performance Indicators (KPIs) for evaluating call quality and agent performance.

============================================================================================

![](https://github.com/harishramu17/QMS-for-Airline-Call-Center/blob/main/Images/nx59dhUZSz.gif)

============================================================================================

## Step-by-Step Implementation 
To achieve these objectives, we've outlined a step-by-step implementation guide:

- ### Project Setup:
  Initialize the project, set up a virtual environment, and install necessary libraries.
- ### Building the UI:
  Create an intuitive interface with a file upload option for the zip file containing MP3 files.
- ### Uploading and Processing:
  Implement functionality for users to upload the zip file and extract MP3 files seamlessly.
- ### Integrating Lyzr AI API:
  Integrate the Lyzr AI API to transcribe audio files accurately.
- ### Problem Bucketing/Classification:
  Analyze call content to categorize issues such as flight cancellations, rescheduling, refunds, delays, staff behavior complaints, etc.
- ### Analyzing Transcriptions:
  Extract insights from transcriptions, including sentiment analysis, keyword identification, and identifying specific phrases indicating customer satisfaction or dissatisfaction.
- ### Calculating KPIs:
  Develop functions to calculate various KPIs such as customer satisfaction scores, resolution times, and agent performance metrics.
- ### Displaying Results:
  Design a visually appealing dashboard to present calculated KPIs effectively through tables, charts, or graphs.
