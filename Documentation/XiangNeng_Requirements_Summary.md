# XiangNeng Smart Property Management System - Requirements Summary

## System Overview
The XiangNeng Smart Property Management System is a comprehensive platform for managing properties, owners, billing, and query functionalities. It is designed for use by property managers, agents, and owners, providing tools for efficient and streamlined operations.

---

## Core Functionalities
1. **Building Management**:
   - Add, edit, and delete building information.
   - Validate required fields such as building code, name, and area.
   - Support for pagination in building lists.

2. **Owner Management**:
   - Add and manage owner information with fields like name, gender, phone, and ID.
   - Query owners using filters such as name, phone, and property number.
   - Validation of required fields and pagination for large datasets.

3. **Billing and Payments**:
   - Add and manage billing items (e.g., property fees, deposits).
   - Generate periodic invoices for properties, units, and owners.
   - Validate dynamic billing formulas and calculations.

4. **Query and Search**:
   - Comprehensive search capabilities with exact, fuzzy, and incorrect inputs.
   - Combine filters for advanced searches (e.g., name + phone + ID).
   - Validate data completeness and correctness by cross-checking with backend records.

---

## User Roles
1. **Property Manager**:
   - Full access to all modules for managing properties, owners, and billing.
2. **Owner**:
   - Limited access to view personal property and billing information.
3. **Agent**:
   - Restricted access for property and owner management.

---

## System Validation Points
1. **Input Validation**:
   - Check for empty, invalid, or malformed inputs in all modules.
   - Ensure fields like name, phone, and area meet length and format requirements.

2. **Error Handling**:
   - Provide clear error messages for incorrect or missing inputs.
   - Prevent invalid data from being saved.

3. **Pagination**:
   - Ensure large datasets are paginated for usability.
   - Validate that all data is accessible via pagination.

4. **Data Integrity**:
   - Ensure data accuracy and completeness in frontend displays.
   - Cross-check displayed data with backend or database records.

---

## Technical Requirements
- **Frontend**: Web-based user interface with clear navigation and responsive design.
- **Backend**: Robust backend for handling data operations and queries.
- **Database**: Reliable storage for property, owner, and billing information.
- **Performance**: Support large datasets and handle concurrent users without performance degradation.
