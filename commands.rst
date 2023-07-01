applications
------------

::

 sudo apt-get install vim
                      git

Render rst files to html::

 restview git.rst -l 10.0.1.7:8787 -B --allowed-hosts 10.0.1.7                      
Launch all your tube::

 cd ~/github/all-your-tube
 python -m pipenv shell
 ./launch.sh
 http://<IP>:1424/yourtube/
