# Ecommerce2 Service
It's very simple service designed to manage certain pool of orders, provide some basic informations about orders itself, statistics etc.
Structure is a bit larger than in Ecommerce Service 1. 

Data about Orders will be loaded from JSON file in a way that match bussiness logic that I was working with.
Order contains:
  Client
  Product
  quantity
  order_date

At this point it's fully testable.

Project is part of a learning so I'm happy to get any valuable feedback :)




## Installation

  !ENTER MAIN DIRECTORY

First install pipenv if u don't have it yet.
```bash
  pip install pipenv
```

then set up virtual enviroment

```bash
  pipenv install
```

access enviroment

```bash
  pipenv shell
```
    
## Running Tests

To run tests, run the following command from ecommerce2/tests

```bash
  pipenv run pytest
```

## Tests Coverage

To see coverage please find index.html file in ecommerce2/tests/htmlcov


## Authors

- [@DSmolke](https://www.github.com/DSmolke)
