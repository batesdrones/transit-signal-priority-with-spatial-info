<!-- # lyft-motion-prediction-for-autonomous-vehicle -->

### Description


### Table of Contents

- [Environment Setup](#environment-setup)
- [Model](./model)
- [Training](#training)

### Environment Setup
- Python 3.* is installed
- Set permission
```
chmod 700 bin/bootstrap
```
- Run the bootstrap for installing the requirements
```
bin/bootstrap
```

### Training
- After installing all the requirements, run the following command for trainig
```
python train.py -d -gpu -model MODEL_NAME
```
- `-d`: debug mode, default is `False`
- `-gpu`: train on GPU, default is on `CPU`
- `model`: REQURIED, all the available models are in the folder `model/`, simply input the name of the model file.<br /> (eg. `-model baseline` for model `baseline.py`)

