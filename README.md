# HikeFinder #
---
### HikeFinder will take user input like skill level, location, and find a suitable nearby hike based on inputs, weather and trail class rating. More detail below. ###
---
Intended for personal portfolio, but hopefully useful.

WHAT IS HIKE FINDER:
I plan to build Hike Finder– a Hike Recommendation algorithm that suggests hikes based on trail reviews (average star ratings), and user input like location, elevation, elevation gain, time of year, time of day, amount of time available, live or expected weather at time of hike, and risk tolerance. This will account for weather, expected hiking speed based on elevation, and class rating of trails.

WHY MAKE HIKE FINDER:
There are way too many trails to cover in a lifetime in Colorado alone, not to mention nation-wide or globally, so having a recommendation algorithm would increase your odds of having a great experience, every time.

SOURCE DATA FOR HIKE FINDER:
I plan to use .xml & .gpx files and other qualitative data from:
14ers.com for tracks, timing and weather data from trip reports.
Same files from my Dad, who’s been on a peak-bagging mission in retirement. He’s done the majority of 50 state highpoints and the majority of 58 fourteeners in Colorado, along with a bunch of thirteeners along the way. I have his track with timing and have done only a handful of these with him, so this is my way of spending a little bit more time with him, while helping others do the same with their people.

QUESTIONS HIKE FINDER WILL ANSWER:
Best hikes for X type of person at X time and place;
Average speed relative to altitude;
Effect of different variables on speed. Variables include: Weather, Elevation, Elevation gain.

EDIT 09-27-2023
1. Converted .gpx files to .csv.

2. Used VIM to remove headers (all but column labels) from .csv files using this format in Terminal:
$ vim filename.csv
:1,/\ntrkpt/+1d
:wq
