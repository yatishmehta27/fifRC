## About this code ##
My first attempt at learning Ruby/Rails.

This script when run, parses the RSS feed from railscast.com
and starts Downloading the videos in 'mp4' in the directory where
the script has been called. 

Duplication of videos has been avoided by passing the '-c' parameter
to 'wget'.

Sorry for such crappy condition of the code, i'm new to ruby :)

## How to use it ##

Download the fifRC.rb script and cd into the directory.

$ruby fifRC.rb

voila!!!

## Are there any dependancies? Yes! ##
* ruby
* wget