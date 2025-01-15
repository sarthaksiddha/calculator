# Calculator Application

A simple calculator application that performs basic arithmetic operations.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with zero division handling)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sarthaksiddha/calculator.git
cd calculator
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

```python
from calculator import Calculator

# Create a calculator instance
calc = Calculator()

# Perform operations
result_add = calc.add(5, 3)      # Returns 8
result_sub = calc.subtract(5, 3)  # Returns 2
result_mul = calc.multiply(5, 3)  # Returns 15
result_div = calc.divide(6, 2)    # Returns 3
```

## Running Tests

To run the tests:
```bash
python -m pytest test_calculator.py
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.