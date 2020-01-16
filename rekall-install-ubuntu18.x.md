## From Terminal
```
virtualenv [target_env_path]
source [target_env_path]/bin/activate
pip install --upgrade setuptools pip wheel
pip install rekall-agent rekall
```
---
Likely fixes due to latest Python3 version of libraries
```
pip install future==0.16.0
pip install pyaff4==0.26.post6
```
