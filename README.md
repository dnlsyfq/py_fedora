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
