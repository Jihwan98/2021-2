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
```
[name: "/device:CPU:0"
device_type: "CPU"
memory_limit: 268435456
locality {
}
incarnation: 18048418793289264508
, name: "/device:GPU:0"
device_type: "GPU"
memory_limit: 5732106240
locality {
  bus_id: 1
  links {
  }
}
incarnation: 13686685529342944195
physical_device_desc: "device: 0, name: NVIDIA GeForce RTX 3070, pci bus id: 0000:2b:00.0, compute capability: 8.6"
]
```
