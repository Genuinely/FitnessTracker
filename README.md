## GetFit
GetFit is an Android mobile application that helps people get fit! It tracks your running workouts using GPS and the Google Mpas API. It can show you the duration of the run, the location of the run, and how many calories are burnt from the run.

## Record Workout
The Record Workout Screen records how far and how long you've run. 

## Workout Details
GetFit has the capability to show how far you've run, how long you've run, and calories burnt. It can also show all time distance ran, time ran, and calories burnt.

## All Workouts Stored
All workouts are stored in a [SQLite database](https://developer.android.com/training/data-storage/sqlite), so they can be viewed at a later time. Although the database is quite low level

## GPS and Google Map Integration
The app uses [Google Maps API](https://developers.google.com/maps/documentation/android-sdk/start) to track location and uses the phone's internal accelerometer to calculate steps.

## Calorie Tracking Algorithm
The calories burnt is calculated through the number of steps taken based off this [source](https://www.verywellfit.com/pedometer-steps-to-calories-converter-3882595). 
