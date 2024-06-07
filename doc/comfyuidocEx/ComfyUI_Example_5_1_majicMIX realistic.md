_cfg 如果设置太高会出现油画那样的失真_
# ComfyUI Ex 5 1
## 超逼真人物面部特写
模仿源：[Fetching Title#vc24](https://civitai.com/images/753660)![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/bb16f656-90b1-48ce-ba0e-f7aa5db1069d/original=true/01589-1370404257-(masterpiece),%20 best%20 quality,%20 ultra%20 high%20 res,%20 close%20 up,%20 slim%20 body,%201 girl, school%20 uniform,%20 long%20 hair,%20 laughing,%20 ramen,%20 night,%20 Tokyo. jpeg)
这个太惊艳了, 细节，色调，用来打口红，妆容的广告简直不要太好，
可能存在的困难：
- 细节，也就是画面颗粒感，
- 色调
- 眼神
好，开始
模型：
- checkpoint：majicMIX realistic[majicMIX realistic 麦橘写实 - v4 | Stable Diffusion Checkpoint | Civitai](https://civitai.com/models/43331/majicmix-realistic?modelVersionId=55911)
- lora： Asian girls face [Asian girls face - v1.0 | Stable Diffusion LoRA | Civitai](https://civitai.com/models/62760/asian-girls-face?modelVersionId=67325)
- _画面皮肤有大疙瘩，降低 lora_比例试试_
- _分块 vae 解码_和编码_这个类似分割放大_
- _锐化放大放在最后输出图片的地方_
- 脸部已经快接近效果了，但是手部皮肤会有皱纹
- 把手部去掉，脖子又有皱纹
- 开了第二个云，第二个云没有皱纹，靠北，怎么回事
- 解决了，cfg 调高了，
- 结果：[Page Not Found](https://civitai.com/posts/2737040)
- 预览：![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/7db2db6a-94b8-4405-8d53-8847fcd6b120/width=700/3%20(1). jpeg)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/d1fcbdd1-1f81-49ed-835a-f9bc8266782b/width=700/4dfd752c1024333615aed6f034afc6f2488af9ae12d04e3bfbcc1c3cff8e32f7.jpeg)
- ![](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/f87833df-863a-4fad-b733-b4b690473412/original=true/2%20(2). jpeg)
- 现在是细节和眼神处理得还行，最后就是色调，复刻原图的色调实在太迷人了，虽然我也可以后期，但是如果可以直接就输出那样的图，为什么不呢，他的口红简直都可以接广告了，
- 色调的问题在加个 lora 还是换个模型，还是什么办法，今天就到这里了，
- _vae 解码模型也会对生成的图片造成影响, 那种碎片错误的图片_
2024-05-21_ 23:15
