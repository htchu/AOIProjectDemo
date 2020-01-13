# AOIQuickDemo
AIDEA-Defect Classifications of AOI https://aidea-web.tw/topic/a49e3f76-69c9-4a4a-bcfc-c882840b3f27


## Installing Python 3.x, Pip3, VirtualEnv on Ubuntu
```bash
> sudo apt update
> sudo apt-get install python3
> python3 -V
> sudo apt-get install python3-pip
> sudo apt install virtualenv
```

## Create a virtual environment AOI-Py3
```bash
> virtualenv -p python3 AOI-Py3
> python3 -m ipykernel install --user --name=AOI-Py3
> source AOI-Py3/bin/activate
> pip3 install -r requirements.txt
```

# Run with the virtual environment AOI-Py3
```bash
> jupyter notebook
```
