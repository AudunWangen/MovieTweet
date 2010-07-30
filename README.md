# MovieTweet

MovieTweet is a simple PHP script that fetches data from Dialog eXe AS publically awailable XML-files and posts movie and theatre showtimes to Twitter. By default it posts movie showtimes for today, so it makes sence to schedule the script to run daily.

* [MovieTweet on GitHub](http://github.com/AudunWangen/MovieTweet)

The script is built using functions from other scripts:

* [xml2array](http://www.bin-co.com/php/scripts/xml2array/) - BSD license
* [bit.ly API script](http://davidwalsh.name/bitly-api-php) - unknown license
* [Twitter curl script](http://kosso.co.uk/twitter/twitterCurl.phps) - free to use as you want

## Required packages

* PHP with libcurl
* A bit.ly-account
* A twitter-account

## Installation

Copy the script anywhere you like and change twitter username and password, bit.ly username and key and change p_id to the id of your cinema. See comments in the scripts for further information.

Make sure the script is executable, and run it manually or make a daily cronjob/scheduled task.

## Contact

Audun Wangen  
http://audunwangen.net/  
audun@norblogg.net
