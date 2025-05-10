# 🔧 Steps:

## Edit your requirements.txt
Replace:

``` sentence-transformers==2.6.1 ```

With:

```sentence-transformers>=3.0.0 ```


## Update your environment


```pip install --upgrade sentence-transformers```


## (Optional but recommended) If you’re using a virtual environment:

```pip install --upgrade pip setuptools```
```pip install -r requirements.txt ```

## Run Jupiter 

```jupyter lab --ip=0.0.0.0 --allow-root --ServerApp.allow_remote_access=True```