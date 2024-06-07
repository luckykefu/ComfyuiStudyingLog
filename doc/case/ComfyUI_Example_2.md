# ComfyUI Example 2
# 琉璃效果复现
_建议直接看下方 安装失败_
## 详情：
[IMAGE TO 💎JADE STYLE | ComfyUI Workflow](https://openart.ai/workflows/xiongmu/image-to-jade-style/BRuUXjQhMaLu0dPOvZHD)
## 准备
### checkpoint 模型：
[Juggernaut XL - Jugg\_X\_RunDiffusion\_Hyper | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/133005/juggernaut-xl)

### lora模型：

- glazed girl

https://civitai.com/models/140681/xlglazed-girl-jade-glass-ceramic-and-other-textures

- sdxl_glass

https://civitai.com/models/11203/glass-sculptures

- jade

https://civitai.com/models/148809/sdxl-or-jadeite-cabbage-or-chinese-treasure
### 放大模型
[4x-Ultrasharp - 4x-UltraSharp v1.0 | Stable Diffusion Upscaler | Civitai](https://civitai.com/models/116225/4x-ultrasharp)
## 开始
###  打开工作流
#### - 安装缺失的节点
[GitHub - Fannovel16/comfyui\_controlnet\_aux: ComfyUI's ControlNet Auxiliary Preprocessors](https://github.com/Fannovel16/comfyui_controlnet_aux/)
```sh
cd  custom_nodes 
git clone https://github.com/Fannovel16/comfyui_controlnet_aux/
cd comfyui_controlnet_aux
pip install -r requirements.txt
```
[GitHub - WASasquatch/was-node-suite-comfyui: An extensive node suite for ComfyUI with over 190 new nodes](https://github.com/WASasquatch/was-node-suite-comfyui/)
```
cd  custom_nodes 
git clone https://github.com/WASasquatch/was-node-suite-comfyui/
cd was-node-suite-comfyui
pip install -r requirements.txt
```
[GitHub - EllangoK/ComfyUI-post-processing-nodes: A collection of Post Processing Nodes for ComfyUI, which enable a variety of cool image effects](https://github.com/EllangoK/ComfyUI-post-processing-nodes/)
```
git clone https://github.com/EllangoK/ComfyUI-post-processing-nodes/
```
[GitHub - Suzie1/ComfyUI\_Comfyroll\_CustomNodes: Custom nodes for SDXL and SD1.5 including Multi-ControlNet, LoRA, Aspect Ratio, Process Switches, and many more nodes.](https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes)
```
git clone https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes.git
```
[GitHub - cubiq/ComfyUI\_IPAdapter\_plus](https://github.com/cubiq/ComfyUI_IPAdapter_plus)
```
git clone https://github.com/cubiq/ComfyUI_IPAdapter_plus.git
```
[Page not found · GitHub · GitHub](https://github.com/sipherxyz/comfyui-art-venture.)
```
git clone https://github.com/sipherxyz/comfyui-art-venture.git
```
[GitHub - Kosinkadink/ComfyUI-Advanced-ControlNet: ControlNet scheduling and masking nodes with sliding context support](https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet)
```
git clone https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet.git
```
[GitHub - rgthree/rgthree-comfy: Making ComfyUI more comfortable!](https://github.com/rgthree/rgthree-comfy)
 ```
git clone https://github.com/rgthree/rgthree-comfy.git
```
[GitHub - shadowcz007/comfyui-mixlab-nodes: Workflow-to-APP、ScreenShare&FloatingVideo、GPT & 3D、SpeechRecognition&TTS](https://github.com/shadowcz007/comfyui-mixlab-nodes)
```
git clone  https://github.com/shadowcz007/comfyui-mixlab-nodes.git
```
### controlnet 模型
[sai\_xl\_canny\_256lora.safetensors · lllyasviel/sd\_control\_collection at main](https://huggingface.co/lllyasviel/sd_control_collection/blob/main/sai_xl_canny_256lora.safetensors)

[sai\_xl\_depth\_256lora.safetensors · lllyasviel/sd\_control\_collection at main](https://huggingface.co/lllyasviel/sd_control_collection/blob/main/sai_xl_depth_256lora.safetensors)

### clip_vision 模型
- /ComfyUI/models/clip_vision  
    - [CLIP-ViT-H-14-laion2B-s32B-b79K.safetensors](https://huggingface.co/h94/IP-Adapter/resolve/main/models/image_encoder/model.safetensors), download and rename  
    - [CLIP-ViT-bigG-14-laion2B-39B-b160k.safetensors](https://huggingface.co/h94/IP-Adapter/resolve/main/sdxl_models/image_encoder/model.safetensors), download and rename  

### 运行过程中还要下载模型，

# 没错 安装失败
本地安装失败。白下几十个 G,
切换在线使用复现琉璃效果

网站：[eSheep(内测中) - 一站式的AIGC社区](https://www.esheep.com/app)

工作流下载地址： [IMAGE TO 💎JADE STYLE | ComfyUI Workflow](https://openart.ai/workflows/xiongmu/image-to-jade-style/BRuUXjQhMaLu0dPOvZHD)

在线启动：
- 更换模型，checkpoint, lora, 放大模型，
- 上传图片，两个地方需要上传，
- 开始，
- 成功出图
- 对比：图片地址：[eSheep(内测中) - 一站式的AIGC社区](https://www.esheep.com/image/69780)

只要成功复现就说明步骤没问题，工作流也没问题。

同样的参数，在我的设备不是不能完全复现就是直接安装失败，模型下载了几十个 g, 靠北熬

好，好歹成功复现，增强学习信心。

后面准备一个案例学习一个 cmfyui功能