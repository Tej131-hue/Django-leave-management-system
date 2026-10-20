<p align="center">
<img width="800" src="./images/main_2.png">  
</p>


## Overview

The **Leave Management System** is a Django-based web application designed to simplify and organize employee leave management. It provides a centralized platform for submitting leave requests, tracking leave balances, and managing the approval workflow.

## Features

- **User Accounts**:
    Employees can log in to their accounts, view their leave balance, and manage their leave requests.

- **Leave Requests**:
    Employees can submit leave requests by selecting the required leave type and specifying the leave dates.

- **Approval Workflow**:
    Submitted leave requests can be reviewed and processed through the approval workflow, with requests supporting different statuses such as pending, approved, rejected, modified, and canceled.

- **Leave Balance Tracking**:
    The system displays available leave balances and helps track leave usage based on approved requests.

- **Request Management**:
    Users can view their submitted leave requests along with the request status, leave type, dates, and number of leave days.

- **Email Notifications**:
    The application supports email notifications to keep users informed about changes in their leave request status.


## Technology Stack

- **Backend:** Python, Django
- **Frontend:** HTML, CSS, JavaScript
- **Database:** PostgreSQL
- **Containerization:** Docker, Docker Compose
- **Version Control:** Git, GitHub


## Usage

[Setup the application](./docs/Setup.md)


## Project Setup

The application can be run locally using Docker and Docker Compose. The setup includes the Django application and PostgreSQL database, providing a consistent development environment.

For detailed installation and setup instructions, refer to the [Setup Guide](./docs/Setup.md).


## Project Structure

```text
Django-leave-management-system/
│
├── docs/                 # Project documentation
├── images/               # Application screenshots
├── src/                  # Django application source code
├── Dockerfile            # Docker image configuration
├── docker-compose.yaml   # Docker Compose configuration
├── requirements.txt      # Python dependencies
├── .gitignore
├── LICENSE
└── README.md
