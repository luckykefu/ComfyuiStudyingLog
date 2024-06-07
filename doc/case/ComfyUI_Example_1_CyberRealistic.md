# 少女, 山上, 露出, 热爱大自然
_逛C站的时候看到的一张图片，不错,  决定复刻_
- url：[Image posted by xiaoxiaohuiji](https://civitai.com/images/10880329)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76f34435-346c-405b-b54e-3315fe33cd9a/original=true/00000-2576117923.jpeg)

_果然性是人类第一动力_

- 所包含模型url：
	- [epiCPhoto - epiCPhoto | Stable Diffusion Embedding | Civitai](https://civitai.com/models/195911/epicphoto?modelVersionId=220262)
	- [長乳locon / hanging breasts locon - v1 | Stable Diffusion LyCORIS | Civitai](https://civitai.com/models/16202/locon-hanging-breasts-locon?modelVersionId=19135)
	- [Add More Details - Detail Enhancer / Tweaker (细节调整) LoRA - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/82098/add-more-details-detail-enhancer-tweaker-lora?modelVersionId=87153)
	- [BadDream + UnrealisticDream (Negative Embeddings) - BadDream v1.0 | Stable Diffusion Embedding | Civitai](https://civitai.com/models/72437/baddream-unrealisticdream-negative-embeddings?modelVersionId=77169)
	- [PicXer - real | Stable Diffusion LoRA | Civitai](https://civitai.com/models/273909/picxer?modelVersionId=308719)
	- [LCM-LoRA - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/198694/lcm-lora?modelVersionId=223551)
	- [CyberRealistic Revamp - v3.2 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/385039/cyberrealistic-revamp?modelVersionId=429696)
	- [breast size slider - offset | Stable Diffusion LoRA | Civitai](https://civitai.com/models/131864/breast-size-slider?modelVersionId=146600)

- 下载模型，放在对应位置
- 启动comfyui 
- 打开本地UI http://127.0.0.1:8188/
- 把参数复制过来
- 开始炼丹
- 参数：工作流：
- 生成效果：[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2683657)
- 分析结果：
	- 眼睛不自然，（他的 prompt 里包含很多 lora 我只下载他给出的两个 lora ，初步猜测可能是这个引起的 ）
	- 清晰度不够，（没有使用 upscale 放大图片，可能是这个原因）
	- 没有大白腿，（可能是没有使用 lora）
	- 奶子下坠太厉害了，（可能是没有使用 lora）
- 改：
	- 清晰度问题就是没有使用 upscale ，
		- 加载 upscale，下载模型 : 放在 `model/upscale_models`, vaedecode 节点后面插入：图像--放大---图像通过模型放大。图像通过模型放大节点的放大模型连接到：加载器--放大模型加载器。
	- 下载全部 lora, 还是多张图片都不理想，可以考虑为采样算法带a,不能完全复现图片。
	- 眼睛有点古怪，可以看到虽然不能复现，但是可以增加眼睛或者面部 lora 改善这个情况，
	- 多次生成都是这个动作姿势，可能是vae解码模型不一样
## 总结
- 模型的选择是图片输出的主要来源，也是影响输出效果的关键因素。
- 我在 c 站同样的参数是能够复现的，排除设备的影响，我选择的这个图片没有工作流参考，具体原因还不能确定。
2024-05-20_ 19:08:[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2883051)


