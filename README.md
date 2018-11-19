Virtual Env Setup:
-> Install virtualenv (if it is not already installed): python -m pip install --user virtualenv
-> Create a viritual environment for this class: virtualenv ml4t-venv
-> Activate the new virtual environment: source ml4t-venv/bin/activate on Linux or macOS, ml4t-venv/Scripts/activate.bat on Windows.
-> Save the above list as a text file, say ml4t-libraries.txt
-> Install the libraries using the requirements file you just saved: python -m pip install --requirement ml4t-libraries.txt


Paackges to be included:

 cycler==0.10.0
 functools32==3.2.3.post2
 matplotlib==2.0.2
 numpy==1.13.1
 pandas==0.20.3
 py==1.4.34
 pyparsing==2.2.0
 pytest==3.2.1
 python-dateutil==2.6.1
 pytz==2017.2
 scipy==0.19.1
 six==1.10.0
 subprocess32==3.2.7
