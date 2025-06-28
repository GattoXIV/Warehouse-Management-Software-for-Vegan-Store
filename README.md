# BioMarket Inventory Management Software

A simple command-line inventory management software for a vegan product store, developed for BioMarket s.a.s.  
This program allows you to add products, list inventory, register sales, and calculate gross and net profits with data persistence.

## Features

- Add new products with name, quantity, purchase price, and sale price.
- List all products currently in stock.
- Register sales of one or multiple products, updating inventory accordingly.
- Calculate and display total gross and net profits.
- Command-line interface with help menu.
- Data persistence using a JSON file to keep data between sessions.
- Input validation and error handling for robust usage.

## Getting Started

### Prerequisites

- Python 3.6 or higher installed on your system.

### Installation

1. Clone this repository or download the source code.
2. Make sure the file `biomarket_data.json` is in the same folder as the script (it will be created automatically on first run if missing).
3. Run the program:

## Usage

The program accepts the following commands:

| Command  | Description                          |
|----------|------------------------------------|
| `add`    | Add a product to the inventory     |
| `list`   | List all products in inventory     |
| `sale`   | Register a completed sale           |
| `profits`| Show total gross and net profits   |
| `help`   | Show available commands            |
| `exit`   | Exit the program                   |


## Data Persistence

All product and sales data are saved in `biomarket_data.json` in the program folder, ensuring data is retained between runs.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements or bug fixes.

## License

This project is released under the MIT License.

---

*Developed for BioMarket s.a.s by [Gabriele Garattoni]*  
*Date: June 2025*
