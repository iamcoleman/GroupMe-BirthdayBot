# GroupMe Birthday Bot

A simple script that will send a happy birthday message into a GroupMe when it is someone's birthday.

`birthday-guy.py` is the main script that will take a list of names and birthday's from `birthday-list.csv`, construct the birthday message, then post to the GroupMe.

# Deploy

I have this birthday bot deployed to Heroku and I use Heroku's built in Scheduler to run the `birthday-guy.py` script every morning at 9:00am. 
