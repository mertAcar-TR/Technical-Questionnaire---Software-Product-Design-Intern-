# User Management Screen Interface Specification

## Overview
The user management screen provides functionality to manage users within the system. This document outlines the requirements and details of the user interface (UI) components for this screen.

## Requirements
- Display a top navigation bar with the following components:
  - "Add New User" button: Allows the user to add a new user.
  - "Hide Disabled Users" checkbox: Filters out disabled users from the user list.
  - "Save Users" button: Saves any changes made to user data.

- Display a user list table with the following columns:
  - ID: Unique identifier of the user.
  - Username: User's username.
  - Email: User's email address.
  - Enabled: Indicates whether the user account is enabled or disabled.

- Provide a user details section on the right-hand side for adding or editing users:
  - Username: Textbox for entering the username.
  - Display Name: Textbox for entering the display name.
  - Phone: Textbox for entering the user's phone number.
  - Email: Textbox for entering the user's email address.
  - User Role: Dropdown or radio buttons for selecting the user role (Guest, Admin, SuperAdmin).
  - Enabled: Checkbox to enable or disable the user account.

## Initial Display
- When the user navigates to the user management screen:
  - The list of users (from the database) is displayed in the table.
  - All users are shown initially, regardless of their enabled/disabled status.
  - The user details section is empty or shows default values for adding a new user.

## Component Behavior
- "Add New User" button:
  - Opens the user details section with empty fields to add a new user.

- "Hide Disabled Users" checkbox:
  - Toggles the visibility of disabled users in the user list.

- "Save Users" button:
  - Saves any changes made to user data in the user details section.

## UI Layout
The screen layout should be divided into two sections:
- Left Section: User list table.
- Right Section: User details section for adding/editing users.



