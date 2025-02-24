### Create conda envrionment
```linux
conda create -n scprinter python=3.11
conda activate scprinter
```

### Install conda-compatible packagses
```linux
conda install -c conda-forge mamba --yes
mamba install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install bioframe pybedtools pysam==0.21
```
