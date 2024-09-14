---
created: '2024-06-05 '
---
## prompt 提示词基本书写tips
- 词的位置与其权重正相关
- 符号分割
- 基本结构
	- 主体
	- 环境
	- 媒介
	- 风格
        - 时间
        - 地点
        - 人物
        - 场景

## embedding 模型
-  提示词增强
- 下载 `embedding` 模型放在`models/embeddings` 文件夹内

- 加载模型

_右键单击 CLIP Text Encode 节点,
然后选择顶部选项“Prepend Embedding Picker”。
如果直接连接到text的embedding节点，则append 设置为true_

## loRA
![LoadLoRA-Bng2EN8f.svg](https://www.comfyuidoc.com/assets/LoadLoRA-Bng2EN8f.svg)
- 微调，滤镜的意思
- 连接、
    - 左：checkpoint
    - 右：clip, ksampler

## 额外功能
- iamge 2 image![](https://www.comfyuidoc.com/assets/img2imgExample-Xo6WpEPU.png)
	- add load image node
		- right click
		- all node 
		- image
	- add clip vision encode
		- ![CLIPVisionEncode-CftDdXV-.svg](https://www.comfyuidoc.com/assets/CLIPVisionEncode-CftDdXV-.svg)
		- encode image
		- right click
		- all node 
		- conditioning
	- add unclipconditioning node![unCLIPConditioning-DLHXFnff.svg](https://www.comfyuidoc.com/assets/unCLIPConditioning-DLHXFnff.svg)
		- 融合 text encode 和 image encode
		- right click
		- all node
		- conditioning
	- 
- upscale
![LoadUpscaleModel-C74PIl6V.svg](https://www.comfyuidoc.com/assets/LoadUpscaleModel-C74PIl6V.svg)

## 采样器

![](https://file.jishuzhan.net/article/1777525178465521666/33aa107a108666d5038166b66352fb6d.webp)

