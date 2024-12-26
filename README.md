# F1-scrutiny
# F1 Data Visualization & Analysis Tool (Streamlit Version)

This project is a Streamlit-based web application that provides visualizations and analysis of Formula 1 data. It uses the `fastf1` Python library to fetch F1 data and displays it using Streamlit.

## Project Overview

This application allows users to:

*   Fetch and display Formula 1 race results for a specific year.
*   Visualize the results data in a tabular format.

## Technology Stack

*   **Python:** The primary programming language.
*   **Streamlit:** For creating the web application interface.
*   **FastF1:** For fetching Formula 1 data.
*   **Pandas:** For data manipulation and analysis.

## Prerequisites

Before running the application, make sure you have the following installed:

1.  **Python:** Python 3.7 or higher
2.  **pip:** Python package installer.
3. **Poetry (Recommended):** For package and environment management
4. **Virtual Environment:** It is recommended to use a virtual environment for this project to avoid problems with the installed libraries

## Setup

### Using Poetry (Recommended)

1.  **Install Poetry:** Follow the instructions on the [official Poetry website](https://python-poetry.org/docs/#installation) for your operating system.

2.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd <project_directory>
    ```

3.  **Install project dependencies:**
    ```bash
    poetry install
    ```

4.  **Activate the virtual environment:**
    ```bash
    poetry shell
    ```

### Without Poetry
1. **Clone the Repository:**
    ```bash
    git clone <repository_url>
    cd <project_directory>
    ```
2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```

3.  **Activate the virtual environment:**

    *   **On Windows:**
        ```bash
        venv\Scripts\activate
        ```
    *   **On macOS and Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install project dependencies:**
    ```bash
    pip install streamlit fastf1 pandas
    ```

## Usage

1.  **Navigate to the project directory** in your terminal.

2.  **Run the Streamlit application:**

    ```bash
    streamlit run streamlit_app.py
    ```

   

3.  **Open the application** in your web browser. Streamlit will typically provide a local URL where the application is running (usually `http://localhost:8501`).

4.  **Enter the Year:**
    *   Use the input field to enter a year for which you want to see the results.
    *   Click the "Fetch Results" button.

5.  **View Results:**
    *   The results will be displayed in a tabular format on the screen.

## Code Structure

*   **`streamlit_app.py`:** The main Python file containing the Streamlit application logic.
*   **`fastf1_data.py`:** (Optional) Python file with the logic for fetching data with fastf1.
*   **`cache`:** Directory for caching fastf1 downloads.

## Error Handling

The application includes error handling:
*   For invalid year formats.
*   For years that have no races available.
*   For potential errors when fetching and loading the data with `fastf1`.

## Contributing

Contributions are welcome! If you have ideas for improvements or new features, please feel free to submit a pull request.

## License

This project is licensed under the [Open source] License. (Replace with the actual license you want to use).

## Contact

If you have any questions, please feel free to contact me at [karthikreddy9035@gmail.com].
