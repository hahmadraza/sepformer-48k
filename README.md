## Sepformer
### Installation
```
git clone https://github.com/hahmadraza/sepformer-48k.git
cd sepformer-48k
pip install -r requirements.txt
pip install --editable .
```
### Training Sepformer
```
cd sepformer-48k/recipes/LibriMix/separation/
python train.py hparams/sepformer-liiri3mix.yaml --data_folder /path/to/datafolder/
```
