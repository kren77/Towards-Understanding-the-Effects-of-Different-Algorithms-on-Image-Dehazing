# MSBDN-DFF


## Test

```bash
MSBDN-DFF/$python test.py --checkpoint path_to_pretrained_model
```

## Train


1. Run the ``MSBDN-DFF/train.py`` with cuda on command line: 
```bash
MSBDN-DFF/$python train.py --dataset path_to_dataset/RESIDE_HDF5_all/ --lr 1e-4 --batchSize 16 --model MSBDN-DFF-v1-1 --name MSBDN-DFF
```
