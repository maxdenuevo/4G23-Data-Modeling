# Data Modeling

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlite&logoColor=white)
![Pipenv](https://img.shields.io/badge/pipenv-737373?style=for-the-badge&logo=python&logoColor=white)

</div>

Create a model for your StarWars Blog.

Create the Entity Relationship Diagram for your SW Blog Database, very similar to this one:

![Starwars Diagram](https://github.com/breatheco-de/exercise-starwars-data-modeling/blob/master/assets/example.png?raw=true)
[Click to open diagram](https://app.quickdatabasediagrams.com/#/d/LxNXQZ)

## Installation

1. Get inside the environment `$ pipenv shell`

2. Install all dependencies `$ pipenv install`

3. Generate the diagram as many times as you need `$ python src/models.py`

4. Open the file `diagram.png` to check out your UML diagram!

## Instructions

Your Job is to update the `src/models.py` file with the code needed to replicate the StarWars data model.

The project is using the SQLAlchemy Python library to generate the database.

- ✅ Table User to represent blog users
- ✅ Users can login (email and password fields)
- ✅ Users can save favorite planets and characters (through Favorite table)
- ✅ Database stores characters and planets (Character and Planet tables)
- ✅ Has more than 4 models (User, Planet, Character, Favorite)
- ✅ Proper relationships between tables:
  - Users have many favorites
  - Planets can be favorited by many users
  - Characters can be favorited by many users
  - Characters belong to a planet
- Generate the `diagram.png` file at the end by running `$ python src/models.py` on the console.

## Sources:

This exercise is part of the complete 4Geeks Academy Full Stack course:

[![4Geeks Academy](https://img.shields.io/badge/4Geeks%20Academy-blue.svg)](https://4geeks.com/syllabus/santiago-pt-49/project/data-modeling-starwars)
