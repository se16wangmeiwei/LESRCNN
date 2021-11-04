# LESRCNN

## Lightweight Image Super-Resolution with Enhanced CNN（LESRCNN）is conducted by Chunwei Tian, Ruibin Zhuge, Zhihao Wu, Yong Xu, Wangmeng Zuo, Chen Chen and Chia-Wen Lin, and accepted by Knowledge-Based Systems (IF:8.038) in 2020. It is implemented by Pytorch. And it is reported by Cver and 52CV. Its website is https://mp.weixin.qq.com/s/njlAEQXxjXKqFcxM7KYiqA. 





## Requirements (Pytorch)  
#### Pytorch 0.41
#### Python 2.7
#### torchvision 
#### openCv for Python
#### HDF5 for Python
#### Numpy, Scipy
#### Pillow, Scikit-image
#### importlib

#### tqdm

## Commands
### Test 

注意：该模型暂时只支持4**倍放大因子的超分**。后续可继续更新。

`cd x4`

### Single SR model for x4
#### `python tcw_sample.py --test_data_dir dataset/test --save_dir results`

####  解释：test_data_dir  表示需超分的图片所存放的图片

#### 			save_dir  表示最终的图片所保存的地址。（这里为了展示我们图片的效果，我们保存的是输入与输出的对比图）

