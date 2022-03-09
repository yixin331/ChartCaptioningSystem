## Chart Captioning System 

### Original repo:
https://github.com/Sprea22/NeuralCaptiongSystem_WebAppUI

### Project:
"Neural Data-Driven Captioning of Time-Series Line Charts"

### Project Description:
This study focuses on generating captions for time-series line charts.
Due to the lack of suitable training corpora, we collect a dataset through crowdsourcing. 
This MERN stack web application is designed as a collector of captions.

### New updates:
1. Add 100 new time series line charts
2. Change the schema to record student id and show the scale of the charts
3. Change the mongodb connection

### How to test locally
In the project directory, you can run:

### `npm run dev`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### How to deploy it to Heroku
1. Install `heroku-cli`
2. `heroku login`
3. `heroku create my-app`
4. `git push heroku master`
