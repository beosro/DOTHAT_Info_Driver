This version is for python2.x.

You can install it the same way as the python3.3+ version, just with a different virtualenv command:

(First confirm that "python -V" lists the standard Python 2.7.6, and that "which python" lists /usr/bin/python)

virtualenv -p /usr/bin/python ./.env

source .env/bin/activate

pip install -r requirements.txt

./dot3k_text_run.py
