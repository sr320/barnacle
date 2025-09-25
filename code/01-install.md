# Install

raven

```
# 1) Create & enter a 3.11 env
conda create -n barnacle311 python=3.11 -y
conda activate barnacle311

# sanity check you're in the right env
python --version
which python
which pip

# 2) Upgrade build tools
python -m pip install --upgrade pip setuptools wheel

# 3) Install from your repo (editable install so you can iterate)
cd /home/shared/16TB_HDD_01/sr320/github/barnacle
python -m pip install -e .

# 4) Verify
python -c "import barnacle, sys; print('barnacle OK on', sys.version)"
```


then


```
poetry install
```


in terminal 

```
Installing the current project: barnacle (0.1.0)
(barnacle311) sr320@raven:/home/shared/16TB_HDD_01/sr320/github/barnacle$ 
```