
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
<img width="626" alt="Screenshot 2025-05-24 at 8:13:51 PM" src="https://github.com/user-attachments/assets/53317ce9-5284-4867-8896-29e38062716e" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 21 34 PM" src="[https://github.com/user-attachments/assets/1d54cd5f-8217-4b5b-bb6d-0b812becbd92](https://github.com/user-attachments/assets/5f7bdf47-6c98-4f4b-bfef-95d824c68eca)" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 14 27 PM" src="https://github.com/user-attachments/assets/1d54cd5f-8217-4b5b-bb6d-0b812becbd92" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 14 27 PM" src="https://github.com/user-attachments/assets/1a320b93-538a-4278-b321-3f6b31a4eb0d" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 15 03 PM" src="https://github.com/user-attachments/assets/b4bfeb3f-9149-42c9-9cba-9c8a8858b594" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 19 27 PM" src="https://github.com/user-attachments/assets/9568e242-73d1-4b00-82b3-d85cd59740e4" />
<img width="1920" height="1080" alt="Screenshot 2025-05-24 at 8 19 46 PM" src="https://github.com/user-attachments/assets/1dba400e-2423-4610-b654-0ccc0dbb0687" />
<img width="1920" height="1080" alt="Screenshot 2025-05-25 at 7 04 15 PM" src="https://github.com/user-attachments/assets/4d8dbf3e-b2f5-4cc4-87f8-b6ac3336a330" />

## Used Dependencies 
* **HTTP**: For making HTTP requests to fetch data from APIs.
* **getx**: For state management, routing, and dependency injection.
* **shared_preferences**:For storing small amounts of data locally on the device.
* **pdf**: For generating and manipulating PDF documents.
* **intl**: For internationalization, localization, and formatting dates, numbers, and currencies.
