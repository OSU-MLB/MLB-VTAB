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
