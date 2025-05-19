
# Coffee Shop 

## Description
Python project using OOP principles to model a coffee shop domain. It consists of three main entities: `Customer`, `Coffee`, and `Order`, with defined relationships between them.
## Features
- A `Customer` can place many `Orders`.
- A `Coffee` can have many `Orders`.
- An `Order` belongs to one `Customer` and one `Coffee`.
## methods
- Many-to-many relationships
- Input validation and exception handling
- Aggregation and association methods
- Class-level methods (e.g., most aficionado)
- Unit tests using Pytest

## Setup and Installation

1. **Clone the Repository:**
   ```bash
   git clone git@github.com:shazzar0137/coffee_shop.git
   cd coffee_shop
   ```

2. **Set Up a Virtual Environment:**
   ```bash
   pipenv install
   pipenv shell
   ```

3. **Install Dependencies:**
   ```bash
   pipenv install pytest
   ```

## Run
```bash
python debug.py
```

## Tests
```bash
pytest
```

## Author
Daniel Kipngetich.

## Folder Structure

```
coffee_shop/
├── coffee.py
├── customer.py
├── order.py
├── debug.py
├── tests/
│   ├── test_coffee.py
│   ├── test_customer.py
│   └── test_order.py
|    |__ __init__.py  
└── README.md
```

## License

This project is licensed under the MIT License. Feel free to use and modify the code as needed for your projects.
