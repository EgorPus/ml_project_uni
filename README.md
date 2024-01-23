Этап 1-2

python3 -m venv venv

source ./venv/bin/activate

pip3 install -r requirements.txt

source .env

python3 ./train.py

Этап 3

MlFlow

source .env

mlflow run . --env-manager=local --experiment-name=kinopoisk

