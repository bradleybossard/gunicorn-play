# gunicorn-play
Just trying out the GUnicorn example

## Setup
TODO(bradleybossard) : Actually test out these commands from scratch.

    git clone <this-repo>
    cd <this-repo>
    source bin/active                        # Active the virtualenv environment
    pip install -r requirements              # Install gunicorn 
    cd app
    gunicorn -b 127.0.0.1:9030 -w 4 app:app  # Starts server on port 9030.
                                             #  Assumes code is in file app.py, calls function app




