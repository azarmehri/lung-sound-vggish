## VGGish-BiGRU implementation
TensorFlow implementation of VGGish-BiGRU for IEEE Access paper "[Lung Sound Recognition Algorithm Based on VGGish-BiGRU](https://ieeexplore.ieee.org/document/8850324)", Lukui Shi, Kang Du, Chaozong Zhang, Hongqi Ma and Wenjie Yan.

### The lung sound recognition model based on VGGish-BiGRU
![The lung sound recognition model based on VGGish-BiGRU](/images/yan1-2943492-large.gif)

### Respiratory Sound Database
The respiratory sounds from "[ICBHI 2017 Challenge](https://bhichallenge.med.auth.gr/)" database.

### VGGish network
The parameters of [VGGish network](https://github.com/tensorflow/models/tree/master/research/audioset/vggish) provided by Google are directly transferred to the model and frozen.

## Running Code
Please download "[vggish_model.h5](https://drive.google.com/uc?id=1QbMNrhu4RBUO6hIcpLqgeuVye51XyMKM)" from [vggish-keras](https://pypi.org/project/vggish-keras/).