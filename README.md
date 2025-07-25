# Library Manager

A simple C++ console-based Library Management System for managing Books, DVDs, and Magazines. This application allows users to add new items to a library, store their details in a CSV file, and display existing records by category.

## Features

- **Add Items:** Supports adding Books, DVDs, and Magazines with relevant details.
- **View Records:** Display all records of Books, DVDs, or Magazines.
- **CSV Storage:** All data is stored in a `Library.csv` file for persistence.
- **Menu-driven UI:** Easy-to-use console interface.

> **Note:**  
> This program writes to `d:/Library.csv` by default. Make sure the directory exists or modify the code for your preferred path.

### 3. Menu Options

- `1` : Add a Book
- `2` : Add a DVD
- `3` : Add a Magazine
- `4` : Display Book records
- `5` : Display DVD records
- `6` : Display Magazine records
- `0` : Exit the program

## Data Format

The `Library.csv` file will contain records in the following format:

Category,Title,Author,Year,Publisher/Studio,Genre,Director,Pages,issueNumber,Runtime
Book,Title,Author,Year,Publisher,Genre,N.A.,Pages,N.A.,N.A.
DVD,Title,Author,Year,Studio,Genre,Director,N.A.,N.A.,Runtime
Magazine,Title,Author,Year,Publisher,N.A.,N.A.,N.A.,issueNumber,N.A.