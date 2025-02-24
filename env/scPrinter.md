### scPrinter github
https://github.com/buenrostrolab/scPrinter/tree/main

---
### Create conda envrionment
```linux
conda create -n scprinter python=3.11
conda activate scprinter
```

---
### Install conda-compatible packagses
```linux
conda install -c conda-forge mamba --yes
mamba install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install bioframe pybedtools pysam==0.21
mamba install -c bioconda MACS3 cykhash hmmlearn=0.3.0 python-igraph==0.11.6 pandas==2.1.1 polars==0.20.31 pyfaidx==0.7.2.2
pip install MOODS-python snapatac2 ema_pytorch modisco-lite
```
