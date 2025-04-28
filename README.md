# sllaunch

`sllaunch` is a Bash script designed to simplify the process of launching Streamlit applications. It automatically detects and runs your Streamlit app, provided it is named `app.py` or `streamlit_app.py`. Alternatively, you can specify the script name as a command-line argument.

## Features

- Automatically detects and runs `app.py` or `streamlit_app.py`.
- Allows specifying a custom Streamlit script as an argument.
- Sets up a Python virtual environment (`venv`).
- Installs dependencies from `requirements.txt`.
- Launches the Streamlit app using the `streamlit run` command.

## Usage

### Default Behavior

If your Streamlit app is named `app.py` or `streamlit_app.py`, simply run:

```bash
./sllaunch
