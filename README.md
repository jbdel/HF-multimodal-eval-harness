```
conda create -n HF-harness python=3.9
conda activate HF-harness
pip install -e .

python main.py \
    --model hf \
    --model_args pretrained=JB/HF_RRG_harness \
    --tasks report_generation_mimic_cxr \
    --device cuda:0 \
    --limit 5
```
   