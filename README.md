# RaspberryPi
RPi projects

## DHT11 Temperature and Humidity Sensor Tweets
For this project, I connected the sensor to the GPIO and I'm using a short python program that reads in the variables as bits and calculates the temp and humidity. I've also connected the program to a Twitter account, [@JacksonsDigs](https://twitter.com/JacksonsDigs?lang=en) via Tweepy so that every time the program is run it tweets the temperature and humidity. Finally, I've used the time-based job scheduler, Cron, to run the Python script every hour. 
