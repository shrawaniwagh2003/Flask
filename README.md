# Flask Mathematics Problem Solver

This Flask web application serves as a Mathematics Problem Solver API. It allows users to perform basic mathematical operations such as summation, subtraction, and multiplication through simple API endpoints.

## Operations

### Summation
- **Endpoint:** `/sum`
- **Parameters:**
  - `num1` (float): First number
  - `num2` (float): Second number
- **Example Usage:**
  ```
  http://localhost:8080/sum?num1=5&num2=3
  ```
  Returns the sum of the two numbers.

### Subtraction
- **Endpoint:** `/sub`
- **Parameters:**
  - `num1` (float): First number
  - `num2` (float): Second number
- **Example Usage:**
  ```
  http://localhost:8080/sub?num1=8&num2=3
  ```
  Returns the result of subtracting `num2` from `num1`.

### Multiplication
- **Endpoint:** `/mul`
- **Parameters:**
  - `num1` (float): First number
  - `num2` (float): Second number
- **Example Usage:**
  ```
  http://localhost:8080/mul?num1=4&num2=7
  ```
  Returns the product of the two numbers.

## Getting Started

### Prerequisites

- Python 3.x
- Flask

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/flask-math-problem-solver.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flask-math-problem-solver
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open your web browser or use a tool like `curl` or `Postman` to make API requests to the provided endpoints.

3. Explore the API by performing summation, subtraction, and multiplication operations.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
