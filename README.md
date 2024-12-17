# ML learning

A few notebooks I used to learn various ML data analysis techniques.


To [install tensorflow](https://www.tensorflow.org/install/pip#windows-wsl2):

```
mamba create --name ml-tensorflow-wsl python=3.12 numpy pandas matplotlib seaborn scikit-learn xgboost jupyter 
mamba activate ml-tensorflow-wsl
pip install tensorflow[and-cuda]
```