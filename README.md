Как запустить:

python3 -m venv venv

source ./venv/bin/activate

pip3 install -r requirements.txt

source .env

python3 ./train.py

Как запустить при наличии mlflow:

source .env

mlflow run . --env-manager=local --experiment-name=kinopoisk
