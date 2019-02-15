# SaaS - Simpsons as as Service

1.0.0

Simpsons as a Service provides you with a scalable, RESTful API for Simpsons-related tasks.

## Installation

npm install

## Run

npm start

## Usage

```
await fetch("/doh")
.then(response=>response.json()
.then(data=>data))
```

will return 

```
{message: "D'oh!"}
```

## Adding new endpoints

* Fork the repo
* Add your operation (see index.js for now)
* Push and submit a pull request

## Contributors

PuzzleBart @ the Arctic Cloud Developer Challenge 2019