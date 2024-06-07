# ComfyUI Examples 3

# ControlNet
参考网址：https://www.comfyuidoc.com/zh/Examples/controlnet/

## 准备工作
- 下载controlnet 插件
- 下载模型 [stablediffusionapi/anything-v5 at main](https://huggingface.co/stablediffusionapi/anything-v5/tree/main/safety_checker)
- 下载 controlnet 涂鸦模型
	-[control\_v11p\_sd15\_scribble.pth · lllyasviel/ControlNet-v1-1 at main](https://huggingface.co/lllyasviel/ControlNet-v1-1/blob/main/control_v11p_sd15_scribble.pth)
- vae：[vae-ft-mse-840000-ema-pruned.ckpt · stabilityai/sd-vae-ft-mse-original at main](https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt)
### 涂鸦 ControlNet
  - 加载工作流：
    - 下载图片
    - comfyui里加载图片
    - 复现成功
    
- 使用 T 2 I-适配器
	- 将Load ControlNet Model 改为Load ControlNet Model (diff)
	- 左侧连接 checkpoint 的model

### 姿势 controlnet
下载模型：
下载 controlnet 模型：[control\_v11p\_sd15\_openpose.pth · lllyasviel/ControlNet-v1-1 at main](https://huggingface.co/lllyasviel/ControlNet-v1-1/blob/main/control_v11p_sd15_openpose.pth)
# 案例三 复刻赛博女杀手
有了 control net 后面复刻会好很多，
准备复刻一张什么信息都没有的图片：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5b7e6a6-b9dc-4cc6-a981-e9036a972a3e/original=true/45.jpeg)
- 模型：[GhostMix - v2.0-BakedVAE | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/36520/ghostmix?modelVersionId=76907)
- 写prompt：
- 利用controlnet固定姿势，和外表大概样子，
- 最终得到如下效果：
  - https://civitai.com/posts/2672387
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8dd29ae7-80de-4001-a5fc-db010d33c129/original=true/15a9cbf00e710eec6af07e18b647fd7ef576e4f6f1a98223bcb9a1aec1b6153c.jpeg)
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac5022c3-733e-4f06-a8b8-9bbae539974c/original=true/986a78506633172c411e39fd077997c512d3d48edc51defe36786c22a9adf96e.jpeg)
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae2e6a52-4fda-4073-8989-4dffe73d49f0/original=true/25393dc5af848d08eb0a4178862ab24ce0d4ebd90cd763bebeefb9a42666f39e.jpeg)
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e109f9ee-4a19-42be-8bf3-a9d66175f8b4/original=true/ed022d974a26276e3835df289cc5b419955e14390342b471c632f55f42de3f62.jpeg)


## 总结
- 虽然没有百分百复刻出来，但是作者什么信息都没给，这个程度，以我的初学者水平能够接受，
- 参数
2024-05-20_ 19:14[Page Not Found](https://civitai.com/posts/2883180)
