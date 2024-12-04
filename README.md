

# XiangNeng Smart Property Management System - Test Cases

## Overview

This repository contains the **test cases** for the **XiangNeng Smart Property Management System**. These test cases are designed to validate the system's functionality, ensure data accuracy, and maintain user experience quality. Each module is tested for core functionality, validation scenarios, and edge cases.

---

## Modules and Coverage

### 1. **Building Management**
Test cases in this module cover:
- Adding, editing, and deleting building information.
- Validation of required fields and input constraints.
- Pagination for large building lists.

### 2. **Owner Management**
Test cases in this module cover:
- Adding and managing owner information with required and optional fields.
- Querying owners with various filters (e.g., name, phone, ID).
- Validation of pagination and data accuracy for owner lists.

### 3. **Billing**
Test cases in this module cover:
- Adding and editing billing items.
- Validation of billing calculations and formulas.
- Managing invoices for properties and owners.

### 4. **Query Handling**
Test cases in this module cover:
- Search functionalities with exact, fuzzy, and incorrect inputs.
- Combined filter queries for complex searches.
- Validation of data completeness and correctness across backend and frontend.


## Repository Structure

```
.
├── README.md               # Project overview and instructions
├── TestCases/              # Directory for test cases
│   ├── BuildingManagement.md  # Test cases for building management
│   ├── OwnerManagement.md     # Test cases for owner management
│   ├── Billing.md             # Test cases for billing and payments
│   ├── QueryHandling.md       # Test cases for query handling
└── Documentation/          # System documentation and resources
    ├── Requirements.pdf    # Functional requirements for the system
    ├── TestPlan.md         # Overall testing plan
    └── BugSummary.pdf  # Bug Track Report
```

---

## Test Case Structure

Each test case is documented with the following format:

| Field               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Test Case ID**    | Unique identifier for the test case                                        |
| **Title**           | Brief description of what the test case validates                         |
| **Priority Level**  | Importance of the test case (High, Medium, Low)                           |
| **Preconditions**   | Conditions that must be met before executing the test                     |
| **Test Input**      | Input values or data used for the test                                    |
| **Steps to Execute**| Step-by-step instructions for executing the test                          |
| **Expected Result** | The expected outcome of the test                                          |

---

## Example Test Case

### Test Case: Add a Building Successfully

| Field               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Test Case ID**    | BM001                                                                      |
| **Title**           | Add a building with valid data                                             |
| **Priority Level**  | High                                                                       |
| **Preconditions**   | System access is normal; user has property manager permissions.            |
| **Test Input**      | Building Code: `001`, Building Name: `Block A`, Building Area: `1000`.      |
| **Steps to Execute**| 1. Log in.<br>2. Navigate to **Building Information → Add Building**.<br>3. Enter valid inputs.<br>4. Click **Save**. |
| **Expected Result** | The building is added and displayed in the building list.                  |

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/gaon5/PMSystem
   cd your-repo
   ```

2. Navigate to the `TestCases` directory for detailed test cases.

3. Use the `Documentation/` folder for system requirements and testing plans.

---

## Contribution

We welcome contributions! Please follow these steps:
1. Fork this repository.
2. Add or edit test cases.
3. Submit a pull request with a description of your changes.

---

