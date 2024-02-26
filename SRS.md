**Software Requirements Specification (SRS)**
**Version 1.0**
**Date: February 26, 2024**

**1. Introduction**

This document serves as the Software Requirements Specification (SRS) for the development of a Todo List application. The purpose of this application is to provide users with the ability to manage their tasks effectively. The application will be built using the Django framework for the backend.

**1.1 Purpose**

The purpose of this document is to outline the functional requirements of the Todo List application.

**1.2 Scope**

The Todo List application will allow users to perform the following tasks:

- Display a list of todo items with their titles, descriptions, statuses, dates created, and dates updated.
- Add new todo items with validation for empty or invalid inputs.
- Edit existing todo items, including modifying titles, descriptions, and status (completed or not).
- Delete todo items with user confirmation.

**2. Functional Requirements**

**2.1 Display Todo List**

**Description:** The application shall fetch and display a list of todo items from the Django backend. Each item shall include a title, description, status (completed or not), date created, and date updated.

**2.2 Add New Todo**

**Description:** Users shall be able to enter the title and description of a new todo item. The application shall include validation to ensure that inputs are not empty or invalid.

**2.3 Edit Todo**

**Description:** Users shall have the ability to modify the title, description, and status of existing todo items. The status can be marked as completed or not completed.

**2.4 Delete Todo**

**Description:** Users shall be able to select a todo item and confirm its deletion. Once confirmed, the selected todo item shall be permanently removed from the list.
    