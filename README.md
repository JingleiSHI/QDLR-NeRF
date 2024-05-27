# QDLR-NeRF



This is the repository for paper "__Light Field Compression via Compact Neural Scene Representation__"  (__ICASSP 2022__).

By [Jinglei Shi](https://jingleishi.github.io/) and  [Christine Guillemot](https://people.rennes.inria.fr/Christine.Guillemot/)

<[Paper link](https://ieeexplore.ieee.org/document/10095668/)>

## Dependencies
```
python==3.x
pytorch==1.xx
torchvision==xxx
```
## Examples
### Preparation of the dataset

### Training
Before launching the training, we should adapt the configuration (Lines 12 - 30) of the file 'train.py' as follows:

After configuring all settings, users can simply launch the training by:
```
python train.py
```

### Evaluation
To synthesize dense light fields with given corner views, users should adapt the configuration (Lines 12-19) of the file 'test.py' as follows:

After configuring the above settings, users can launch the test by:
```
python test.py
```

### Pretrained Models


## Citation
Please consider citing our work if you find it useful.
```
@inproceedings{shi2023light,
    title={Light Field Compression via Compact Neural Scene Representation},
    author={Jinglei Shi and Christine Guillemot},
    booktitle={IEEE International Conference on Acoustics, Speech and Signal Processing},
    pages={1--5},
    year={2023},
    organization={IEEE}}
```
