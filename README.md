# deeplearning.ai notes

Note: If running Python 3.7, be sure to run the tensorflow fix to rewrite a file that uses `async` as a parameter name. In Python 3.7+, this is a reserved keyword.

Otherwise, simply create a virtualenv
```sh
python3 -m venv env/
source env/bin/activate
```

and install all the reqs (which may change as I proceed):
```sh
pip3 install -r requirements.txt
```

then launch the notebook
```sh
(env) jupyter notebook
```
