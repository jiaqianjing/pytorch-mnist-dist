# pytorch-mnist-dist

## 使用方式
```python
#gloo
python mnist.py --backend gloo
#nccl
python mnist.py --backend nccl
#mpi（pytorch 在编译的时候需要指定 mpi）
python mnist.py --backend mpi
```

## 说明
数据集在有网络的情况下会自动下载到 --data (default:/data)



