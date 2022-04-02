

e' un progetto flask

necessario python

necessario usare un virtual env
e creare un database test

comandi
da eseguire nella cartella 

in un terminale:

virtualenv env
source env/bin/activate
pip install -r requirements.txt
python app.py

se da problemi il DB, ma non credo, in un altro terminale:

python
(oppure python3)
from app import db
db.create_all()

