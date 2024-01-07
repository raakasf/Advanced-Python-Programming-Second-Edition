# Installation and running history

```bash
virtualenv advanced
cd advanced/bin/
ls
./activate
sudo ./activate
cd ..
source advanced/bin/activate
ls
pip list
pip install -r requirements.txt
source /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/activate
/home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/python /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/Chapter01/simul.py
which pip
source /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/activate
ifconfig
cd ~/Workspace
cd Advanced-Python-Programming-Second-Edition
cd Chapter01
virtualenv advanced
source advanced/bin/activate
pip list
python Chapter01/simul.py
cd -
cd ../Chapter01
time python simul.py
python Chapter01/simul.py
ipython
pip install timeit
pip install ipython 
python -m timeit -s 'from simul import benchmark'
ipython
python -m timeit -s 'from simul import benchmark' \n'benchmark()'
python simul.py
source /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/activate
pwd
cd Chapter01
python simul.py
pip install -r ../requirements.txt
pip list
pytest test_simul.py::evolve_test
pytest test_simul.py::test_evolve
python -m cProfile simul.py
clear
python -m cProfile -s totime simul.py
python -m cProfile -s tottime simul.py
source /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/activate
python -m cProfile -o prof.out simul.py
codes ipython
ipython
python -m cProfile -o prof.out exercise.py
python -m cProfile -s tottime exercise.py
sudo apt install kcachegrind
pip install pyprof2calltree
python -m cProfile -o prof.out taylor.py
pyprof2calltree -i prof.out -o prof.calltree
kcachegrind prof.calltree # or qcachegrind prof.calltree
cd Chapter01
kcachegrind prof.calltree # or qcachegrind prof.calltree
pip install line_profiler
source /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/activate
cd Chapter01
kernprof.py -l -v simul.py
find ../ -name "kernprof.py" -print
../advanced/lib/python3.11/site-packages/kernprof.py -l -v simul.py
sudo ../advanced/lib/python3.11/site-packages/kernprof.py -l -v simul.py
ipython
kernprof.py -l -v simul.py
pip3 install --user line_profiler
~/.local/bin/kernprof
sudo ln -s ~/.local/bin/kernprof /usr/local/bin/kernprof\n
source /home/vboxuser/Workspace/Advanced-Python-Programming-Second-Edition/advanced/bin/activate
kernprof.py -l -v simul.py
kernprof -l -v simul.py
cd Chapter01
kernprof -l -v simul.py
clear
kernprof -l -v simul.py
kcachegrind prof.calltree # or qcachegrind prof.calltree
```
