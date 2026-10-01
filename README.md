# Vending Machine System

A Java-based vending machine simulation that handles product inventory, coin management, and purchase transactions with change calculation.


## How It Works

1. **Add products** - Stock the machine with products and quantities
2. **Refill coins** - Add coins to the machine for making change
3. **Insert coins** - User inserts coins to purchase a product
4. **Purchase** - System validates stock, payment, and returns change
5. **Change calculation** - Automatically calculates and returns change using available coins

## Running the Tests

The project includes JUnit tests that verify all functionality:
- Product management (add, restock, reduce)
- Coin operations (insert, refill, calculate totals)
- Purchase scenarios (successful purchase, insufficient funds, out of stock, cannot make change)

Compile and run the test file to verify the system works correctly.

## Project Structure

- **VendingMachine.java** - Main vending machine logic
- **Product.java** - Product model (id, name, price)
- **Coin.java** - Coin enumeration with values
- **VendingMachineTest.java** - Unit tests
- **Main.java** - Entry point (currently empty)

