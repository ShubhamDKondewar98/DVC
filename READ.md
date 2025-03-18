```
Command promt
mkdir dvc

cd dvc 

code .
```


```
conda create --prefix  env(environment name) python=3.8 -y 
source activate ./env 
```

```
git init
```

```
touch .gitignore
```

```
touch README.md
```
```
dvc init
```



```
ctrl+enter -- work as git add. & git commit 
```
```
pip install -r requirements.txt 

touch test.py
```

```
python stage_01.py
python stage_02.py
dvc init
dvc repro
dvc dag
``` 

