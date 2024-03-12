#Pip/Python must be run from a venv

See notes here: https://chat.openai.com/c/b9afd56f-48e0-432b-b34c-fdb7acf380a4

Here's how I did it with Modal's Get Started project:
melissarosenthal@melissas-mbp modal-app % cd ..
melissarosenthal@melissas-mbp ~ % source python3venv/bin/activate
(python3venv) melissarosenthal@melissas-mbp ~ % python3venv/bin/pip install modal
(python3venv) melissarosenthal@melissas-mbp ~ % python3 -m modal setup
(python3venv) melissarosenthal@melissas-mbp ~ % modal run get_started.py
(python3venv) melissarosenthal@melissas-mbp ~ % cd Desktop
(python3venv) melissarosenthal@melissas-mbp Desktop % cd Code
(python3venv) melissarosenthal@melissas-mbp Code % cd modal-app
(python3venv) melissarosenthal@melissas-mbp modal-app % modal run get_started.py