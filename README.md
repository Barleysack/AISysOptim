Code from https://github.com/thuml/Autoformer.

**TODO**

0. Download and unzip the dataset into dataset folder.
1. Change the bash script allocating GPU/CPU if necessary. (CUDA_VISIBLE_DEVICES, prefix)

Bash command for comparison
```
bash comp_scripts/ECL_script/ECL_comp.sh # GPU=1, cpu=8~15
bash comp_scripts/ETT_script/ETT_comp.sh # GPU=2, cpu=16~23
bash comp_scripts/Exchange_script/Exchange_comp.sh # GPU=3, cpu=24~31
bash comp_scripts/ILI_script/ILI_comp.sh # GPU=4, cpu=32~39
bash comp_scripts/Traffic_script/Traffic_comp.sh # GPU=5, cpu=40~47
bash comp_scripts/Weather_script/Weather_comp.sh # GPU=6, cpu=48~53
```
