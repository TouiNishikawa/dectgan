# dectgan

# Installation
Please install our liblary by this code. 
 
```bash
pip install  git+https://github.com/TouiNishikawa/dectgan.git
```
 
# Usage
 

```bash
import dectgan
dectgan.train('./baron_train_1_2.csv', 50, 251, 50, "ductal", 1000)
```

```bash
dectgan.train2train_aug('./baron_train_1_2.csv','./baron_pDataC_1_2.csv', 1000, 250)
```
