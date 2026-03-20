# RTL-Sequencer
An initial prototype has been developed in [model.ipynb](./model.ipynb); the complete code implementation will be provided in a subsequent release.

## Python Environment
```
conda create python=3.9 --name rtl-sequencer
conda activate rtl-sequencer
conda install nvidia::cuda==11.8.0 # optional and based on your device
conda install pytorch==2.1.1 torchvision==0.16.1 torchaudio==2.1.1 pytorch-cuda=11.8 -c pytorch -c nvidia
pip install causal-conv1d==1.5.0.post8 mamba-ssm==2.2.2 # many issues can refer to the original repo
pip install -r requirements.txt
```
