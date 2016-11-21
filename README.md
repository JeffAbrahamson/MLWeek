# MLWeek
MLWeek presentations etc.

## For codelabs, set up a virtual environment using python2

    $ virtualenv venv
    $ . venv/bin/activate
    $ for cat requirements.txt | while read line; do pip install $line; done
    $ jupyter notebook
    # (should open a browser window)

Install TensorFlow for your OS according to the instructions here:
  https://www.tensorflow.org/versions/r0.11/get_started/os_setup.html
