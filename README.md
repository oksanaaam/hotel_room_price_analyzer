# Hotel Room Price Analyzer

This script processes hotel room data from a JSON file, finds the room with the lowest price, calculates total prices for all rooms including taxes, and saves the output to a file.

## Features

- Finds the room type, number of guest with the lowest price (without using the `min` function).
- Calculates the total price (Net price + taxes) for all rooms.
- Outputs results to a JSON file.

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/oksanaaam/hotel_room_price_analyzer.git
    cd hotel-room-price-analyzer
    ```
2. Install dependencies, this project uses Python 3.

## Usage

To run the script, execute:

```
python main.py
```

## Running Tests

To run the unit tests:

```
python -m unittest discover tests
or 
python -m unittest tests/test_main.py
```

## Output

The results will be printed and saved to output.json in the same directory.

Printed results:   
![img.png](images/printed_results.png)
