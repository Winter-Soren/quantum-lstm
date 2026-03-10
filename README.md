# Quantum LSTM 

Get the code:
```
git clone https://github.com/Winter-Soren/quantum-lstm.git
cd quantum-lstm
```

Create a Python 3.x virtual environment and install libraries:
```
python3 -m venv venv
source venv/bin/activate
pip3 install --upgrade pip
pip3 install -r requirements.txt
```

Test if it works with the classical LSTM from PyTorch:
```
$ ./example_pos.py -E 8 -H 4 -Q 0 -e 300
```
