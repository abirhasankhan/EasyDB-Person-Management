# EasyDB-Person-Management

## Overview

This project is designed to manage a simple database of persons using SQL commands and text file operations. It allows for the creation, insertion, selection, and deletion of person records. The data is stored in a structured format, making it easy to read and manage.

## Features

- Create a `Person` table with fields for `PersonID`, `LastName`, `FirstName`, `Address`, and `City`.
- Insert new person records into the database.
- Select and display all person records from the database.
- Clear all data from the associated text file.

## Technologies Used

- Python
- SQL
- Google Colab
- Google Drive

## Getting Started

### Prerequisites

- A Google account to access Google Drive.
- Google Colab for running the Jupyter Notebook.

### Installation

1. Clone the repository or download the Jupyter Notebook file.
2. Upload the file to Google Colab.
3. Mount your Google Drive in the notebook to access files.

### Usage

1. Run the notebook cells to create the `Person` table.
2. Follow the prompts to insert new person records.
3. Use the provided functions to select and manage records as needed.

## Functions

- `create_table()`: Creates the `Person` table in the database.
- `insert_person()`: Prompts for person data and inserts it into the database.
- `select_person()`: Retrieves and displays all records from the `Person` table.
- `remove_data_from_file()`: Clears all data from the `Person.txt` file.

## File Structure

- `Person.txt`: Stores person records in a structured format.
- Jupyter Notebook: Contains the SQL commands and functions for database management.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the need for a simple person database management system.


