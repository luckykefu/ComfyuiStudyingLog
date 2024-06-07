# lora 的组合使用
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


模型:
- [Fetching Title#hr21](https://civitai.com/models/46898/niji3dstyle)
- [Fetching Title#i988](https://civitai.com/images/808323)
- [Fetching Title#4hpw](https://civitai.com/models/4384/dreamshaper)
- [Fetching Title#mmlq](https://civitai.com/models/44023/nijiexpressivev1)
- 