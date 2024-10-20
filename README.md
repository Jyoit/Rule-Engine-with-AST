# Rule-Engine-with-AST- Jyoti

## Project Description

This project implements a **Rule Engine** using Python that can create, combine, and evaluate rules in the form of **Abstract Syntax Trees (AST)**. The engine allows dynamic modification of rules by altering operators, operands, or adding/removing sub-expressions within the AST. Additionally, the project includes test cases to validate the rule engine's functionality.

### Key Features:
- **Rule Creation**: Users can define rules like `age == 30`.
- **Rule Combination**: Combine rules using logical operators (e.g., `AND`, `OR`).
- **Rule Evaluation**: The engine evaluates rules against input data.
- **Dynamic Rule Modification**: Modify rules at runtime (e.g., change operators, operand values, or sub-expressions).

---

## Design Choices

The engine is built using an `ASTNode` class to represent individual rules, enabling flexible and dynamic rule creation and evaluation. The rules consist of:
- **Left Operand**: The field (e.g., `age`).
- **Operator**: Logical operators like `==`, `!=`, `>`, `<`.
- **Right Operand**: The value being compared against.

Rules are evaluated based on the input data and return a boolean (`True` or `False`).

---

## Project Structure

```bash
├── main.py          # Main application file 
├── rule_engine.py   # Core rule engine implementation 
├── test_cases.py    # Test cases to validate the rule engine
├── requirements.txt # List of dependencies 
└── README.md        # Project documentation
