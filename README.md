# django-api-sqlite
django-api-sqlite backend server

## to get data in list form
http://127.0.0.1:8000/bucketlists

[ { "id": 1, "name": "leslie223232", "date_created": "2019-01-19T04:46:49.840129Z", "date_modified": "2019-01-19T04:49:49.630368Z" }, { "id": 2, "name": "leslie22", "date_created": "2019-01-19T04:47:03.831911Z", "date_modified": "2019-01-19T04:47:03.831934Z" } ]

## get specific item
http://127.0.0.1:8000/bucketlists/1/

{ "id": 1, "name": "leslie223232", "date_created": "2019-01-19T04:46:49.840129Z", "date_modified": "2019-01-19T04:46:49.840155Z" }

## to update a specific item
http://127.0.0.1:8000/bucketlists/1/

request body { "id": 1, "name": "leslie223232", "date_created": "2019-01-19T04:46:49.840129Z", "date_modified": "2019-01-19T04:46:49.840155Z" }

## delete an item
http://127.0.0.1:8000/bucketlists/1/

Response = no content..
