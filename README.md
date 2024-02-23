# Dashboard

Cloning the Repository

    git clone https://github.com/evadelzz1/pandas-dashboard.git

Setting up a Virtual Environment

    cd ./pandas-dashboard

    pyenv versions

    pyenv local 3.11.6

    echo '.env '  >> .gitignore
    echo '.venv' >> .gitignore

    python -m venv .venv

    source .venv/bin/activate

Install the required dependencies

    pip list
    
    pip install -r requirements.txt
    
    pip freeze | tee requirements.txt.detail

Running the Application

    python -m streamlit run Home.py

Deactivate the virtual environment

    deactivate


## Reference

[Python Interactive Dashboard Development using Streamlit and Plotly](https://www.youtube.com/watch?v=7yAw1nPareM)

[git](https://github.com/AbhisheakSaraswat/PythonStreamlit)
