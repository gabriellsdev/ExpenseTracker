# Credo

[![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactnative.dev/)
[![JavaScript](https://img.shields.io/badge/logo-javascript-blue?logo=javascript)]
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## About the Project

This is **Credo**, a personal financial management mobile app built with **React Native**, using **Supabase** as the backend for authentication and data persistence.

The project was developed entirely as part of a technical course in Systems Development, with the goal of consolidating skills in mobile development, full-stack integration, and UI design.

## Features

Credo offers a robust set of features for financial control:

### Financial Management

- **Transaction Tracking:** Easily add income and expenses.
- **Categorization:** Use predefined categories (e.g., Transport, Food, etc.).
- **Operation Details:** Add descriptions and values for each transaction.
- **Maintenance:** Edit and remove existing operations.
- **Visualization:** Clear and organized list of all transactions.

### Reminder System

- **Interactive Calendar:** View days with scheduled transactions or reminders.
- **Daily Filter:** Filtered view of operations and reminders by day.
- **Reminder Status:** Filters for active, inactive, and all reminders.
- **Scheduling:** Schedule with specific days and times.
- **Notifications:** Local notifications for reminders.

### Settings

- **Customization:** Light/dark mode.
- **Notifications:** Enable/disable notifications.
- **Information:** Access to app information.

### Authentication

- **Supabase Auth:** User registration and login.
- **Session Persistence:** User session maintenance.

## Technologies Used

| Category | Technology | Description |
| :--- | :--- | :--- |
| **Front-end** | React Native, Expo | Cross-platform mobile development. |
| | React Navigation | Screen navigation. |
| | React Hook Form, Hooks | Form and state management. |
| | Async Storage | Local data storage. |
| **Back-end / Infra** | Supabase (Auth + Postgres) | Backend-as-a-Service, authentication, and relational database. |
| | Data Modeling | Optimized table structure. |
| | Access Policies | Security rules and access policies. |
| **Tools & Dev** | WSL, Android SDK | Setup for Android builds and local development. |
| | Manual Testing | Structured manual testing. |
| | Eslint/Prettier | Linting and code formatting tools (if applicable). |

## How to Run the Project

Follow the steps below to set up and run the project on your machine:

### 1. Clone the Repository

```bash
git clone https://github.com/gabriellsdev/ExpenseTracker.git
cd ExpenseTracker
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Project

```bash
npx expo start
```

## Android Build (APK / AAB)

To generate the Android app build, you can use EAS (Expo Application Services) or run a local build:

### Option 1: Using EAS

```bash
eas build -p android --profile preview
```

### Option 2: Local Build (Requires WSL/Android SDK setup)

```bash
eas build --platform android --local --profile preview
```
