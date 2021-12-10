# Getting started

### Requirements

If you want to train the models locally install all the necessary packages with pip.

```pip3 install -r requirements.txt```

### Weights & Images

You can find the associated Images in the first release v0.1. Download the .zip and put your repisitory in the following folder structure:
```
├── TrashTron2.ipynb
├──  datasets                    
|    ├── train/                         # training images
|    ├── val/                           # validation iamges
|    ├── train.json                     # training annotations
|    └── val.json                       # validation annotations
└── output
     ├── coco_instances_results.json
     ├── events.out.tfevents
     ├── instances_predictions.pth
     ├── last_checkpoint
     ├── metrics.json
     └── model_final.pth                # final model after training
```

# Google Collab

You can use the whole project in the associated [TrashTron2 Notebook](https://colab.research.google.com/drive/1IrutxbF5P1LnbXOjIhMCBu6hJdr5qrjz?usp=sharing). You can apply the folder structure from above.
