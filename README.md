# RaspberryPi
RPi projects

### DHT11 Temperature and Humidity Sensor Tweets
For this project, I connected the sensor to the GPIO and I'm using a short python program that reads in the variables as bits and calculates the temp and humidity. I've also connected the program to a Twitter account via Tweepy so that every time the program is run it tweets the temperature and humidity.  The script also connects to a MySQL database which records each temperature reading along with it's timestamp. The data is displayed in a simple table format on an Apache web server. Finally, I've used the time-based job scheduler,Cron, to run the Python script every hour. 
