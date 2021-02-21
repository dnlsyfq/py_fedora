```
sudo dnf install python
ls /bin/python
chmod +x _.py
./testFile.py
```

```
#!/bin/python

print("2 + 2 =",4)
```

```
#!/bin/bash

```

### PIP , Virtual Environment Setup

```
sudo dnf install python3-virtualenv -y
sudo dnf install python3-pip

python -m venv new_virt
cd ..

source new_virt/bin/activate
deactivate

pip list
pip search selinux

pip install <name> --user
pip uninstall <name>

pip install --upgrade pip

pip freeze > requirements.txt

pip install -r requirements.txt
```


### Tuple 
```
constant value 
tuplevar = (1,2,3) # doesnt allow reassign value
```

### Binary , bitwise
```
a = 0b11110000
b = 0b11001100
bin(a)
a 
bin(a&b)
bin(a|b)
bin(a^b)
bin(b >> 3)


n1 = 3
n2 = 3

n1 is n2 
n1 == n2 
n1 in [15,30,23]
n1 not in [15,23,14]
```


### loops and conditional statements
```
mkdir myProject
python -m venv myProject/myVenv
vim myProject/loops.py
source myProject/myVenv/bin/activate 
cd myProject
python loops.py


chmod +x _.py
```

