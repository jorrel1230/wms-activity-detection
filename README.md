# wms-activity-detection

## Pipeline

![wms-activity-detection drawio](https://github.com/user-attachments/assets/fd30604f-88bf-471b-8cf3-f6af49a64480)

This project was done using compute resources from the *Adroit* cluster.

## Activating the Conda Environment and starting Jupyter Server in Adroit

```bash
salloc --nodes=1 --ntasks=1 --time=60:00 --gres=gpu:1 --partition=mig
module load anaconda3/2024.10 && conda activate wms-activity-detection
jupyter-lab --no-browser --port=8889 --ip=0.0.0.0 
```
