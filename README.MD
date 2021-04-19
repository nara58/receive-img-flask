1. Pada server, upload file server.py kemudian pada file wsgi.py ubah baris:
from flask_app import app as application
menjadi:
from server import app as application

2. Pada client, upload file client.py dan gambar.jpg. kemudian pada file wsgi.py ubah baris:
from flask_app import app as application
menjadi:
from client import app as application