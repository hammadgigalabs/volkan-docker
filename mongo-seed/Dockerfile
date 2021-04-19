FROM mongo

COPY users.json /users.json
CMD mongoimport --host mongodb --db volkan-mongodb --collection users --type json --file /users.json --jsonArray