_发现一个问题_

我原封不动复制 c 站的参数下来在我的电脑上使用，出来的图片和作者不一样。

为此，我又在网上开启一个云 gpu 来再次生成这个参数的图片，

但是结果并不是和作者的一样而是和我的一样，所以, 我认为，这可能是由于作者的配置问题引起的，

比如能够影响图片的生成的 embedding ，lora, vae 等等没有给出的模型，
# ComfyUI Ex 4
# 日漫赛博御姐
[Fetching Title#ov1n](https://civitai.com/images/12172952)
- this civitai pic:
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/149d378e-ce16-4cab-b666-2b0afdaa71c1/original=true/00059-2425464473.jpeg)
## ComfyUI_Example_4_1

- 主模型: 麦橘写真, lora:nikke[0516 nikke Isabel（pony and 1.5） - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/433115/0516-nikke-isabel?modelVersionId=482481)
- my generated pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a42467f-a6d6-4c2f-8011-68940b810eb8/original=true/ComfyUI_00001_.jpeg)
- my generated pic with the cloud gpu :![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2581572-86b9-4414-8b50-9fccafdd506b/original=true/d55bbca18dbeda21aa44ef44fc32ebd9c163b1cc799d682d5057eb0243929b20.jpeg)
- 由此可见，我的本地和云端gpu好歹姿势是一样的，虽然生成的风格差别有点大，但是我生成的两个和C站作者差别也太大了。
- 经过浏览，作者的这个穿搭应该是启用了网站的一个lora,我忘记名字了
- 我用C站生成的图和作者的差不多，然后看到我C站使用的vae是kl-f8-anime2 vae ，而我使用的是vae-ft-mse-840000-ema-pruned 所以，这个问题解决了，包括一开始就找不到原因的案例一也差不多可以肯定就是这个原因了。
## c 站生成:
- 2024-05-20_ 19:26[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2883240)
## ComfyUI_Example_4_2
- 模型:
	- [Resident Evil Latex Costume 1 - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/445434/resident-evil-latex-costume-1?modelVersionId=496017)
	- [AniMesh - Animesh-Pruned V2.2 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/90642/animesh?modelVersionId=224732)
	- [EnvyBetterHands LoCon - beta2 | Stable Diffusion LyCORIS | Civitai](https://civitai.com/models/47085/envybetterhands-locon?modelVersionId=55199)
	- [kl-f8-anime2 VAE - kl-f8-anime2 VAE | Stable Diffusion VAE | Civitai](https://civitai.com/models/23906/kl-f8-anime2-vae?modelVersionId=28569)
- 生成
	- 2024-05-21_19:55
	- [Image post by kefu51252770 | Civitai](https://civitai.com/posts/2906142)
	- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08fbc675-4990-4413-b771-2630006c05f5/width=2048/ComfyUI_Example_4_00003_.jpeg)
