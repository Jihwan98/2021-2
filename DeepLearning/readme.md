# 2021-2 DeepLearning

## tensorflow gpu 잡았는지 check
```python
import tensorflow as tf
tf.__version__
```
```python
from tensorflow.python.client import device_lib
print(device_lib.list_local_devices())
```
