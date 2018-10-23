# deeplearning.ai notes

![Python 3.7.1](https://img.shields.io/badge/Python-3.7.1-green.svg?longCache=true&style=flat)


Note: If running Python 3.7, be sure to run the tensorflow fix to rewrite a file that uses `async` as a parameter name. In Python 3.7+, this is a reserved keyword. *Update*: I decided to switch to PyTorch for the purposes of anything related to this course, until TF is actually required.


Otherwise, simply create a virtualenv
```sh
$ python3 -m venv env/
$ source env/bin/activate
```

and install all the reqs (which may change as I proceed):
```sh
(env)$ pip3 install -r requirements.txt
```

then launch the notebook
```sh
(env)$ jupyter notebook
```

These notes are MIT Licensed, so pursuant to that license do whatever you want with any code or algorithms I publish here.

With that said, I will not publish programming assignments (doing the work is the fun bit).

© 2018 Damien Stanton

See LICENSE for details.

[![Buy Me A Coffee](https://www.buymeacoffee.com/assets/img/custom_images/white_img.png)](https://www.buymeacoffee.com/damienstanton)
