# YOSO_TensorRT

## Repo still under development
TODO
- Integrate export.py within detectron2

## Getting started
- Clone this repo
- Follow the official repo for setup 
- To export the model
```bash
python demo/export.py --config-file projects/YOSO/configs/coco/panoptic-segmentation/YOSO-R50.yaml --video-input input_video.mp4 --output output_video.mp4 --opts MODEL.WEIGHTS ./model_zoo/yoso_res50_coco.pth
```

