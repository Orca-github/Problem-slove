# Problem-slove
Deal Ubuntu python2.7 download matplotlib problem

1.ERROR: Failed building wheel for subprocess32
  solve: download subprocess32-3.2.7.tar.gz     
  python2.7 -m pip download subprocess32
  tar -xzvf subprocess32-3.2.7.tar.gz
  python setup.py install
    if 2. _posixsubprocess.c  do not have .......
      solve: sudo apt-get install python-dev
      
 ImportError:No module named_tkinter,please install the python-tk package
 solve: sudo apt-get install python-tk
 


