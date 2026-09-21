# Community Welfare Support at CHANGE Trust

## Project Overview
A web-based welfare management system developed for CHANGE Trust to digitally manage welfare-related information and administrative activities.

The system includes resident records, weekly food menus, events, documents, messages, and administrative functions. Firebase Firestore is used as the cloud database and backend service for supported data synchronization.

## Objectives
- Digitally organize welfare-related information.
- Manage resident records in an organized way.
- Manage weekly breakfast, lunch, and dinner menus.
- Maintain a calendar of events and special occasions.
- Support cloud-based synchronization across devices.
- Reduce manual paper-based record maintenance.

## Main Features
### Admin Portal
Provides administrative access to manage website information.

### Resident Management
- Add and manage resident information.
- Maintain basic welfare-related records.
- View stored resident details.

### Food Menu
- Separate Food Menu section.
- Monday to Sunday weekly schedule.
- Breakfast, lunch, and dinner entries.
- Regular Tamil-style meals and special/non-vegetarian meals can be maintained.

### Calendar & Events
- Add and manage events.
- Record festivals and special occasions.
- Examples: Pongal, Deepavali, birthdays, medical camps, and meetings.

### Documents and Records
Digital management of welfare-related records and documents.

### Messages
Management of website messages and information.

### Cloud Synchronization
Firebase Firestore provides cloud storage and synchronization for supported application data.

## Technologies Used
| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Design and styling |
| JavaScript | Functionality and interaction |
| Firebase | Cloud backend services |
| Firebase Firestore | Cloud database and synchronization |
| Netlify | Hosting/deployment |

## System Architecture
```text
User
  ↓
HTML / CSS / JavaScript Website
  ↓
Firebase
  ↓
Cloud Firestore
  ↓
Stored & Synchronized Data
```

The project does not use a separately developed backend server. Firebase provides the required backend services and cloud database.

## Firebase
**Firebase Project:** Welfare system

Firebase Web SDK is configured in the website and Firestore is used for cloud data storage.

> Do not store administrator passwords or other private credentials in this README.

## Admin Login
The website contains an administrator login system.

For security, the administrator password is not included in this README. Credentials should be shared separately for demonstration when required.

## Project Structure
```text
CHANGE-Trust-Welfare-System/
│
├── change_trust_website.html
└── README.md
```

The HTML file contains the website interface, styling, JavaScript functionality, and Firebase integration.

## How to Run
1. Download the project files.
2. Keep the HTML file and README in the project folder.
3. Open the HTML file in a modern web browser.
4. Open the Admin Portal when administrative access is required.
5. Ensure the Firebase configuration is connected correctly.

## Deployment
The website can be deployed using a static hosting service such as Netlify.

1. Log in to Netlify.
2. Upload/deploy the website project.
3. Open the generated website URL.
4. Verify the Firebase-connected features.

## Database
The application uses **Cloud Firestore**, a NoSQL cloud database provided by Firebase.

Application data may include:
- Residents
- Food Menu
- Events
- Documents
- Messages
- Settings
- Activity/record information

## Data Synchronization
Supported information is stored in Firebase Firestore. When data is updated through the website, other devices connected to the same application can access the updated cloud data.

## Advantages
- Simple user interface.
- Digital welfare information management.
- Cloud-based data storage.
- Multi-device access for synchronized data.
- Easy weekly food-menu management.
- Easy event and festival management.
- Reduces manual record maintenance.
- Can be deployed as a web application.

## Future Enhancements
- Role-based login for multiple administrators.
- Firebase Authentication.
- Automated backup and data export.
- Resident search and filtering.
- Reports and statistics.
- Mobile application version.
- Improved Firestore security rules.
- Event notifications.
- Firebase Storage for photos and documents.

## Conclusion
The CHANGE Trust Welfare Management System provides a simple digital platform for organizing welfare information and administrative activities.

By combining a web frontend with Firebase Firestore, the project provides cloud-based data management and synchronization without requiring a separately developed backend server.

## Project Information
**Project Title:** Community Welfare Support at CHANGE Trust  
**Project Type:** Web Application  
**Frontend:** HTML, CSS, JavaScript  
**Backend Service:** Firebase  
**Database:** Firebase Firestore  
**Hosting:** Netlify  
**Application Area:** Community Welfare / NGO Management
