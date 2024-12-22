# Hospital Management System

## Introduction
This is a **Java-based Hospital Management System** designed to manage patient records, diagnosis information, and billing details in a streamlined and user-friendly manner. The system allows users to:

- Log in as an authorized user.
- Record and update patient details.
- Add diagnosis information for patients.
- Retrieve patient history.
- Generate bills based on the provided services.

## Features

1. **Login System**:
   - Only authorized personnel can access the system by entering a valid username and password.

2. **Patient Details**:
   - Add new patient details, including their name, age, and contact number.
   - View and update existing patient records.

3. **Diagnosis Information**:
   - Record diagnosis details, including symptoms, prescriptions, and test results.
   - Update the diagnosis information for existing patients.

4. **Patient History**:
   - Retrieve and display the complete history of a patient, including personal details and diagnosis records.

5. **Billing**:
   - Generate detailed bills for patients based on the services rendered, including consultations, medications, and tests.

## Requirements
- **Java Development Kit (JDK)**: Version 8 or higher
- **Integrated Development Environment (IDE)**: IntelliJ IDEA, Eclipse, or any Java-compatible editor

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/hospital-management-system.git
   ```

2. Open the project in your preferred IDE.

3. Compile and run the `Main.java` file to start the application.

4. Follow the on-screen instructions to use the system.

## Code Structure

- **Main.java**:
  - Entry point of the application. Handles the menu and navigation between features.

- **Login.java**:
  - Manages the login system, verifying the username and password of authorized users.

- **PatientDetails.java**:
  - Handles CRUD operations for patient records.

- **Diagnosis.java**:
  - Manages the addition and retrieval of diagnosis details for patients.

- **Billing.java**:
  - Generates and displays bills based on services provided to patients.

## Sample Functionalities

### Adding a New Patient
```java
PatientDetails pd = new PatientDetails();
pd.addNewPatient("John Doe", 30, "123-456-7890");
```

### Recording Diagnosis Information
```java
Diagnosis diag = new Diagnosis();
diag.addDiagnosis("Fever", "Paracetamol", "Blood Test");
```

### Generating a Bill
```java
Billing bill = new Billing();
bill.generateBill(patientId);
```

## Screenshots
### Main Menu
![Main Menu](https://via.placeholder.com/800x400?text=Main+Menu)

### Add Patient Details
![Add Patient](https://via.placeholder.com/800x400?text=Add+Patient+Details)

### Generate Bill
![Generate Bill](https://via.placeholder.com/800x400?text=Generate+Bill)

## Future Enhancements
- Integration with a database for persistent data storage.
- Enhanced user interface using JavaFX or Swing.
- Multi-user support with role-based access control.

## Contributing
Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more information.

---

### Developer Contact
If you have any questions or suggestions, feel free to contact:

- **Name**: Shruti Gupta
- **Email**: gshruti779@gmail.com
- **GitHub**: [Shruti2026](https://github.com/Shruti2026)

---

