# Personnel Database Management System

## Description

The **Personnel Database Management System** is a Windows Forms application designed to manage employee data within a company. It connects to a database and allows users to view, edit, and save employee records. The system utilizes data-binding to display employee information in a grid and provides functionalities for adding, updating, and deleting records.

## Features

- **View Employee Data**: Displays employee information in a data grid.
- **Edit Employee Records**: Allows modification of employee details directly in the grid.
- **Save Changes**: Saves changes made to employee records back to the database.
- **Database Integration**: Connects to a database and supports operations on the `Employee` table.
- **Data Binding**: Automatically updates the data grid when changes are made to the employee records.

## How It Works

1. **Data Display**:  
   Upon loading the application, employee data is fetched from the connected database and displayed in a data grid.

2. **Editing Records**:  
   Users can edit employee details directly in the data grid, such as name, department, position, and other attributes.

3. **Saving Changes**:  
   After making changes, users can save the modifications by clicking the **Save** button. The data will then be written back to the database.

4. **Binding and Updating**:  
   The application uses data binding to automatically update the employee records in the database.

## Installation

1. **Clone or Download the Repository**  
   Clone this repository or download the project files to your local machine.

2. **Open the Project in Visual Studio**  
   Open the project in Visual Studio.

3. **Set Up the Database**  
   Ensure that your local database is set up, and the connection string in the project is correctly configured to point to the database.

4. **Build the Project**  
   Build the project by selecting **Build** > **Build Solution**.

5. **Run the Application**  
   Once the application is built, run it by clicking **Start** in Visual Studio or executing the compiled `.exe` file.

## Usage

1. **Viewing Data**:  
   Upon starting the application, employee records will be displayed in a data grid.

2. **Editing Records**:  
   Modify employee details directly in the data grid (e.g., update the name, department, or position).

3. **Saving Changes**:  
   After editing, click the **Save** button to save the changes to the database.

4. **Exiting the Application**:  
   When you're done, exit the application by closing the form or using the exit option.

## Example

When the application loads, it will show employee data like this:

| Employee ID | Name          | Department | Position         | Salary  |
|-------------|---------------|------------|------------------|---------|
| 1           | John Doe      | HR         | Manager          | 50000   |
| 2           | Jane Smith    | IT         | Developer        | 60000   |

Users can click on any field in the data grid, modify the values, and click **Save** to store the changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
