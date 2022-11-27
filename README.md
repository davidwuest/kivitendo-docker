docker  environment for kivitendo-erp 

## Kivitendo setup (default github repo.)

    $ cd web/
    $ git clone https://github.com/kivitendo/kivitendo-erp.git

The entrypoint script creates the webdav directory.
Additionally it chowns the user to www-data and sets the group to rw
on first container startup.

## Database setup


## Run

Adapt ports in `docker-compose.yml` as needed.

Run:

    $ docker-compose build
    $ docker-compose up -d

or

    $ docker-compose up --build -d


Admin-Login (default): admin123

## Development Notes


