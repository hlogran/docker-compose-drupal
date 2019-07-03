# docker-compose-drupal
A docker compose file to set up a drupal and a postres container

Technologies
======
- docker-compose

To set up the server
======
1 -Mount the containers by running the current instruction from the repo directory
- docker-compose up
2 - Go yo http://localhost:8080
3 - To configure drupal, set up the database connection with this data:
- host: postgres
- user: postgres
- pass: pwd
