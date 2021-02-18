# Workout-Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 
![License](https://img.shields.io/static/v1?label=Language&message=JavaScript&color=brightgreen)
![License](https://img.shields.io/static/v1?label=Language&message=MongoDB&color=blueviolet)


  ---
  
<p>&nbsp;<p>

## Description

Users are be able to:

Add exercises to a previous workout plan.

Add new exercises to a new workout plan.

View the combined weight of multiple exercises on the stats page.

<p>&nbsp;<p>

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributing](#contributing)
* [Tests](#tests)

<p>&nbsp;<p>

## Installation

To install dependencies when executing on localhost, run the following:

```
npm i
```
To seed the MongoDB database:
```
npm run seed
```

### Built with
* Javascript
* [MorganDB](https://mongodb.com/)
* [npm](https://nodejs.org/en/)
* [npm express](https://www.npmjs.com/package/express)
* [npm mongoose](https://www.npmjs.com/package/mongoose)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
* [Heroku](www.heroku.com)
* [Visual Studio Code](code.visualstudio.com)

<p>&nbsp;<p>

## Usage

To run on localhost:

```
npm run start
```

### Heroku Link
[Heroku Workout Tracker Link](https://obscure-sierra-98370.herokuapp.com/)

When the user enters the main page, he/she will see the most recent workout details. If the user has not entered any workouts yet, he/she be asked to start a new workout. If the user has already entered one previously, they can choose to continue their previous workout, or begin a new one. Either way, the user will be asked to enter details about a resistance based exercise, or cardio. For resistance workouts, the user can add the name of the exercise, the time duration of the exercise in minutes, the weight that was lifted in pounds, the amount of sets lifted, and the reps within each set. The user can then add the workout if an entry was entered.  Otherwise, the user can add an additional exercise. For cardio, very similar, but the user will input distance in miles (if applicable), duration of the cardio exercise in minutes, and the name of the exercise performed. When completely finished adding all exercises within a workout routine, the user can add the workout by pressing the "Complete" tab. The user will will be re-directed to the main page and presented with the totals of the workout that was just logged. The user can view graphs of the workouts on the dashboard.  These graphs will give workout duration totals on a line chart, weight lifted totals on a bar chart, and breakdown percentages of how much of the workout was spent on each exercise via pie charts.

<p>&nbsp;<p>


## License


This repository is licensed under the MIT License.
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p>&nbsp;<p>

## Contributing

This repository is a homework project and is not accepting contributions.
