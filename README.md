# **XiangNeng Smart Property Management System - Test Cases**
<div align="center">
  
  <img src="/public/PM_Testcases.gif" width="100%" alt="Chan Meng Snorkelling">
</div>

## **Overview**
This repository contains the **test cases** for the **XiangNeng Smart Property Management System**. These test cases ensure the system functions correctly, maintains data accuracy, and provides a seamless user experience. Each module is tested for critical functionality, validation scenarios, and edge cases.

---

## **Modules and Coverage**

### 1. **Building Management**
- Add, edit, and delete building information.
- Validate required fields and input constraints.
- Handle large building lists with pagination.

### 2. **Owner Management**
- Add and manage owner details, including required and optional fields.
- Query owners using filters such as name, phone, and ID.
- Validate pagination and ensure data accuracy in owner lists.

### 3. **Billing**
- Add and edit billing items with accurate calculations.
- Validate formulas used in billing.
- Manage property and owner invoices.

### 4. **Query Handling**
- Test search functionalities with exact, fuzzy, and incorrect inputs.
- Combine filters for complex queries.
- Validate data completeness and consistency across backend and frontend.

---

## **Repository Structure**

```plaintext
.
├── README.md               # Project overview and instructions
├── Documentation/          # System documentation and resources
│   ├── Requirements.pdf    # Functional requirements for the system
│   ├── TestPlan.md         # Overall testing plan
│   └── BugSummary.pdf      # Bug track report
```

### **Google Sheets Test Cases**
The detailed test cases are available as Google Sheets:
- [View Test Cases in Google Sheets](https://docs.google.com/spreadsheets/d/1d_qqttPVivKSL7Ls0hp1P4UVSwwHRLMy/edit?usp=sharing)

---

## **Test Case Structure**

Each test case follows this structured format for clarity and consistency:

| Field               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Test Case ID**    | Unique identifier for the test case.                                        |
| **Title**           | Brief description of what the test case validates.                         |
| **Priority Level**  | Importance of the test case (High, Medium, Low).                           |
| **Preconditions**   | Conditions that must be met before executing the test.                     |
| **Test Input**      | Input values or data used for the test.                                    |
| **Steps to Execute**| Step-by-step instructions for executing the test.                          |
| **Expected Result** | The expected outcome of the test.                                          |

---

## **Example Test Case**

### **Test Case: Add a Building Successfully**

| Field               | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| **Test Case ID**    | BM001                                                                      |
| **Title**           | Add a building with valid data.                                             |
| **Priority Level**  | High                                                                       |
| **Preconditions**   | System access is normal; user has property manager permissions.            |
| **Test Input**      | Building Code: `001`, Building Name: `Block A`, Building Area: `1000`.      |
| **Steps to Execute**| 1. Log in.<br>2. Navigate to **Building Information → Add Building**.<br>3. Enter valid inputs.<br>4. Click **Save**. |
| **Expected Result** | The building is added and displayed in the building list.                  |

---

## **How to Use This Repository**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gaon5/PMSystem.git
   cd PMSystem
   ```

2. **Access Test Cases**:
   - Use the [Google Sheets link](https://docs.google.com/spreadsheets/d/1d_qqttPVivKSL7Ls0hp1P4UVSwwHRLMy/edit?usp=sharing) for detailed test cases.

3. **Explore Documentation**:
   - Navigate to the `Documentation/` folder for system requirements, test plans, and bug summaries.

---

## **Contribution Guidelines**

We welcome contributions to improve the testing process. Please follow these steps:
1. Fork this repository.
2. Add or update test cases in the repository or Google Sheets.
3. Submit a pull request with a clear description of your changes.

---

