---
created: '2024-06-08 '
---
# 女孩，机械身躯

url: [Image posted by hostInShell](https://civitai.com/images/652645)
workflow：[](../workflow/GhostMix.json)
#GhostMix

img:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3ba53358-aa09-4e2b-883b-ecc1564a2900/width=1024,quality=90/22759-3696906123-(masterpiece,%20top%20quality,%20best%20quality,%20official%20art,%20beautiful%20and%20aesthetic_1.2),%20(1girl_1.3),%20extreme%20detailed,colorful,high.jpeg)

model and lora:

- [Fetching Title#knvz](https://civitai.com/models/4629/deep-negative-v1x?modelVersionId=5637)
- [Fetching Title#eukj](https://civitai.com/models/36520/ghostmix?modelVersionId=76907)
- [Fetching Title#uzob](https://civitai.com/models/22354/clearvaesd15?modelVersionId=88156)
- [Fetching Title#uwyv](https://civitai.com/models/135737/golden-tech-world-morph?modelVersionId=149683)

## myGEN：

- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e2a440e5-b5bf-460d-800f-356b09e30545/width=512/43C86FF3D4F82334C15FAAE0CD49027A0B308CF7A68E0595159B0608233C0B80.jpeg)

- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a505c93b-5525-462f-b29e-e150264b980b/width=512/EA1283CEEDCA3C2FD7B57B55EBD10D3AC4ABA06D8ED65D08BD7CD483588748B6.jpeg)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/393c82d1-1735-4bc6-9418-09fb25b9c25d/width=512/642896C910854056622DCB798DEBB9D136C66BA50D8580110949B6653A895F7D.jpeg)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/494a8fe5-5df8-436a-8658-d82260c610e7/width=512/A5AEC26117C5A61F293B3A3F35C8BE77D5684D2E2388D83B1DC915CC4CB20259.jpeg)
# 女孩，侧颜杀，cool

url ：
workflow:[](../workflow/ComfyUI_Example_3.json)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c5b7e6a6-b9dc-4cc6-a981-e9036a972a3e/original=true/45.jpeg)
- 模型：
- [GhostMix - v2.0-BakedVAE | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/36520/ghostmix?modelVersionId=76907)

## 利用controlnet固定姿势，和外表大概样子，
- 参考网址：[ControlNet 和 T2I-适配器示例 | ComfyUI 手册](https://www.comfyuidoc.com/zh/Examples/controlnet/)
- 下载 controlnet 插件
- 下载模型 [stablediffusionapi/anything-v5 at main](https://huggingface.co/stablediffusionapi/anything-v5/tree/main/safety_checker)
- 下载 controlnet 涂鸦模型[control\_v11p\_sd15\_scribble.pth lllyasviel/ControlNet-v1-1 at main](https://huggingface.co/lllyasviel/ControlNet-v1-1/blob/main/control_v11p_sd15_scribble.pth)
- vae：[vae-ft-mse-840000-ema-pruned.ckpt · stabilityai/sd-vae-ft-mse-original at main](https://huggingface.co/stabilityai/sd-vae-ft-mse-original/blob/main/vae-ft-mse-840000-ema-pruned.ckpt)
### 涂鸦 ControlNet
  - 加载工作流：
    - 下载图片
    - comfyui 里加载图片
    - 复现成功
    
- 使用 T 2 I-适配器
	- 将 Load ControlNet Model 改为 Load ControlNet Model (diff)
	- 左侧连接 checkpoint 的 model

### 姿势 controlnet
下载模型：
下载 controlnet 模型：[control\_v11p\_sd15\_openpose.pth · lllyasviel/ControlNet-v1-1 at main](https://huggingface.co/lllyasviel/ControlNet-v1-1/blob/main/control_v11p_sd15_openpose.pth)
## MyGEN：
  - https://civitai.com/posts/2672387
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8dd29ae7-80de-4001-a5fc-db010d33c129/original=true/15a9cbf00e710eec6af07e18b647fd7ef576e4f6f1a98223bcb9a1aec1b6153c.jpeg)
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac5022c3-733e-4f06-a8b8-9bbae539974c/original=true/986a78506633172c411e39fd077997c512d3d48edc51defe36786c22a9adf96e.jpeg)
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ae2e6a52-4fda-4073-8989-4dffe73d49f0/original=true/25393dc5af848d08eb0a4178862ab24ce0d4ebd90cd763bebeefb9a42666f39e.jpeg)
  - ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e109f9ee-4a19-42be-8bf3-a9d66175f8b4/original=true/ed022d974a26276e3835df289cc5b419955e14390342b471c632f55f42de3f62.jpeg)
### 总结
- 虽然没有百分百复刻出来，但是作者什么信息都没给，这个程度，以我的初学者水平能够接受，
# 动画，女孩，黑色胶衣，cool
#AniMesh
url：[Image posted by kefu51252770](https://civitai.com/images/12172952)
ref img:
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/149d378e-ce16-4cab-b666-2b0afdaa71c1/original=true/00059-2425464473.jpeg)
## Example_4_1
workflow:
- 主模型: 麦橘写真, lora:nikke [0516 nikke Isabel（pony and 1.5） - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/433115/0516-nikke-isabel?modelVersionId=482481)
- my generated pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8a42467f-a6d6-4c2f-8011-68940b810eb8/original=true/ComfyUI_00001_.jpeg)
- my generated pic with the cloud gpu :![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b2581572-86b9-4414-8b50-9fccafdd506b/original=true/d55bbca18dbeda21aa44ef44fc32ebd9c163b1cc799d682d5057eb0243929b20.jpeg)
- 由此可见，我的本地和云端 gpu 好歹姿势是一样的，虽然生成的风格差别有点大，但是我生成的两个和 C 站作者差别也太大了。
- 经过浏览，作者的这个穿搭应该是启用了网站的一个 lora, 我忘记名字了
- 我用 C 站生成的图和作者的差不多，然后看到我 C 站使用的 vae 是 kl-f 8-anime 2 vae ，而我使用的是 vae-ft-mse-840000-ema-pruned 所以，这个问题解决了，包括一开始就找不到原因的案例一也差不多可以肯定就是这个原因了。
## c 站生成:
- 2024-05-20_ 19:26[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2883240)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/17c3c5f5-565b-4522-951d-131d0e4af716/width=700/ComfyUI_00006_.jpeg)
## ComfyUI_Example_4_2
workflow:[](../workflow/GhostMix2.json)
- 模型:
	- [Resident Evil Latex Costume 1 - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/445434/resident-evil-latex-costume-1?modelVersionId=496017)
	- [AniMesh - Animesh-Pruned V2.2 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/90642/animesh?modelVersionId=224732)
	- [EnvyBetterHands LoCon - beta2 | Stable Diffusion LyCORIS | Civitai](https://civitai.com/models/47085/envybetterhands-locon?modelVersionId=55199)
	- [kl-f8-anime2 VAE - kl-f8-anime2 VAE | Stable Diffusion VAE | Civitai](https://civitai.com/models/23906/kl-f8-anime2-vae?modelVersionId=28569)
- 生成
	- 2024-05-21_ 19:55
	- [Image post by kefu51252770 | Civitai](https://civitai.com/posts/2906142)
	- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/08fbc675-4990-4413-b771-2630006c05f5/width=2048/ComfyUI_Example_4_00003_.jpeg)
_发现一个问题_

我原封不动复制 c 站的参数下来在我的电脑上使用，出来的图片和作者不一样。

为此，我又在网上开启一个云 gpu 来再次生成这个参数的图片，

但是结果并不是和作者的一样而是和我的一样，所以, 我认为，这可能是由于作者的配置问题引起的，

比如能够影响图片的生成的 embedding ，lora, vae 等等没有给出的模型，

# 沙发，女孩，二郎腿
#majicMIXreallistic 

url: [Fetching Title#ygzg](https://civitai.com/images/1733579)
img:
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a768b16f-41b0-4eb7-89f0-5f6dbdfb0687/original=true/00010-2503085764.jpeg)

模型：
-  [majicMIX realistic 麦橘写实 - BETTER v2 = v2.5 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/43331/majicmix-realistic?modelVersionId=126470)
workflow:[](../workflow/majicMIXreallistic.json)
## MyGEN:

2024-05-20_ 20:04[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2883861)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/502b2f01-f9d4-48f8-a26f-0fb1b218c943/width=1556,quality=90/ComfyUI_temp_aupsy_00001_.jpeg) ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f6017b07-07ad-4269-8848-02b5359e42f9/width=1556,quality=90/ComfyUI_temp_aupsy_00006_.jpeg)

# 女孩，脸部特写
#majicMIXreallistic 
url：[Image posted by ChenL666](https://civitai.com/images/753660)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bb16f656-90b1-48ce-ba0e-f7aa5db1069d/original=true/01589-1370404257-(masterpiece),%20 best%20 quality,%20 ultra%20 high%20 res,%20 close%20 up,%20 slim%20 body,%201 girl, school%20 uniform,%20 long%20 hair,%20 laughing,%20 ramen,%20 night,%20 Tokyo. jpeg)
这个太惊艳了, 细节，色调，用来打口红，妆容的广告简直不要太好，
可能存在的困难：
- 细节，也就是画面颗粒感，
- 色调
- 眼神
好，开始
模型：
- checkpoint：majicMIX realistic [majicMIX realistic 麦橘写实 - v4 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/43331/majicmix-realistic?modelVersionId=55911)
- lora： Asian girls face [Asian girls face - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/62760/asian-girls-face?modelVersionId=67325)
workflow：[](../workflow/majicMIXreallistic2.json)
- _画面皮肤有大疙瘩，降低 lora_比例试试_
- _分块 vae 解码_和编码_这个类似分割放大_
- _锐化放大放在最后输出图片的地方_
- 脸部已经快接近效果了，但是手部皮肤会有皱纹
- 把手部去掉，脖子又有皱纹
- 开了第二个云，第二个云没有皱纹，靠北，怎么回事
- 解决了，cfg 调高了，

## MyGEN：
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2737040)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7db2db6a-94b8-4405-8d53-8847fcd6b120/width=700/3%20(1). jpeg)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1fcbdd1-1f81-49ed-835a-f9bc8266782b/width=700/4dfd752c1024333615aed6f034afc6f2488af9ae12d04e3bfbcc1c3cff8e32f7.jpeg)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f87833df-863a-4fad-b733-b4b690473412/original=true/2%20(2). jpeg)
- 现在是细节和眼神处理得还行，最后就是色调，复刻原图的色调实在太迷人了，虽然我也可以后期，但是如果可以直接就输出那样的图，为什么不呢，他的口红简直都可以接广告了，
- 色调的问题在加个 lora 还是换个模型，还是什么办法，今天就到这里了，
- _vae 解码模型也会对生成的图片造成影响, 那种碎片错误的图片_
2024-05-21_ 23:15
_cfg 如果设置太高会出现油画那样的失真_
# 女孩，白色短发，可爱
#chilloutmix 
url：[Site Unreachable](https://civitai.com/images/12300777)
pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9a77af36-7cce-44ea-43e0-a114bf779b00/width=1513/163560.jpeg)
- model：
	- checkpoint：[ChilloutMix - Chilloutmix-Ni-pruned-fp32-fix | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/6424/chilloutmix?modelVersionId=11745)
	- lora：
	- emmbedded：

workflow：[](../workflow/chilloutmix3.json)
## MyGEN
# 女孩，脸部特写，细腻 
#ZavyChromaXL
url：[Fetching Title#l6u4](https://civitai.com/images/12118185)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e5b8524f-3802-4ea9-bc50-8901271260a4/original=true/69A2E747B919EB8D245DC992AC20F6E55A58DDF77C39C5EA3F4305B3B142E198.jpeg)
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

workflow：[](../workflow/ZavyChromaXL.json)
## MyGEN
- 七和八案例是要确保生成这样精细的画面不是偶然而是能够出工作流的
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3f5fc81d-8373-498a-b96c-390be1e471e2/width=2048/b85ab63bdb3a60eb791f48ceb7dd627fbc68eb79ba8d13d0949e9e17aa0e4b66.jpeg)
### 总结:
这几个案例下来, 基本上能够复刻出同一种风格的图片出来, 虽然在细节上, 在创意上, 在精细度控制上还有差距, 但是, 这些都不是短时间能够补齐的东西, 需要长期磨练, 需要学习更多的知识才能够创作出来
###  control net tile 放大, 能够让图片更加清晰
### 多重采样, 去噪强度不必递减, 保持低强度即可
### 模型强度的增加可适当增加去噪强度
## IPAdapter Plus 使用
_如果 vae 解码模型设置部队也会出现油画那样的失真_
# 女孩，可爱，户外，男友视角
#majicMIXsombre
url：[Image posted by kefu51252770](https://civitai.com/images/12299078)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1ada02a3-a6e1-4171-bf7f-68d8f45ebf73/width=512,quality=90/CFBB21F63328047B419F52C19A462F976D45F4DACD28E0C432F5477ECB705011.jpeg)
- model：
	- [EasyNegative - EasyNegative | Stable Diffusion Embedding | Civitai](https://civitai.com/models/7808/easynegative?modelVersionId=9208)
	- [Cute\_girl\_mix4 - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/14171/cutegirlmix4?modelVersionId=16677)
	- [majicMIX sombre 麦橘唯美 - v2.0 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/62778/majicmix-sombre?modelVersionId=75209)
	- [ClearVAE(SD1.5) - v2.3 | Stable Diffusion VAE | Civitai](https://civitai.com/models/22354/clearvaesd15?modelVersionId=88156)

workflow：[](../workflow/majicMIXsombre.json)
## MyGEN  
# 沙发，女孩，麦橘梦幻
#majicMIXsombre 
- url：[Image posted by kefu51252770](https://civitai.com/images/12298147)
- pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e96f6144-7e9b-4358-9bcf-d090f00038eb/width=512,quality=90/5348B09E84C6BD3CC3B4CB7402D7286143C2E9E054E5E111A73CA322AD71D4CE.jpeg)
- model：
	- [ClearVAE(SD1.5) - v2.3 | Stable Diffusion VAE | Civitai](https://civitai.com/models/22354/clearvaesd15?modelVersionId=88156)
	- [Eye - LoRa - Eyes\_V1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/5529/eye-lora?modelVersionId=6433)
	- [Fetching Title#uahg](https://civitai.com/models/62778/majicmix-sombre?modelVersionId=75209)
workflow：[](../workflow/majicMIXsombre1.json)
## MyGEN  
# 2 girl, 迪士尼，深情对视
#PonyDiffusionV6 
url: [Image posted by Stellaaa](https://civitai.com/images/9679258) 
img:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4b4ad911-c1dd-46fd-b5ee-7057028ddd07/width=1408/2024-04-06-021053_ponyDiffusionV6XL_v6StartWithThisOne_3673610310_euler_ancestral.karras.25_cfg7.0_USX_FD.jpeg)
不能放大重绘, 缺少 controlnet xl tile 模型
2024-05-22_ 05:34
- [ExpressiveH (Hentai LoRa Style) エロアニメ - ExpressiveH | Stable Diffusion LoRA | Civitai](https://civitai.com/models/341353/expressiveh-hentai-lora-style?modelVersionId=382152)
- [Pony Diffusion V6 XL - V6 (start with this one) | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/257749/pony-diffusion-v6-xl?modelVersionId=290640)
- [Vixon's Pony Styles - gothic oil v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/352581/vixons-pony-styles?modelVersionId=394299)
- [Styles for Pony Diffusion V6 XL (Not Artists styles) - Concept Art Twilight | Stable Diffusion LoRA | Civitai](https://civitai.com/models/264290/styles-for-pony-diffusion-v6-xl-not-artists-styles?modelVersionId=330475)
- [Sinfully Stylish (dramatic lighting) - For SDXL v0.1 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/340248/sinfully-stylish-dramatic-lighting?modelVersionId=407532)
- 
workflow：[](../workflow/PonyDiffusionV62.json)
## MyGEN  

# 黑白，写实
#moxiediffusionXL
url：[Image posted by moxie1776](https://civitai.com/images/7554959) 
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9dcfb90c-32e1-443b-b283-c1861e6f4d2e/width=832/00406-2024-03-06_.jpeg)
缺 tile 模型
2024-05-22_ 06:43[Moxie Diffusion XL - v1.32 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/260460/moxie-diffusion-xl?modelVersionId=375981)
[Linquivera - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/249837/linquivera?modelVersionId=281935)
workflow：[](../workflow/moxiediffusionXL.json)
## MyGEN  

# 古风，妖娆妩媚
#xxmix9realistic
[Fetching Title#k1v2](https://civitai.com/images/1667702) ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/deb1ed25-6fdd-45c9-8108-0737a1c5c336/width=1024/00265-2711264555.jpeg)
没有那个眼神啊喂
workflow：[](../workflow/xxmix9realistic.json)
## MyGEN  

![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9b138de2-f9e7-4172-a48c-9c5e659ba45f/width=2048/aed030e9d7bbf9c8b610282c771dfd25035af234010005e4f0f037be0eeec7b3.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f99acf0f-0db5-4a20-8d8e-74a114799cb8/width=2048/bc8122a767fe824f1be7d5f5c50828b118ba294d00fc6ebfa9b57e573c7b53cb.jpeg)2024-05-22_ 07:29
[XXMix\_9realistic - v4.0 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/47274/xxmix9realistic?modelVersionId=102222)
[anxiang | 暗香 - anxiang | Stable Diffusion LoRA | Civitai](https://civitai.com/models/94087/anxiang-or?modelVersionId=120452)
[LowRA-OFFSET NOISE - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/221845/lowra-offset-noise)
[OC - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/43227/oc)
[Smoke - Smoke v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/62757/smoke)
# 女孩，双马尾，beauty

[Image posted by Yuki\_Hotaru](https://civitai.com/images/7302052) 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/dd11fd62-e96c-49fa-8517-1920f9572b98/width=768/242.jpeg)
[Fetching Title#g6bt](https://civitai.com/images/10804911)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d540c9de-5e36-4584-a384-6c6f3f6d2a61/width=1070/336.jpeg)

忘记用什么模型了
workflow：
## MyGEN  
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2852526)

![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/cc9168bd-5d9a-4879-88a3-e33c01534e96/width=2049/1c0bfd96526576b39c5e4f358410cedbd81a017f10784744a623849fd2f0c55a.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/88de980e-7d75-4baf-93ec-63bbcd68fbe6/width=2049/80c822e77bac90767c321d873b7523564d4666f7b9977139752b048ccde46b4a.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/9793bcb9-e092-4505-9c46-24b5ca573147/width=2049/c0d2675c5321e35531cdad068ab974be0b2ee7544738e97d73d0f76acdbb3c45.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c3eab3c1-1638-4e26-864f-6060f15406c6/width=2049/e83e507b9cda21e14c34a6f93c10b11b941d7a8c32bda52677197b94fd69c525.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6ae8518c-39bc-4e4a-8b4c-b16b168737a2/width=2049/f57e1d4464327e19e6974cd2dfcc0254349111d24514435ec482d9973c50db82.jpeg)
2024-05-22_ 08:05
# 古风，谁说女子不如男
#Redbluefantasy
workflow：[](../workflow/Redbluefantasy.json)
[Image posted by ChaosOrchestrator](https://civitai.com/images/7021498) ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/38bca0b7-8eee-4e9a-bfa4-8167732c70aa/width=1024/00278-2945277364.jpeg)
2024-05-22_ 09:27
[绪儿-红蓝幻想 Red-blue fantasy - v2.0 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/313098/red-blue-fantasy?modelVersionId=351315)
[Sword Sakura剣桜(Photographic style) - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/282753/sword-sakuraphotographic-style?modelVersionId=318252)
[Unlimited Blade Works (UBW) | Weapon LyCORIS \[Axe, Bows, DualWielding, Fan, Katana, Knife, Kunai, Lightsaber, MasterSword, Planted Swords, Scythe, Sheathed, Shield, Spear, Staff, Tomahawk, Trident, Unsheathing, Warhammer, Whip\] - v 2.01 Katana One Hand | Stable Diffusion LyCORIS | Civitai](https://civitai.com/models/69323/unlimited-blade-works-ubw-or-weapon-lycoris-axe-bows-dualwielding-fan-katana-knife-kunai-lightsaber-mastersword-planted-swords-scythe-sheathed-shield-spear-staff-tomahawk-trident-unsheathing-warhammer-whip?modelVersionId=223864)
[EasyNegative - EasyNegative | Stable Diffusion Embedding | Civitai](https://civitai.com/models/7808/easynegative?modelVersionId=9208)

## MyGEN

# 卡通，女孩，旗袍，异域风情
#RealCartoonXL
[Image posted by kefu51252770](https://civitai.com/images/12297724)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/02354c66-fde1-42c0-a7f1-3bedfcaa01d0/width=512,quality=90/9A13B4BAF81FC0FE59FA384F014EF1B03296B1E39B36CB871B1B75A4A1F8867C.jpeg)
[RealCartoon3D - V15 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/94809/realcartoon3d?modelVersionId=393843)

workflow：[](../workflow/RealCartoonXL.json)

## MyGEN 
# 卡通，女孩，回眸一笑，心动的感觉
#RealCartoonXL 
[Fetching Title#3ub3](https://civitai.com/images/9078035) 

![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ab2daea7-2269-436b-acad-e6c73ee8af83/width=720/00115-4033382240.jpeg)
[Site Unreachable](https://civitai.com/models/125907/realcartoon-xl?modelVersionId=254091) 2024-05-22_ 17:55
workflow：[](../workflow/RealCartoonXL1.json)
## MyGEN
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2932254)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8eda8e60-048e-405a-ba41-760174de9260/width=1556,quality=90/ComfyUI_temp_tyasj_00001_.jpeg)
# 卡通，梦幻仙境，女孩
#lyriel
- url：[Fetching Title#85vw](https://civitai.com/images/724449)
- pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/24e1e52b-17e8-4c56-a4a5-02466c048147/width=1856/00063-158005779.0.jpeg)
- model：
	- checkpoint：[Fetching Title#p8c1](https://civitai.com/models/22922/lyriel?modelVersionId=50127)
	- lora：[Windranger arcana dota lora - 1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/21912/windranger-arcana-dota-lora)
	- emmbedded：
workflow：[](../workflow/lyriel.json)
# 动漫，女孩，仙境
#blazingDrive
[Image posted by Yoshistrider](https://civitai.com/images/9068908) ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/989e1f53-0164-4951-a5f5-127c6eed5f1d/width=4096/00005-1036743912_US4.jpeg)
无模型
2024-05-22_ 19:50
- [Whispers of Zen - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/378524/whispers-of-zen?modelVersionId=422644)
- [Rin Tohsaka (Fate/Stay) - Lora Pony | SD 1.5 - SD 1.5 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/291308/rin-tohsaka-fatestay-lora-pony-or-sd-15?modelVersionId=327473)
-  [Blazing Drive - \_V13md | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/121083/blazing-drive)
- 
workflow：[](../workflow/blazingDrive.json)
# 女孩，艺术画，colorful
#majicmixreverie
[Image posted by dkorbat](https://civitai.com/images/814848) 
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/fe681a42-a29b-4264-bc29-13ffcfa34d59/width=1024/00380-3515475520.jpeg)
[Page Not Found](https://civitai.com/posts/2870217)
2024-05-22_ 20:26
- [majicMIX reverie 麦橘梦幻 - v1.0 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/65055/majicmix-reverie?modelVersionId=69687)
- [Abstract Dreamwave - GPTS4 Full | Stable Diffusion LyCORIS | Civitai](https://civitai.com/models/62293/abstract-dreamwave?modelVersionId=71264)
- 
workflow：[](../workflow/majicmixreverie.json)
# 狐狸，写实
#jibmixrealisticXL
- url：[Image posted by F42](https://civitai.com/images/12515146)
- pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6f9fb782-21ec-4a40-848f-10cc6c726e7f/width=832/B2B85D1E72A1CD92511A5E8095B0A8D1BE2AFEE9128651EB43801A602A06AF4D.jpeg)
- model：
	- checkpoint：[Jib Mix Realistic XL - v11.0 PenUltimate Detail | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/194768/jib-mix-realistic-xl?modelVersionId=462183)
	- lora：[OMG-Is-DucHaiten (lora fixes everything sdxl) - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/377395/omg-is-duchaiten-lora-fixes-everything-sdxl?modelVersionId=421428)
	- [Detail Tweaker XL - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/122359/detail-tweaker-xl?modelVersionId=135867)
	- 
	- emmbedded：[EasyNegative - EasyNegative | Stable Diffusion Embedding | Civitai](https://civitai.com/models/7808/easynegative?modelVersionId=9208)
	- [Deep Negative V1.x - V1 75T | Stable Diffusion Embedding | Civitai](https://civitai.com/models/4629/deep-negative-v1x?modelVersionId=5637)
	- 
workflow：[](../workflow/jibmixrealisticXL.json)
# 动漫，日本，节日
#duchaitenponyXL
- url：[Image posted by DucHaiten](https://civitai.com/images/11369655)
- pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb5a4793-ac3d-4298-8e0b-38746214b843/width=1536,quality=90/01017-209951850.jpeg)
- model：
	- checkpoint：[DucHaiten-Pony-XL (no-score) - Pony-no\_score\_v3.0 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/376450/duchaiten-pony-xl-no-score?modelVersionId=481945)
	- lora：
	- emmbedded：
	- 
workflow：[](../workflow/duchaitenponyXL.json)
# 2.5 D 动漫，细节
## 案例 1

#Niji3dstyle #lyriel #Dreamshaper 
模仿源：[Image posted by Mazz\_W](https://civitai.com/images/718471)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/4c0ccb9b-8426-4e33-b4fe-bbca293efc32/original=true/Mazz_Earth_1440.jpeg)
这看起来难度有点大啊
不管
按流程：找模型，找 lora 模型，写 prompt，出图
- 模型：[SDVN7-NijiStyleXL - v1 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/123307/sdvn7-nijistylexl?modelVersionId=155870) 看起来一点也不相关
- lora：[extremely detailed (no trigger) - sliders.ntcai.xyz - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/229213/extremely-detailed-no-trigger-slidersntcaixyz?modelVersionId=258687)
- prompt：一个女孩，站在龙头上，沙尘漫天，在空中，
- 出图：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d443f2a0-737a-4da5-a1c5-bb70c488fe89/original=true/2b61b7ef7e40855508fc99f980860268077172e7c47136db4b4d8aec11fa43e1.jpeg)
- 评价：差远了，
- 出图：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/713a4675-1df1-4f80-b62d-0a5911764719/original=true/ed4e640ced8e6c45d7b221b35258b2c55f33f23006bf934996ed5b1dd7094433.jpeg)
- 评价：同上，
- 出：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8c5b88f5-170f-4212-9bbe-7da8db30d7b1/original=true/252864069edad0d7d0751c27ff82cd60a4acf91fc62032430afdcd10330e398f.jpeg)
- ps: face is oh my god 
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/68c04364-5ee1-4d24-afa7-792689a68810/original=true/28c74d6e4848cf28ba2df29e679a09c460574b953dacb977d3ceb65384b75845.jpeg)
- ps: just so so, 不过细节还可，

- 不管怎么改 prompt, 女人就是不骑在龙头上，而且龙占了 主体，而女人是却成了点缀，
- 所以，这个复刻应该算是 失败的，要好好 学一下怎么写 prompt,
- 还有，好好研究怎么让细节更加惊叹，
- 和原图还是有很大的差别的，烟雾和沙尘的细节，光影的艺术，等等，人物的刻画也是，那个主角太有生命力了


- 今天继续这个话题吧，不复刻出来，难受
- 模型合并：[模型合并示例 | ComfyUI 手册](https://www.comfyuidoc.com/zh/Examples/model_merging/)
- 图像放大：[图像放大节点（Upscale Image） | ComfyUI 手册](https://www.comfyuidoc.com/zh/Core%20Nodes/Image/upscaling/UpscaleImage.html)
- controlnet：[ControlNet 和 T2I-适配器示例 | ComfyUI 手册](https://www.comfyuidoc.com/zh/Examples/controlnet/)
-  两步 Txt 2 Img（高分辨率修复）示例：[两步Txt2Img（高分辨率修复）示例 | ComfyUI 手册](https://www.comfyuidoc.com/zh/Examples/2_pass_txt2img/)
- 获取图片尺寸：getimagesize
- 图片反推提示词：[GitHub - pythongosssss/ComfyUI-WD14-Tagger: A ComfyUI extension allowing for the interrogation of booru tags from images.](https://github.com/pythongosssss/ComfyUI-WD14-Tagger)
- 图片缩放：resize
- 图片分割放大算法：[Stable Diffusion ComfyUI 基础教程（六）图片放大与细节修复 - 知乎](https://zhuanlan.zhihu.com/p/680926870)
- 第一 次：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ecffe07d-c62e-4c95-9a4d-f50396fd254e/original=true/ComfyUI_temp_yfzsm_00005_.jpeg)
- 细节和 prompt 今天算是有进步，为什么只发了一张图片，因为在搞细节，图片搞到一百 m 去了，上传不了网络，看不了，接单说一下结果，那就是细节处理搞错了方向，我以为是放大图片展示细节，但是只放大了图片，而细节处理，云 gpn 都干爆了，起码得买 a 100 才行，或者学习其他方法弥补细节，图片分割放大是各可行的方案，
- 今天依旧是实践细节的处理，图片依旧放大到能够容纳我想要的细节的尺寸，关键是 gpn 处理不了，所以今天学习图片分割放大算法，看看内不能在有限的资源条件下将图片清晰放大，
- 还有：放大模型中：upscalesharp 处理二次元会锐化，结果不好，不如其他放大模型

今天的任务：图片 分割放大算法的应用 
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a730da5b-469a-4b73-9480-3e54775ab9f2/original=true/7f74b6c194e373257d6c0e44d7f1765fe8019de9d840c19a9a046f92025e43e0.jpeg)
- 这是 2 d 风格，换个模型或者采用模型合并添加 3 d 风格进去
```
Error occurred when executing KSampler: 
'ModuleList' object has no attribute '1'
'ModuleList' object has no attribute '1'
```
- [Image post by kefu51252770 | Civitai](https://civitai.com/posts/2732781)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ac0d7ecd-c0d0-4d32-a9e4-ca246cbf2b91/width=700/99ff24db51f11766c727387ee98a6ade0bbbeb075828166a3986e56196930462.jpeg)
- 可以说这是三天里生成效果 ，最接近的，虽然烟雾的处理，眼睛，等等都还有差距，但是这可是 ai, 能接受，
总结：一个初学者决定复刻这个东西，真是折磨，可以从我生成的图片可看到，从最初的姿势动作，也就是 controlnet 都不会用，到最后，图片风格，内容都比较接近，算是入门了吧。
为了节省计算资源我还没有执行放大步骤，如果放大的话，效果应该会更好一点的。

workflow：[](../workflow/ComfyUI_Example_6.json)
模型:
- [Fetching Title#hr21](https://civitai.com/models/46898/niji3dstyle)
- [Fetching Title#i988](https://civitai.com/images/808323)
- [Fetching Title#4hpw](https://civitai.com/models/4384/dreamshaper)
- [Fetching Title#mmlq](https://civitai.com/models/44023/nijiexpressivev1)

## 案例 2
- url：[Fetching Title#crzj](https://civitai.com/images/718391)
- pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e71fa169-51ae-497c-8527-11200fadb2ca/width=1440/Mazz_Aqua_1440.jpeg)
workflow：[](../workflow/ComfyUI_Example_6_1.json)
## MyGEN
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2932112)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/98c93b51-3269-4bd4-be83-da1da404c7b8/width=1800,quality=90/1de3df2f7b12d38d386bb4a0809b11046510939dc134581a70d24f2627c97984.jpeg)
