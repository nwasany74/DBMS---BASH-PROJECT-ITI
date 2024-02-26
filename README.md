# H.N.D.B.M.S (Home Network Database Management System)

## Overview

**H.N.D.B.M.S** is a simple database management system designed to work on a Unix/Linux environment, specifically for managing databases and tables within a home network. It offers the following functionalities:

- **Create Database**: Create a new database with a unique name.
- **Connect Database**: Connect to an existing database.
- **Drop Database**: Drop an existing database.
- **List Database**: List all available databases.
- **Create Table**: Create a new table within a database.
- **Select Table**: Select and display the contents of a table.
- **Drop Table**: Drop an existing table within a database.
- **Update Data**: Update existing data in a table.
- **Insert Data**: Insert new data into a table.
- **Delete Data**: Delete existing data from a table.

## Prerequisites

- Unix/Linux operating system
- Bash shell (version 4 or higher recommended)

## Installation

1. Clone the repository: `git clone <repository_url>`
2. Navigate to the HNDBMS directory: `cd HNDBMS`
3. Make the shell scripts executable: `chmod +x main.sh Scripts/*.sh`

## Usage

- Run `main.sh` to start the H.N.D.B.M.S shell.
- Follow the on-screen menu to perform actions such as creating, connecting to, or dropping a database, listing databases, or exiting the system.
- When creating a database, you will be prompted to enter a unique name for the database.
- When connecting to a database, select an existing database from the list.
- When dropping a database, select a database from the list.
- Tables can be created, selected, dropped, updated, inserted into, and deleted from within the selected database.

## Scripts

- **main.sh**: The main script that provides a menu-driven interface for accessing database functionalities.
- **create_db.sh**: Script to create a new database.
- **connect_db.sh**: Script to connect to an existing database.
- **drop_db.sh**: Script to drop an existing database.
- **list_db.sh**: Script to list all available databases.
- **create_table.sh**: Script to create a new table within a database.
- **select_table.sh**: Script to select and display the contents of a table.
- **drop_table.sh**: Script to drop an existing table within a database.
- **update_data.sh**: Script to update existing data in a table.
- **insert_data.sh**: Script to insert new data into a table.
- **delete_data.sh**: Script to delete existing data from a table.
- **DatabaseMenu.sh**: Provides a menu-driven interface for performing table-related operations within a selected database.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Authors

- Ibrahim ELnwasansy
- Mahmoud Hatem
- Ahmed Hatem

For further assistance or inquiries, please contact ibrahimalnwasany@gmail.com.
