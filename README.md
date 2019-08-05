# League-Performance-Tracker

This project's goal was to provide a one-step interface that accepts a user's in-game id, utilizes the riot api to stash stats and info in a db, and returns videos based on their stats from the last 10 played games which are intended to be means for them to improve.
The front end is set up, we can execute requests from the riot api, and the youtube api is functional. However, the connection between the api pulls and the youtube search is not yet working. 
This application was built using express, handlebars, mysql2, sequalize, jquery, axios, and the Bulma CSS framework.
In order to ensure full functionality, we need to finish connecting the api pulls to the database. 
The other function we would ideally implement would be a ranking system which orders users by summonder name and winrate for their last ten games, which is also pulled from the riot api, fed through a sorter function, and delivered to the front end through handlebars.
