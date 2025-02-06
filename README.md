# Anomaly-OV
1. Download the files
```
scp -r idwivedi@amhrisva100a:/data/01/kdi/jiacong/Anomaly_OV_7b_cp ./
```
2. Follow the LLaVA-NEXT GitHub page to install the environment (change the env name to anomaly_ov)
3. Run the following code
```
conda activate anomaly_ov
CUDA_VISIBLE_DEVICES=1 python test_7b_chat_image.py
```
