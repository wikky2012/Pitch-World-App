# pitch-world

## Author

[Joseph-Odhiambo](https://github.com/Joseph-Odhiambo)

# Description
This  is a flask application that allows users to post one minute pitches and also allows other users who have signed up to comment and upvote or downvote a pitch. It also allows a person to signup to be able to access the functionalities of the application

## Live Demo

## Screenshot

<img src="https://github.com/Joseph-Odhiambo/pitch-world/blob/master/app/static/photos/Screenshot%20from%202020-09-25%2011-18-03.png?raw=true" width="900px" height="440px">

## User Story

* Comment on the different pitches posted py other uses.
* See the pitches posted by other uses.
* Vote on s pitch they have viwed by giving it a upvote or a downvote.
* Register to be allowed to log in to the application
* View pitches from the different categories.
* Submit a pitch to a specific category of their choice.


## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  https://github.com/Joseph-Odhiambo/pitch-world
  ```
2. Move to the folder and install requirements
  ```bash
  cd pitch-world
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.8 manage.py server
  ```
5. Testing the application
  ```bash
  python3.8 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)


## Known Bugs
<!-- * There are no known bugs currently but pull requests are allowed incase you spot a bug -->

## Contact Information 

If you have any question or contributions, please email me at [josephkdo@gmail.com]

## License
* *MIT License:*
* Copyright (c) 2020 **Joseph Odhiambo**