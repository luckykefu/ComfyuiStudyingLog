_如果 vae 解码模型设置部队也会出现油画那样的失真_
# ComfyUI Ex 8
## 超逼真人物面部特写 2
模仿源：[Fetching Title#l6u4](https://civitai.com/images/12118185)![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5b8524f-3802-4ea9-bc50-8901271260a4/original=true/69A2E747B919EB8D245DC992AC20F6E55A58DDF77C39C5EA3F4305B3B142E198.jpeg)
和案例七类似
太逼真了
模型：
- [ZavyChromaXL - v7.0 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/119229/zavychromaxl?modelVersionId=490254)
- [SDXL VAE - SDXL-VAE | Stable Diffusion VAE | Civitai](https://civitai.com/models/296576/sdxl-vae?modelVersionId=333245)
- [TWbabeSDXL - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/151603/twbabesdxl?modelVersionId=169536)
- [Detail Tweaker XL - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/122359/detail-tweaker-xl?modelVersionId=135867)
- [TTPLanet\_SDXL\_Controlnet\_Tile\_Realistic - v2.0\_fp16 | Stable Diffusion Controlnet | Civitai](https://civitai.com/models/330313/ttplanetsdxlcontrolnettilerealistic)
- checkpoint: SDXL 升级版
- lora： detail tweaker xl, perfext eyes xl
- 结果预览:
- 七和八案例是要确保生成这样精细的画面不是偶然而是能够出工作流的
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f5fc81d-8373-498a-b96c-390be1e471e2/width=2048/b85ab63bdb3a60eb791f48ceb7dd627fbc68eb79ba8d13d0949e9e17aa0e4b66.jpeg)
# 总结:
这几个案例下来, 基本上能够复刻出同一种风格的图片出来, 虽然在细节上, 在创意上, 在精细度控制上还有差距, 但是, 这些都不是短时间能够补齐的东西, 需要长期磨练, 需要学习更多的知识才能够创作出来
##  control net tile 放大, 能够让图片更加清晰
## 多重采样, 去噪强度不必递减, 保持低强度即可
## 模型强度的增加可适当增加去噪强度
# IPAdapter Plus 使用
