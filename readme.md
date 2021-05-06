Date_Detection.ipynb was used to train models for with transforms to generate the results. The directories cannot be uploaded to github due to their large size.

Use the following commands in bash to download the vision repository used in the project.

`git clone https://github.com/pytorch/vision.git

cd vision

git checkout v0.3.0

cp references/detection/utils.py ../

cp references/detection/transforms.py ../

cp references/detection/coco_eval.py ../

cp references/detection/engine.py ../

cp references/detection/coco_utils.py ../`
