
# First Time Setup:
```shell
docker-compose up --build
```
wait till its done, then run the command bellow to setup database and tables, plus creating a new user:
```shell
docker-compose run --rm sentry-base upgrade
```
**Note:** in the process you will be asked to create a new user for login then add a new one by providing email and password.
then open the url below and continue your setup till you reach the dashboard.
- <http://127.0.0.1:9000>

# Regular Run:
if you have already migrated the database and tables all you have to do is to run the command for running the compose file.
```shell
docker-compose up
```


