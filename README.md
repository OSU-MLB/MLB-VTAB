## Announcement

The code is modified from [NOAH](https://github.com/ZhangYuanhan-AI/NOAH/#data-preparation). We added necessary files and random seed to make the split generation reproducible. 

## Preparation

1. Get `conda` installed and run `env_setup.sh`
2. Download the required files and folders from this [link](https://buckeyemailosu-my.sharepoint.com/:f:/g/personal/zhang_14217_buckeyemail_osu_edu/ElOvcg8E_H1LlagiH1RyOdQBvnzh59cmS2V9izAdmoHX3g?e=ejRpsi). The link contains: 
    - `data`: Move the this folder to the root directory of this repository. It contains necessary files to execute `get_vtab1k.py`
    - `vtab-1k.tar.gz`: VTAB-1k dataset processed by this repo, using seed `9526`

## Execute

To execute the script, run the following command:

```bash
python get_vtab1k.py --seed 9526
```

## Publication

If you find this repo useful, please consider citing our work: 

```
@misc{2409.16434,
    Author = {Zheda Mai and Ping Zhang and Cheng-Hao Tu and Hong-You Chen and Li Zhang and Wei-Lun Chao},
    Title = {Lessons Learned from a Unifying Empirical Study of Parameter-Efficient Transfer Learning (PETL) in Visual Recognition},
    Year = {2024},
    Eprint = {arXiv:2409.16434}
}
```
