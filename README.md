# mlflow experiments

Set up your python environment

    Go the training script/notebook folder

    Create python virtual environment

    > python -m venv env_mlflow

    Activate your virtual environment

    > env_mlflow\Scripts\activate -- Windows

    > source env_mlflow/bin/activate -- Ubuntu

    Install all the packages in your virtual environment

    > pip install -r requirements.txt

    Create kernel

    > python -m ipykernel install --user --name mlflow --display-name mlflow-kernel

    Launch Jupyter notebook

    jupyter lab

    Connect jupyter to kernel mlflow-kernel

    Execute mlflow ui

    > mlflow ui