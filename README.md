
# Interactive Dashboard with Python – Streamlit
Sales Dashboard built in Python and the Streamlit library to visualize Excel data.

## Demo
Sales Dashboard: https://dashboard-cis.herokuapp.com/

## Screenshot
![Dashboar Screenshot](https://content.screencast.com/users/jubbel3/folders/Snagit/media/64b4d64a-4e59-4bec-9f16-771eb1a99005/08.18.2021-19.50.jpg)


## Author
- Sven from Coding Is Fun
- YouTube: https://youtube.com/c/CodingIsFun
- Website: https://pythonandvba.com

## Feedback
If you have any feedback, please reach out to me at contact@pythonandvba.com

![Logo](https://content.screencast.com/users/jubbel3/folders/Snagit/media/c42ea34b-4057-4754-96b0-e8e05c866afb/08.18.2021-19.56.png)

## Addendum
* Added `asdf` local Python version 3.9.6
    * On Fedora, needs dependencies installed before compiling:
        ```bash
        sudo dnf install -y bzip2-devel libsqlite3x-devel
        ```
    * Install Python
        ```bash
        asdf install python 3.9.6
        ```
* `poetry` setup
    ```bash
    # update pip
    poetry run python -m pip install --upgrade pip
    
    # install libraries
    poetry install
    
    # activate .venv
    poetry config virtualenvs.in-project true           # .venv in `pwd`
    poetry shell
    ```
* Run the `streamlit` server
    ```bash
    streamlit run app.py
    ```
    * Navigate to the IP address/localhost and port in a browser (e.g., http://localhost:8501)
