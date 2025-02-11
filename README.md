# ICCV2025
ICCV2025用の曼陀羅

前処理に使うモデル<br>
HistoSegNet <br>
Foundation model <br>

# SAMUS setup 手順
https://github.com/xianlin7/SAMUS

# SAM setup 手順
HW: Tensor

```
conda create -n sam python=3.9
conda activate sam
pip install opencv-python pycocotools matplotlib onnxruntime onnx torch torchvision torchaudio
```

[公式Git](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file)からダウンロードし，コードをサーバにUpload

```
pip install -e .
```

[モデルのリンク](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#model-checkpoints)からwgetでインストール

```
pip install  git+https://github.com/facebookresearch/segment-anything.git 
```
