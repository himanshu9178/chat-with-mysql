# Chat with MySQL

An interactive Streamlit app designed to facilitate SQL queries via conversational AI. The application uses AI models to generate SQL queries from natural language questions about your database schema, and then translates SQL responses back into natural language.

## Features

- Connects to a MySQL database using user credentials.
- Generates SQL queries from natural language using OpenAI's GPT models.
- Provides a conversational interface to interact with your database without directly writing SQL.

## Live Demo

You can view and interact with the live application here: [Chat with MySQL Streamlit App](https://chat-with-mysql-ta3dwnpsnw8ssuimmd3ja4.streamlit.app/).

## Screenshot

![Application Screenshot](Screenshot%202024-04-14%20231413.png)

## Requirements

To run this project, you will need:

- Python 3.6+
- Streamlit
- OpenAI API Key
- MySQL Database credentials

## Installation

Follow these steps to get the application running on your local machine:

1. Clone the GitHub repository:
   ```bash
   git clone https://github.com/himanshu9178/chat-with-mysql.git
   cd chat-with-mysql
2. Install the required Python libraries:

  ```bash
  pip install streamlit openai mysql-connector-python
```
3. Set up your environment variables (optional):
You may use a .env file to store your OpenAI API key and database credentials securely. Make sure to uncomment the relevant lines in the script if you choose to use environment variables or directly paste the API key on the interface page.
4. Run the application:

  ```bash
  streamlit run app.py
```
## Usage

After starting the app, you will need to input your MySQL database credentials and OpenAI API key into the interface. Once connected, you can start asking questions about your database in natural language. The app will convert these questions to SQL, execute them, and return the results in a conversational format.
