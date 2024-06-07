# ComfyUI Models Download
## Manual Download
- Hugging Face

[Hugging Face – The AI community building the future.](https://huggingface.co)

-  Civitai

[Civitai: The Home of Open-Source Generative AI](https://civitai.com)

## Tips
- 去模型网站看看别人的图片用的什么模型，参数设置
- 模型种类：
    - checkpoints：主模型
    - lora：辅助修改
    - embeddings：词向量
    - vae：图片处理
- 参数设置：
    - clip：prompt,
        - 正向
        - 反向
    - 采样器：
        - seed：随机种子
        - simpler：采样算法
        - scheduler：调度器
        - cfg：图片与prompt相关度
        - steps：采样步数
- 模型存放地址：

| 模型类型             | 放置路径示例                       | 描述                                |
| ---------------- | ---------------------------- | --------------------------------- |
| 大模型（Checkpoints） | `models\checkpoints` | Stable Diffusion的主要模型文件，通常较大。     |
| VAE模型            | `models\vae`         | VAE（Variational Autoencoder）模型文件。 |
| Lora模型           | `models\loras`       | Lora微调技术相关模型文件。                   |
| plugins          | `custom_nodes\`      | 插件目录，用于存放自定义节点。                   |

## plugin
- 暂时先推荐ComfyUI-Manager，有他就好说。

```sh
# git clone <repository-url> custom_nodes
cd custom_nodes
git clone https://github.com/ltdrdata/ComfyUI-Manager.git 

# AIGODLIKE-ComfyUI-Translation  汉化
# ControlNet  
# 重启 comfyui 生效
```