#Follow these steps to install package 
cd ~
git clone https://github.com/GoMaxOne/json-logic-py
cd ~/json-logic-py 
python3 setup.py bdist_wheel
sudo python3 -m pip install json_logic-0.7.0a0-py2.py3-none-any.whl
