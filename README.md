# 目標 : 成功以此進行訓練
https://github.com/lukemelas/EfficientNet-PyTorch

# 依據作者安裝方式會失敗, https://github.com/lukemelas/EfficientNet-PyTorch
pip install efficientnet_pytorch

# 改這也失敗
conda install pytorch==1.4.0 torchvision==0.5.0 cudatoolkit=10.0 -c pytorch

# 這會成功
conda install pytorch==1.2.0 torchvision==0.4.0 cudatoolkit=10.0 -c pytorch

# 但是，執行efficientnet_sample.py，會出現
from efficientnet.model import EfficientNet
ModuleNotFoundError: No module named 'efficientnet'

