# Dictionary API

This is a simple Flask application that serves as a dictionary API. It provides the definition of words stored in a CSV file named `dictionary.csv`.

## Requirements

- Python 3.x
- Flask
- pandas

## Installation

1. Clone this repository to your local machine:

    ```
    git clone <repository_url>
    ```

2. Navigate to the project directory:

    ```
    cd <project_directory>
    ```

3. Install the required dependencies using pip:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Ensure that you have a CSV file named `dictionary.csv` containing words and their definitions. The CSV file should have two columns: `word` and `definition`.

2. Run the Flask application:

    ```
    python app.py
    ```

3. Once the application is running, you can access the API endpoints:

    - `GET /` : Displays the home page.
    - `GET /api/v1/<word>/` : Retrieves the definition of the specified `<word>`.

