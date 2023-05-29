# CSV Agent for Data Analysis (SQLite)

This is an AI-powered data analysis tool that reads a CSV file, imports the data into a SQLite database, and provides a conversational interface for querying the data using natural language. It uses the `OpenAI` model for natural language understanding and `SQLDatabaseToolkit` from `langchain` for database operations.

## Features
* Upload CSV file and create a SQLite database.
* Infer column types from CSV file and create appropriate SQLite schema.
* Provide conversational interface to query data in natural language.
* Secure OpenAI API Key input.
* Download the generated SQLite database.

## Prerequisites

* Python 3.6+
* Streamlit
* Pandas
* SQLAlchemy
* SQLite
* OpenAI API Key

## Usage

1. Navigate to the directory where this script is located.
2. Run `streamlit run app.py`.
3. The application will run in your default web browser.
4. Enter your OpenAI API key.
5. Upload a CSV file. The script will automatically create a SQLite database and infer the schema from the CSV file.
6. You can now enter your queries in natural language in the text box. The OpenAI model will interpret your queries and provide answers based on the data in your SQLite database.
7. You can download the SQLite database by clicking on the "Download SQLite Database" link.

## Notes
* Please ensure that you enter a valid OpenAI API key, or the AI model won't work.
* CSV files should be well-formatted. Improperly formatted files may cause errors.
* The generated SQLite database is not persistent and will be deleted when the Streamlit session ends.

## Support

For any questions or concerns, please raise an issue in this repository or reach out on [Twitter](https://twitter.com/datamokotow) or [GitHub](https://github.com/datamokotow/).

## License

This project is licensed under the MIT License. See the LICENSE file for details.
