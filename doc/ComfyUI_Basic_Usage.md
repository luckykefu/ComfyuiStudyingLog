# ComfyUI Basic Usage

##  Load Checkpoint 
 ![LoadCheckpointWithConfig-BN6zB4MN.svg](https://www.comfyuidoc.com/assets/LoadCheckpointWithConfig-BN6zB4MN.svg)
-  模型存放位置：`models\checkpoints`

## CLIP (Prompt) 输入提示词
![CLIPTextEncodePrompt-hZy3NNU2.svg](https://www.comfyuidoc.com/assets/CLIPTextEncodePrompt-hZy3NNU2.svg)
- 正向提示词
- 反向提示词
## Empty Latent Image
![](https://www.comfyuidoc.com/assets/EmptyLatentImage-D8EMT608.svg)
- 设置图像大小
## KSmapler 采样器设置
![](https://www.comfyuidoc.com/assets/KSampler-LOr6cHLj.svg)
- seed
    - 种子：相同的种子值每次都会产生相同的图像集
- CONTROL after generated
    - 控制生存后种子的值，变化还是不变
- steps
    - 步数
- cfg
	- 生成的图像和文本相关性，值和相关性正比
	- 参考： [Stable Diffusion 的 CFG Scale 参数 - 蝈蝈俊 - 博客园](https://www.cnblogs.com/ghj1976/p/stable-diffusion-de-cfg-scale-can-shu.html)
- sampler_name
    - 采样算法
	- 参考：[彻底搞定ComfyUI中的采样器和调度器 - 技术栈](https://jishuzhan.net/article/1777525178465521666)
    - 参考：[全面理解Stable Diffusion采样器 - 知乎](https://zhuanlan.zhihu.com/p/673899723)
	    - 在对比了各个采样器在多个维度的表现之后，推荐如下：
			- 如果想要速度快、收敛性好、质量也不错，且想试试新东西的话，最好选择：
				- DPM++ 2M Karras、20-30 步
				- UniPC、20-30 步
			- 如果想要比较好的质量，同时不在意是否收敛的话，可以选择：
				- DPM++ SDE Karras、10-15 步 （注意该采样器比较慢）
				-  DDIM、10-15 步
			 - 如果想要稳定、可复现的结果，不要用任何带有随机性的采样器，比如祖先采样器
			 - 如果想生成一些简单的结果，可以用 Euler 或 Heun。在使用 Heun 时，可以调低一些步数来节省时间。
- scheduler
    - 调度算法
		- normal：
		- karras：
- denoise
    - 初始噪声值
	
## Vae 
![](https://www.comfyuidoc.com/assets/VAEDecode-B-picWPt.svg)
- 变分自编码器
- 图像编码和解码
## Save Image
![](https://www.comfyuidoc.com/assets/SaveImage-z3yAym7e.svg)

_以上就是出一张图的基本操作流程，后面是案例实践_

