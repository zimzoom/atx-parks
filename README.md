# ATX Parks Map

A web map containing Austin parks. A leaflet.js front end consumes a RESTful API provided by Django back end. All requirements can be installed by running `pip install -r requirements.txt`.

## Database

The `kartoza postgis` Docker image provides a container with PostgreSQL and PostGIS. The data populated by the second migration is sourced by a json file downloaded from OpenStreeMap.

## Environment variables with django-environ

In order to load environment variables for database connection, create a `.env` file in the same location and including the same content as `.env.example`.