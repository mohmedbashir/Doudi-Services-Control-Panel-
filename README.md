
<img width="150" height="150" alt="app_icon" src="https://github.com/user-attachments/assets/7742ba0d-e6e4-4faa-b07c-42674de584eb" />

# Doudi Services (Control Panel)

A dedicated control panel for a mobile service center, built by **Flutter** designed to manage various service requests such as internet packages, SIM card issuance, router installation requests, and more. The panel receives incoming requests submitted by app users (branch managers), which are then processed accordingly—either fulfilled, escalated, or handled based on the type of service required.

## Key Features
* **User-Friendly Interface**: The control panel is designed with a clear and intuitive interface to ensure ease of use for all roles.
* **Role-Based Access Control**: The system includes a clear separation of duties with multiple access levels:
 
 • Administrator: Has full access, including adding, editing, or deleting users; modifying service details and pricing; managing payments; and viewing detailed reports.

 • Request Manager: Handles incoming service requests, forwards them to the appropriate departments, and verifies the completeness of submitted data.

 • Verification Officer: Responsible for contacting service requesters to confirm that services have been properly delivered, and updating the request status directly within the control panel.

* **Notifications System**: Real-time alerts are sent for critical actions, such as rejection of incomplete requests or reminders to branch managers regarding pending payments.
* **Requests Dashboard & Reporting**: A dedicated section provides detailed statistics on all service requests. Custom reports can be generated for requests and payments within a selected date range, with powerful filtering options available for granular analysis.

## Screenshots
**Home Page (Orders Page):**

<img width="626" alt="Orders Page Screenshot" src="https://github.com/user-attachments/assets/53317ce9-5284-4867-8896-29e38062716e" /> <img width="626" alt="Orders Page Screenshot 2" src="https://github.com/user-attachments/assets/e2da99df-e3aa-4222-8b89-4dff91a7e37e" />


**Payments Page:**

<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 14 27 PM" src="https://github.com/user-attachments/assets/56036364-7bc8-4ec8-94e6-31c5c3264bf5" />


**Reports Page:**

<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 14 52 PM" src="https://github.com/user-attachments/assets/c5e6eecc-2d0a-4273-84a3-f2b845d73fa0" />


**Charts Page:**

<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 15 03 PM" src="https://github.com/user-attachments/assets/ac44f682-079e-462f-adec-06c5334cfc5b" />
<img width="1920" height="1080" alt="Screenshot 2025-05-25 at 7 04 15 PM" src="https://github.com/user-attachments/assets/59f047b4-f85e-4ddc-b51e-8f8d02bbf20f" />


**Settings Page:**

<img width="1469" height="829" alt="Screenshot 2025-07-10 at 4 35 58 PM" src="https://github.com/user-attachments/assets/968e4c6e-3774-4b6d-98ce-a46c9993e5ad" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 19 27 PM" src="https://github.com/user-attachments/assets/d3e6e6c4-1171-4883-af20-aae7b2d5cf72" />



## Used Dependencies 
* **HTTP**: For making HTTP requests to fetch data from APIs.
* **getx**: For state management, routing, and dependency injection.
* **shared_preferences**:For storing small amounts of data locally on the device.
* **pdf**: For generating and manipulating PDF documents.
* **intl**: For internationalization, localization, and formatting dates, numbers, and currencies.
