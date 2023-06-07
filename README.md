# Native Python executables

## Instructions

### Build

```
python3 -m venv env

. env/bin/activate

pip install -r requirments.txt

python setup.py build
```

### Test

```
deactivate

cd build/exe.linux-x86_64-3.11

./main
```
