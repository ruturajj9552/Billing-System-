# Grocery Billing System

A simple desktop-based **Grocery Billing System** developed using **Python and Tkinter**. This application provides a graphical interface to enter customer details, select product quantities, calculate category-wise prices and taxes, and generate a bill.

## Features

- Customer name and contact number input
- Automatic bill number generation
- Product quantity entry
- Product categories:
  - Snacks
  - Grocery
  - Beauty & Hygiene
- Automatic product price calculation
- Category-wise tax calculation
- Total bill amount calculation
- Bill preview area
- Clear fields functionality
- Exit functionality
- Simple and user-friendly GUI

## Technologies Used

- **Python 3**
- **Tkinter**
- **random module**
- **os module**
- **sys module**

## Project Structure

```text
Grocery-Billing-System/
│
├── billing_system.py
└── README.md
```

> Note: Replace `billing_system.py` with the actual name of your Python file if it is different.

## Requirements

- Python 3.x
- Tkinter

Tkinter is included with most standard Python installations.

## Installation and Setup

### 1. Install Python

Download and install Python from:

https://www.python.org/downloads/

During installation, select **Add Python to PATH**.

### 2. Clone the Repository

```bash
git clone https://github.com/Ruturaj Jadhav/grocery-billing-system.git
```

### 3. Open the Project Directory

```bash
cd grocery-billing-system
```

### 4. Run the Application

```bash
python billing_system.py
```

For some systems, use:

```bash
python3 billing_system.py
```

## How to Use

1. Start the application.
2. Enter the customer name.
3. Enter the customer contact number.
4. Enter the quantity of the required products.
5. Click the **Total Bill** button.
6. View the generated bill in the Bill Area.
7. Click **Clear Field** to reset the entered data.
8. Click **Exit** to close the application.

## Product Categories

### Snacks

- Nutella Choco Spread
- Noodles
- Lays
- Oreo
- Chocolate Muffin
- Dairy Milk Silk
- Namkeen

### Grocery

- Aashirvaad Atta
- Pasta
- Basmathi Rice
- Sunflower Oil
- Refined Sugar
- Daal
- Tea Powder

### Beauty & Hygiene

- Bathing Soap
- Shampoo
- Body Lotion
- Face Cream
- Shaving Foam
- Face Mask
- Hand Sanitizer

## Tax Calculation

The application applies the following tax rates:

| Category | Tax Rate |
|----------|----------|
| Snacks | 5% |
| Grocery | 1% |
| Beauty & Hygiene | 10% |

The total bill is calculated as:

```text
Total Bill = Total Product Prices + Category-wise Taxes
```

## Future Enhancements

- Add a login and authentication system
- Add database integration
- Add product and inventory management
- Add invoice printing
- Export bills to PDF
- Add date and time to the bill
- Add discounts and offers
- Add multiple payment methods
- Improve the graphical interface

## Author

**Ruturaj Jadhav**

## License

This project is licensed under the MIT License.

Copyright (c) 2026 Ruturaj Jadhav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
