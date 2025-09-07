# MMLab projects based on CUDA 12.6 and Pytorch 2.7.1.

This project contains mmengine, mmcv, mmdet, mmseg, mmpretrain. All these five sub-projects has been built based on CUDA 12.6 and Pytorch 2.7.1.

|mmengine|mmcv|mmdet|mmseg|mmpretrain|
|---|---|---|---|---|
|v0.8.5|v2.2.0|v3.3.0|v1.2.2|v1.2.0|

# Install
```
pip install torch==2.7.1 torchvision==0.22.1 torchaudio==2.7.1 --index-url https://download.pytorch.org/whl/cu126
git clone https://github.com/ezKernel/mmlab_cuda12.6_pytorch2.7.1.git
cd subfolder
python setup.py bdist_wheel
```



----
🎉🎉🎉🎉 Acknowledgement: Thanks to Morgan LT (https://github.com/KaceCM).
