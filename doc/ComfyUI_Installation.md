# ComfyUI Installation

# download comfyui
```bash
git clone https://github.com/comfyanonymous/ComfyUI.git

```
# create conda environment
```bash
conda create -n comfyui
conda activate comfyui
conda install python

```
# install requirements
```bash
cd ComfyUI
pip install -r requirements.txt
# or if you have a slow internet connection, you can use the following command to install requirements from a mirror site
pip install -r requirements.txt -i http://mirrors.aliyun.com/pypi/simple/ --trusted-host mirrors.aliyun.com

```
# run
```bash
python main.py
```
###### Notes:
_现在是按装好了，但是不能用，因为模型文件还没有下载。_