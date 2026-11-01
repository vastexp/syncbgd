# Privacy Policy — syncbgd

**Last updated: November 1, 2026**

## 1. Introduction

syncbgd is a free, open-source Linux application designed for personal backup of local files to Google Drive.

This Privacy Policy explains how syncbgd accesses, uses, and handles user information when interacting with Google services.

syncbgd is developed for personal, non-commercial use.

## 2. Information Accessed by the Application

Depending on the features enabled by the user, syncbgd may access the following information:

- Google account authorization information required for authentication.
- Google Drive files and folders necessary to perform backup operations.
- File names, file sizes, modification dates, and other metadata required for backup operations.
- OAuth access tokens and refresh tokens required to maintain authorized access to Google Drive.

The application only requests the permissions necessary for its intended functionality.

## 3. How Information Is Used

Information accessed by syncbgd is used exclusively to provide backup functionality.

Specifically, the application may:

- Authenticate the user with Google.
- Upload selected local files to Google Drive.
- Create and manage backup folders and files.
- Check file metadata to determine whether a backup is necessary.
- Maintain authorization to perform backup operations.

syncbgd does not use Google user data for advertising, marketing, profiling, or commercial purposes.

## 4. Data Storage and Sharing

syncbgd is designed as a local Linux application.

Files selected for backup are transferred from the user's local device directly to Google Drive using Google's official APIs.

The application does not operate its own cloud storage infrastructure or backend server for collecting user files.

OAuth credentials and tokens may be stored locally on the user's device to support authentication and subsequent backup operations.

syncbgd does not sell, rent, or share Google user data with third parties.

Google services process information in accordance with Google's own privacy policies and terms.

## 5. Google API Services

syncbgd uses Google API Services, including the Google Drive API.

The application's use and transfer of information received from Google APIs to any other application will adhere to the Google API Services User Data Policy, including the Limited Use requirements.

Google's Privacy Policy:

https://policies.google.com/privacy

Google API Services User Data Policy:

https://developers.google.com/terms/api-services-user-data-policy

## 6. Data Security

syncbgd uses Google's OAuth 2.0 authorization mechanism to access Google Drive.

Users authorize access through Google's official authorization process.

Users are responsible for protecting their Linux accounts, local devices, and any locally stored authentication credentials.

No software can guarantee absolute security.

## 7. Data Retention and Deletion

syncbgd does not maintain a separate server-side database of user files.

Backup files uploaded through the application remain in the user's Google Drive until the user deletes them.

Users can revoke syncbgd's access through their Google Account security settings:

https://myaccount.google.com/permissions

Users can also remove locally stored application credentials and tokens from their Linux device.

## 8. Children's Privacy

syncbgd is not specifically designed for children and does not knowingly collect personal information from children.

## 9. Changes to This Privacy Policy

This Privacy Policy may be updated when application functionality or data handling practices change.

The latest version will always be published in the project's GitHub repository.

## 10. Contact

For privacy-related questions or concerns, please open an issue in the official GitHub repository:

https://github.com/vastexp/syncbgd

---

syncbgd is an independent, non-commercial open-source project and is not affiliated with or endorsed by Google.
