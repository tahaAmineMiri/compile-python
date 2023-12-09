# compile-python
this is a repo for installing python from scratch

`https://www.python.org/ftp/python/3.10.5/Python-3.10.5.tgz`

`rm  Python-3.10.5.tar`

`cd Python-3.10.5/`

`./configure --enable-optimizations`

`make -j 2`

`sudo make altinstall`

`check python version <python>`

`cd ..` <name of project>

`/usr/local/bin/python3.10`

`vim /home/codespace/.bashrc`

`add this line of code at the end of the file : alias python="/usr/local/bin/python3.10 AND source ~/.venv/bin/activate"`

`source /home/codespace/.bashrc`

`python -m venv /home/codespace/.venv`

`touch requirements.txt`
`touch Makefile`




















































