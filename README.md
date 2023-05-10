# User-Management-Screen-UI-Specification

The User Management Screen is designed to allow administrators to manage users within the system. This includes viewing user details, adding new users, editing existing users, and deleting users.

## Initial Screen State
When the User Management Screen is first loaded, a list of all users currently in the system is displayed in a table format. Each row represents one user and shows the following user details:

- ID
- User Name
- Email
- Enabled
Above the user list, there are two main interactive elements:
- ***New User Button***: Opens the "New User" dialog.
- ***Hide Disabled User Checkbox***: Hides disabled users.

## User List
The User List is displayed in a table with sortable columns for each user detail. By default, the list is sorted by User ID.

## New User
When the "New User" button is clicked, a dialog box opens with a form to enter the new user's details:

- Username (required, must be unique)
- Display Name (required)
- Phone (required)
- Email (required, must be unique)
- User Roles (required, select from predefined roles)
- Enabled

Upon clicking "Save User", the system validates the data:
- If all data is valid, the new user is created, the dialog is closed, and the user list is updated.
