create the environment folling these instructions:
https://internvl.readthedocs.io/en/latest/get_started/installation.html
 
follow the instructions here for downloading model: https://internvl.readthedocs.io/en/latest/internvl2.5/finetune.html
I think using the 1B model is fine for now. 
 
then follow the next step for setting up custom dataset
Our json input is this:

{  "multivent3-classification": {    "root": "/exp/scale24/features/metadata/multimodal/train_thumbnails/",    "annotation": "/exp/scale24/features/metadata/multimodal/train_chat_templates.jsonl",    "data_augment": false,    "max_dynamic_patch": 12,    "repeat_time": 1,    "length": "13330"  }}