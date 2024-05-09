# HACK SONG 🎧

The API provides the following endpoints:

| HTTP Verb     | URL                 | Request body      | Action            |
| ------    | ------------------- | ------------------ | -------------- |
| `POST`    | `/tracks`           | JSON        | Create a new track               |
| `GET`     | `/tracks`           | (empty)     | Return all the tracks            |
| `GET`     | `/tracks/:trackId`  | (empty)     | Return the specific track        |
| `PUT`     | `/tracks/:trackId`  | JSON        | Edits the specific track         |
| `DELETE`  | `/tracks/:trackId`  | (empty)     | Deletes the specific track       |
|           |                     |             |                                  |


| HTTP Verb | URL      | Request body | Action               |
|-----------|----------|--------------|----------------------|
| `POST`    | `/action`| JSON         | Create a new action  |
