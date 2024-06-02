# **Blood Bank Management System**

## **Overview**
The Blood Bank Management System is a robust application developed using Python and Django to streamline the management of blood donations, inventory, and requests. This system is designed to enhance the efficiency of blood banks by providing a comprehensive platform for tracking donors, patients, and blood stock.

## **Table of Contents**
- [Introduction](#introduction)
- [Admin Features](#admin-features)
- [Donor Features](#donor-features)
- [Patient Features](#patient-features)
- [Installation Guide](#installation-guide)
- [Usage Instructions](#usage-instructions)
- [Required Dependencies](#required-dependencies)
- [Contributing Guidelines](#contributing-guidelines)
- [License Information](#license-information)


## **Introduction**
Managing a blood bank involves numerous tasks such as registering donors, handling donations, maintaining inventory, and processing blood requests. This Blood Bank Management System provides an integrated solution to efficiently handle all these operations from a single platform.


## **Admin Features**
- **Create Admin Account:** Set up an admin account using:
```bash
py manage.py createsuperuser
```
Dashboard: Monitor blood units by group, donor count, blood requests, approved requests, and total stock.
Manage Donors: View, edit, and delete donor information.
Manage Patients: View, edit, and delete patient details.
Approve/Reject Donations: Evaluate donation requests based on health criteria and update blood stock accordingly.
Approve/Reject Blood Requests: Process blood requests and adjust inventory.
Track History: Maintain a detailed history of all blood requests.
Update Inventory: Adjust the quantity of specific blood groups as needed.
## **Donor Features**
**Registration:** Donors can sign up by providing basic information.

**Donate Blood:** Submit donation requests and track their approval status.

**Request Blood:** Request blood units and view request history.

**Dashboard:** View statistics on blood donation and request statuses.

## **Patient Features**
**Registration:** Patients can create accounts without admin approval.

**Request Blood:** Submit blood requests and track their approval status.

**Dashboard:** View the status of blood requests made.

## **Installation Guide**
**Install Python (3.7.6):** Ensure Python is added to the system PATH.

**Download and Extract Project:** Obtain the project zip file and extract it.

**Navigate to Project Directory:**

```bash
cd bloodbankmanagement
```
Install Required Packages:
```bash
python -m pip install -r requirements.txt
```
Set Up Database:
```bash
py manage.py makemigrations
py manage.py migrate
```
Start the Server:
```bash
py manage.py runserver
```
Access the Application: Open ```http://127.0.0.1:8000/``` in your web browser.
#Usage Instructions
Admin Configuration:
Create an admin account and log in to access the admin dashboard.
User Registration:
Donors and patients can register and log in to use their respective features.
Required Dependencies
The following dependencies are necessary to run the Blood Bank Management System:

Django
SQLite
Other packages listed in requirements.txt
Install them with:

bash
Copy code
pip install -r requirements.txt

#Contributing Guidelines
We welcome contributions! Please fork the repository, make your changes, and submit a pull request.

#License Information
This project is licensed under the MIT License. See the LICENSE file for more details.
