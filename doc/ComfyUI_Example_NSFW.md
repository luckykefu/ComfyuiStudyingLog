---
created: '2024-06-08 '
---
# 少女, 山上, 露出, 热爱大自然
#majicMIXreallistic
_逛 C 站的时候看到的一张图片，不错,  决定复刻_
- url：[Image posted by xiaoxiaohuiji](https://civitai.com/images/10880329)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/76f34435-346c-405b-b54e-3315fe33cd9a/original=true/00000-2576117923.jpeg)

2024-06-09_ 21:19原作已被作者删除
下面是我的本地保存：![ss](../workflow/majicMIXreallistic1.jpeg)
_果然性是人类第一动力_

- 所包含模型 url：
	- [epiCPhoto - epiCPhoto | Stable Diffusion Embedding | Civitai](https://civitai.com/models/195911/epicphoto?modelVersionId=220262)
	- [長乳locon / hanging breasts locon - v1 | Stable Diffusion LyCORIS | Civitai](https://civitai.com/models/16202/locon-hanging-breasts-locon?modelVersionId=19135)
	- [Add More Details - Detail Enhancer / Tweaker (细节调整) LoRA - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/82098/add-more-details-detail-enhancer-tweaker-lora?modelVersionId=87153)
	- [BadDream + UnrealisticDream (Negative Embeddings) - BadDream v1.0 | Stable Diffusion Embedding | Civitai](https://civitai.com/models/72437/baddream-unrealisticdream-negative-embeddings?modelVersionId=77169)
	- [PicXer - real | Stable Diffusion LoRA | Civitai](https://civitai.com/models/273909/picxer?modelVersionId=308719)
	- [LCM-LoRA - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/198694/lcm-lora?modelVersionId=223551)
	- [CyberRealistic Revamp - v3.2 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/385039/cyberrealistic-revamp?modelVersionId=429696)
	- [breast size slider - offset | Stable Diffusion LoRA | Civitai](https://civitai.com/models/131864/breast-size-slider?modelVersionId=146600)

workflow:[](../workflow/majicMIXreallistic1.json)
- 分析结果：
	- 眼睛不自然，（他的 prompt 里包含很多 lora 我只下载他给出的两个 lora ，初步猜测可能是这个引起的 ）
	- 清晰度不够，（没有使用 upscale 放大图片，可能是这个原因）
	- 没有大白腿，（可能是没有使用 lora）
	- 奶子下坠太厉害了，（可能是没有使用 lora）
- 改：
	- 清晰度问题就是没有使用 upscale ，
		- 加载 upscale，下载模型 : 放在 `model/upscale_models`, vaedecode 节点后面插入：图像--放大---图像通过模型放大。图像通过模型放大节点的放大模型连接到：加载器--放大模型加载器。
	- 下载全部 lora, 还是多张图片都不理想，可以考虑为采样算法带 a, 不能完全复现图片。
	- 眼睛有点古怪，可以看到虽然不能复现，但是可以增加眼睛或者面部 lora 改善这个情况，
	- 多次生成都是这个动作姿势，可能是 vae 解码模型不一样
总结：
- 模型的选择是图片输出的主要来源，也是影响输出效果的关键因素。
- 我在 c 站同样的参数是能够复现的，排除设备的影响，我选择的这个图片没有工作流参考，具体原因还不能确定。
2024-05-20_ 19:08:[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2883051)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f44b09e1-dced-4baa-ba98-25e761e0e5da/width=1800,quality=90/ComfyUI_temp_spjqu_00003_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c82a276-189b-4222-a43b-18be6519fac9/width=1800,quality=90/ComfyUI_temp_ymrbh_00001_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/48a52512-f666-46ef-9174-3a59e301de00/width=1800,quality=90/ComfyUI_temp_ymrbh_00003_.jpeg)

# 女孩，裸体，水彩画，艺术
#majicMIXreallistic 
url：[Image posted by weilonggs](https://civitai.com/images/1306068)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0cd7992e-6da7-45af-9aba-867f7c470aed/width=1024/01745-1815530824-(oil%20 painting_1.5),%20 (NSFW_1.2),%201 girl,%20 feature,%20 pureerosface_v 1,%20%20 Ambilight,%20%20 slender%20 waist,%20%20 (Lying_1.2),%20 (blue%20 tattoo,%20 Paint%20 p. jpeg)

workflow:[](../workflow/majicMIXreallistic3.json)
## MyGEN：
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2852345)
[Page Not Found](https://civitai.com/posts/2852345)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/77220182-3cda-4753-9b24-5e7ae0303de4/width=1556/ComfyUI_temp_lkmqv_00001_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/25151593-8f3b-4385-adb4-8c84ff53d0de/width=1556/ComfyUI_temp_lkmqv_00002_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/767c8705-c6ad-4cf9-b52d-b0d8763051be/width=1556/ComfyUI_temp_lkmqv_00003_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e0bb4b3a-60b6-4388-9e9e-9faf2b1da459/width=1556/ComfyUI_temp_mpket_00003_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/a7b65e7a-b854-40e3-b4e2-c392c37659de/width=1556/ComfyUI_temp_mpket_00005_.jpeg)

![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/8fdc1cf6-e172-43e3-9012-91689395d80d/width=1556/ComfyUI_temp_mpket_00008_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/6b1681a0-f9f9-42f5-babe-561de5aa233c/width=2049/ComfyUI_temp_sxnif_00001_.jpeg)

2024-05-22_ 06:45
[majicMIX realistic 麦橘写实 - v4 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/43331/majicmix-realistic?modelVersionId=55911)
[Fetching Title#hn22](https://civitai.com/models/88207)
[chunmomoLora - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/43305?modelVersionId=47941)
# 户外，露出，女孩，眼睛
#majicMIXreallistic 
url：[Image posted by Bei3](https://civitai.com/images/1230942) 
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/98163e11-ba1a-4842-892c-56238df03465/width=1024/01688-97117974-1girl,,%20 pubic%20 hair,%20 (looking%20 at%20 viewer,%20 light%20 smile,%20),%20 brown%20 hair,%20 brown%20 eyes,%20%20 long%20 hair,%20 hair_flying,%20 Fluttering%20 hair,%20 flying. jpeg)
2024-05-22_ 19:56
- [majicMIX realistic 麦橘写实 - v6 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/43331/majicmix-realistic?modelVersionId=94640)
- [badhandv4 - badhandv4 | Stable Diffusion Embedding | Civitai](https://civitai.com/models/16993/badhandv4?modelVersionId=20068)
- [EasyNegative - EasyNegative | Stable Diffusion Embedding | Civitai](https://civitai.com/models/7808/easynegative?modelVersionId=9208)
- [Detail Tweaker LoRA (细节调整LoRA) - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/58390/detail-tweaker-lora-lora?modelVersionId=62833)
- 
workflow：[](../workflow/majicMIXreallistic4.json)
## MyGEN
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2825253)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1c5b8dfa-e743-4f1d-8c10-f87317856789/width=1536,quality=90/ComfyUI_temp_csarg_00001_.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/b9c71c58-4ca2-4f42-a84a-0d0b6c509627/width=1800,quality=90/ComfyUI_temp_csarg_00002_.jpeg)
# 广场，露出，女孩
#chilloutmix
rul：[Image posted by 3260431574266](https://civitai.com/images/363986)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1fadebda-dfa9-410a-5776-62e578d8a200/width=512/363986.jpeg)
模型：
- checkpoint: `chilloutmix_NiPrunedFp32Fix` [Fetching Title#tzid](https://civitai.com/models/6424/chilloutmix?modelVersionId=11745)
- lora：  `Cute_girl_mix4` [Fetching Title#b2ty](https://civitai.com/models/14171/cutegirlmix4?modelVersionId=16677)
workflow：[](../workflow/chilloutmix.json)
## MyGEN:
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/23939412-9737-4653-9bd6-ceac28ac537b/width=2048/64e9e2ad08d6603a053a2dc26134367beac35643b378a1895427ed36758493ae.jpeg)
太高清了, 没有朦朦胧胧的那种感觉,
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/1f979316-3038-421c-b04f-9d3e7b12cd1a/width=2048/ComfyUI_temp_pvtlk_00001_.jpeg)
没有用 lora 就是这样
# 户外，篮球场，露出，女孩
#chilloutmix 

url： [Image posted by AssWeCan\_2023](https://civitai.com/images/347646)
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/3c542c28-e491-472c-2299-f4de714ad700/width=1024/347646.jpeg)
结果: 没有奶子
原因: 没有用 lora
[ChilloutMix - Chilloutmix-Ni-pruned-fp32-fix | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/6424/chilloutmix?modelVersionId=11745)
lora:
- [Shirtlift: a LORA for flashing tits - Shirtliftv1 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/6693/shirtlift-a-lora-for-flashing-tits?modelVersionId=7870)
- [Pure Eros Face - PureErosFace\_v1 | Stable Diffusion Embedding | Civitai](https://civitai.com/models/4514/pure-eros-face)
- [koreanDollLikeness\_v10 - koreanDollLikeness\_v10 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/19356/koreandolllikenessv10)
- [ShojoVibe少女感 - v1.1 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/13213?modelVersionId=16557)
- [JapaneseDollLikeness (v1.5) - v1.5 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/28811/japanesedolllikeness-v15)
- [Cute\_girl\_mix4 - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/14171/cutegirlmix4)

workflow：[](../workflow/chilloutmix1.json)
## MyGEN
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c56d7c7a-4058-43fc-9438-24d657e1b1a4/width=2048/d38a34400e4663bd40dcd740457d73cbe5cc7a088ed4aee9059d2c7b29aaad2a.jpeg)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/907068ed-02f7-43fa-8102-c45d80442e99/width=2048/2b9cd603969f511f7bfab7dc1e8baab12f54cf09cac53c9cba43332fdb8bd798.jpeg)
# 裸体，私房，女孩，床
#chilloutmix 
url：[Image posted by su943515688459](https://civitai.com/images/295538)
img：
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/e73216ad-a0a5-4770-37f2-df3dd504f000/width=512/295538.jpeg)
- model：
	- checkpoint：
	- lora：
		- [Cute\_girl\_mix4 - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/14171/cutegirlmix4)
		- [JapaneseDollLikeness (v1.5) - v1.5 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/28811/japanesedolllikeness-v15)
		- [KoreanDollLikeness (v2.0) - v2.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/26124/koreandolllikeness-v20)
		- [ChilloutMixss - xss1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/10850/chilloutmixss)
	- emmbedded：[Pure Eros Face - PureErosFace\_v1 | Stable Diffusion Embedding | Civitai](https://civitai.com/models/4514/pure-eros-face)

workflow：[](../workflow/chilloutmix2.json)
## Mygen
# make love
#PonyDiffusionV6
url：[Image posted by Pharo](https://civitai.com/images/9232495) 
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/442066a0-ca11-463c-b83d-27594e87b7d5/width=832/58143DBBDDD3AE53DC2CC5557521912B856EFD3B004776B5501986903BD3C73F.jpeg)
2024-05-22_ 19:24
- [Detail Tweaker XL - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/122359/detail-tweaker-xl?modelVersionId=135867)
- [All Disney Princess XL LoRA Model from Ralph Breaks the Internet - v2.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/212532/all-disney-princess-xl-lora-model-from-ralph-breaks-the-internet?modelVersionId=244808)
- [Pony Diffusion V6 XL - V6 (start with this one) | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/257749/pony-diffusion-v6-xl?modelVersionId=290640)
- [Deep Throat XL - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/274845/deep-throat-xl?modelVersionId=309802)
- [Styles for Pony Diffusion V6 XL (Not Artists styles) - Concept Art Twilight | Stable Diffusion LoRA | Civitai](https://civitai.com/models/264290/styles-for-pony-diffusion-v6-xl-not-artists-styles?modelVersionId=330475)
- [\[GP\] somethingweird style \[Pony XL\] - v 1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/315703/gp-somethingweird-style-pony-xl?modelVersionId=354128)
- [ExpressiveH (Hentai LoRa Style) エロアニメ - ExpressiveH | Stable Diffusion LoRA | Civitai](https://civitai.com/models/341353/expressiveh-hentai-lora-style?modelVersionId=382152)
- [Vixon's Pony Styles - gothic neon v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/352581/vixons-pony-styles?modelVersionId=398847)
- 
workflow：[](../workflow/PonyDiffusionV 6. json)
## MyGEN  
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2932445)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/da6ef69e-9d69-4382-943b-43699e841e09/width=700/ComfyUI_temp_rdkek_00003_.jpeg)
# 女孩，床上，荷尔蒙，欲望
url：[Fetching Title#80du](https://civitai.com/images/11351158) 
img：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/c531b7ee-d363-4e1a-86bd-2337e05fe474/width=832/F62E4A05B6EC67ACA5B9F89510D19D90BE764E12E858607A64FC81FBC5CD4FBE.jpeg)
2024-05-22_ 20:29
- [Alice In Wonderland! Disney - SD 1.5 | XL PONY - by YeiyeiArt - Alice - XL PONY V. | Stable Diffusion LoRA | Civitai](https://civitai.com/models/35930/alice-in-wonderland-disney-sd-15-or-xl-pony-by-yeiyeiart?modelVersionId=388595)
- [ExpressiveH (Hentai LoRa Style) エロアニメ - ExpressiveH | Stable Diffusion LoRA | Civitai](https://civitai.com/models/341353/expressiveh-hentai-lora-style?modelVersionId=382152)
- [\[GP\] somethingweird style \[Pony XL\] - v 1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/315703/gp-somethingweird-style-pony-xl?modelVersionId=354128)
- [Styles for Pony Diffusion V6 XL (Not Artists styles) - Concept Art Twilight | Stable Diffusion LoRA | Civitai](https://civitai.com/models/264290/styles-for-pony-diffusion-v6-xl-not-artists-styles?modelVersionId=330475)
- [Pony Diffusion V6 XL - V6 (start with this one) | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/257749/pony-diffusion-v6-xl?modelVersionId=290640)
- [Detail Tweaker XL - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/122359/detail-tweaker-xl?modelVersionId=135867)
- 
workflow：[](../workflow/PonyDiffusionV61. json)
## MyGEN  
[Image post by kefu51252770 | Civitai](https://civitai.com/posts/2933788)
![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/208712c8-c901-47b3-8496-2b7178c99b0d/width=1800,quality=90/ComfyUI_Example_11_2_00003_.jpeg)
# 自慰，女孩，卧室，床上
#mengxmixfantasy
- url：[Fetching Title#txb4](https://civitai.com/images/2500154)
- pic:![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/0566c98b-d84f-4c28-82ab-33d899833d9e/width=1024/00006-1727106929.jpeg)
- model：
	- checkpoint：[MengX\_Mix\_Fantasy - V2 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/145378/mengxmixfantasy?modelVersionId=161716)
	- lora：[Perfect pussy - v0.1 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/10844/perfect-pussy?modelVersionId=61391)
	- emmbedded：[Deep Negative V1.x - V1 75T | Stable Diffusion Embedding | Civitai](https://civitai.com/models/4629/deep-negative-v1x?modelVersionId=5637)
		- [badhandv4 - badhandv4 | Stable Diffusion Embedding | Civitai](https://civitai.com/models/16993/badhandv4?modelVersionId=20068)
	- [ClearVAE(SD1.5) - v2.3 | Stable Diffusion VAE | Civitai](https://civitai.com/models/22354?modelVersionId=88156)
workflow：[](../workflow/mengxmixfantasy.json)
## MyGEN  
