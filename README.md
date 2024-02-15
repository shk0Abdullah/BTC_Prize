```markdown
# Bitcoin Price Checker

This simple Python script retrieves the current price of Bitcoin in USD and calculates the value of a specified quantity of Bitcoin.
It utilizes the CoinDesk API to fetch the latest Bitcoin price.

## Usage

### Prerequisites
- Python 3.x
- Requests library (`pip install requests`)

### Command Line Arguments
The script accepts one command-line argument which specifies the amount of Bitcoin to convert to USD.

```
python main.py {amount of btc}
```

### Example
```
python main.py 0.5
```

This will output the value of 0.5 Bitcoin in USD.

## Functionality

The script performs the following steps:

1. Checks if a command-line argument is provided. If not, it prints a message indicating the missing argument.
2. Retrieves the current Bitcoin price in USD from the CoinDesk API.
3. Parses the command-line argument and converts it to a floating-point number.
4. Calculates the USD value of the specified quantity of Bitcoin.
5. Prints the result in USD with four decimal places.

## Error Handling

- If no command-line argument is provided, the script will exit and print a message.
- If the provided command-line argument is not a number, the script will print an error message.

## Disclaimer

This script provides information about the current price of Bitcoin for educational and informational purposes only. The actual price of Bitcoin may vary, and users should not rely solely on this script for financial decisions.

```
