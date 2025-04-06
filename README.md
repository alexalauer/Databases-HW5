# Homework 5 - CMSC408 - Fall 2024

## About The Project

This project involves exploring and documenting an HR database using Python, MySQL, and Quarto. The goal is to produce a comprehensive report that includes database structure, relationships, and sample data, as well as visual representations of the database schema.

## Built With

- **Python** - Programming language for data manipulation and queries.
- **MySQL** - Database management system for data storage and retrieval.
- **Quarto** - Tool for dynamic document generation and reporting.
- **Pandas** - Python library for data analysis.
- **SQLAlchemy** - SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **VS Code** - Code editor used for development with SQL extensions.

## Getting Started

Follow these steps to set up your environment and start working with the project.

### Prerequisites

- Python 3.9 or later
- Poetry (for managing dependencies)
- Quarto (for document rendering)
- VS Code (with SQL extensions for database interaction)

### Installation

1. Clone the repository:
   ```bash 
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install dependencies using Poetry:
    ```bast
   poetry install
   ```

3. Create a `.env` file in your home directory and add your MySQL credentials:
    ```bash
   USER=24FA_<your EID>
   PASSWORD=Shout4_<your EID>_JOY
   HOST=cmsc508.com
   DATABASE=24fa_hr_24fa_jdleonard
   ```

## Usage

To explore the database and generate reports:

1. Run the exploration script:
    ```bash
   quarto render report/explore.qmd
   ```

2. Complete the `report.qmd` file and render it:
    ```bash
   quarto render report/report.qmd
   ```

3. Submit the generated `report.html` file to Canvas and the repository to GradeScope.

## Roadmap

- [ ] Complete all queries in `explore.qmd`
- [ ] Finalize the report structure in `report.qmd`
- [ ] Create visual representations (Chen and Crow's Foot diagrams)
- [ ] Add sample data to the report


## License

This project is part of the CMSC408 course and is for educational purposes.

## Contact

For any questions or concerns, please contact:

- **Alexa Lauer** - [Email](lauera@vcu.edu)