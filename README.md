# AOIQuickDemo
AIDEA-Defect Classifications of AOI Project
https://aidea-web.tw/topic/314c18ac-d3a4-462a-80dd-61eba86b42e6


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

## Create a virtual environment AOI-Py3 with conda
```
conda create --name AOI-Py3
conda activate AOI-Py3
conda deactivate
```

# Run with the virtual environment AOI-Py3
```bash
> jupyter notebook
```
