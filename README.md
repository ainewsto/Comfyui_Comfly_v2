
# 👋🏻 Welcome to Comfly

# 此版本为无悬浮按钮版本，只有节点。


# 更新 Update：

20250911：

`Comfly_Googel_Veo3:节点`: Veo 模型大幅降价，文生视频支持设置横、竖屏


20250909：

`Comfly_Doubao_Seedream_4节点`: 新增节点："Comfly Doubao Seedream4.0


20250903：

`Comfly_gpt_image_1_edit节点`: 参数新增input fidelity，partial_images参数

20250902：

`Comfly_nano_banana_edit节点`: 新增节点Comfly_nano_banana_edit，这个可以选择生成图片的尺寸，模型只能是：nano-banana
文生图下尺寸才能生效，图生图不生效。

20250829：

`Comfly_MiniMax_video节点`: 新增节点Comfly_MiniMax_video，支持海螺ai全部视频模型，支持最新首尾帧。
具体模型能力和参数选择请查看官方文档，避免使用错误：
https://platform.minimaxi.com/document/video_generation?key=66d1439376e52fcee2853049


20250828：

目前官方返无图的可能性比较高，所以需要你开魔法，并且节点在美国（我测试这样的情况基本没有问题，有问题加群）

`Comfly_nano_banana_fal节点`: 新增节点Comfly_nano_banana_fal，这个可以生成1到4张图片，nano-banana为文生图模型。
nano-banana/edit为图生图模型（图生图模型会产生额外的图片上传费用，具体可以看网站日志，在网站异步任务也可查看任务信息）

`Comfly_nano_banana节点`: 新增模型nano-banana选项，这个模型不容易被识别成对话模型，

20250827：

`Comfly_nano_banana节点`: 新增节点：Comfly_nano_banana（文生图，图生图，支持多图参考编辑），
谷歌最强编辑模型：gemini-2.5-flash-image-preview，
有默认和gemini优质两个分组。价格比官方便宜很多。可以在cherrystudio里面的newapi供应商填写我的api中转站调用模型使用。


20250819：

`qwen image_edit节点`: 新增千问图片编辑节点：Comfly_qwen_image_edit，价格0.1.
可以自定义尺寸（size选择Custom后，在Custom_size输入分辨率即可，例如1280x720）。
num_images生成图片数量是1到4张，注意api计算是按照图片张数来的，生成越多，api消费就多。

20250814：

`doubao节点`: 新增节点：Comfly_Doubao_Seedream和Comfly_Doubao_Seededit都是3.0模型


20250807：

`qwen image节点`: 新增千问绘图节点：Comfly_qwen_image，价格全网最低~
可以自定义尺寸（size选择Custom后，在Custom_size输入分辨率即可，例如1280x720）。
num_images生成图片数量是1到4张，注意api计算是按照图片张数来的，生成越多，api消费就多。

20250731：

`mj 换脸节点`: 新增mj换脸节点：Comfly_Mj_swap_face，修复mju，mjv节点bug。


20250729：

`kling 可灵节点`: 新增可灵多图参考视频节点：Comfly_kling_multi_image2video，最多支持4个参考图，只支持1.6模型。
新增2.1模型选择。 

20250722：

`mj video延长节点`: 新增mj视频延长节点：Comfly_mj_video_extend，一次生成4个视频，按次收费。

task id是接入上一次生成视频的task id 输出内容。
index 是选择延长上一次生成的4个视频里面的哪一个做为延迟，范围是0,1,2,3，对应的是第一，二，三，四视频
视频最多延长4次，一次延长4s。

20250722：

`mj video节点`: 新增mj视频节点：Comfly_mj_video，一次生成4个视频，按次收费。 


20250716：删除了Comfly_kling_videoPreview节点，视频节点的video输出接口可以直接连接comfyui本体的save video节点。

20250714：

`Googel veo3节点`: veo3谷歌视频，新增veo3-fast-frames模型，图生视频


20250630：

`Googel veo3节点`: 

新增Comfly_Googel_Veo3节点，文生视频模型：veo3，veo3-fast，veo3-pro。图生视频模型：veo3-pro-frames。 
enhance_prompt开关：
是否优化提示词，一般是false；由于 veo 只支持英文提示词，所以如果需要中文自动转成英文提示词，可以开启此开关。
目前4个模型都是自动生成带音效的。无法手动关闭，并且不支持选择生成视频尺寸，默认都是生成横幅视频。


20250627：

`Flux节点`: Comfly_Flux_Kontext，Comfly_Flux_Kontext_Edit两个节点新增flux-kontext-dev模型


20250613：

`Flux节点`: 新增bfl官方节点：Comfly_Flux_Kontext_bfl节点，价格不变

20250611：

`Flux节点`: Comfly_Flux_Kontext_Edit节点支持设置出图数量（1-4张范围），这个节点不会消耗上传图片费用，直接传入图片即可，
           跟Comfly_Flux_Kontext一样，就是上传图片不会扣费，图片输入支持base64图片编码格式，可以做为稳定性的备用节点。

20250601：

`Flux节点`: Comfly_Flux_Kontext节点支持设置出图数量（1-4张范围），支持多图输入。
已经支持对上一次生成的图片再次提示词编辑（但只有当出土数量选择1时才可以使用这个。


20250526：

`Jimeng即梦视频节点`: 新增ComflyJimengVideoApi节点。即梦视频，按次收费，5s是0.6元，10s是1.2元。
<details>
<summary>查看更新/Update </summary>  
 
![75ae4f4c3b061c0a7f7d1b1eb1b0264](https://github.com/user-attachments/assets/a8533eef-8233-4c35-ab1b-c9a26d5ddf72)

</details> 

20250518：

`Flux节点`: 新增Comfly_Flux_Kontext节点，支持：flux-kontext-pro和flux-kontext-max模型，按次收费：pro模型大约0.096元，max大约0.192元，比官方便宜很多。


20250518：

`Kling节点`: 可灵节点新增kling-v2-master的可灵2.0模型。价格很贵，按需使用。

20250429：

`Chatgpt节点`: Comfly_gpt_image_1_edit新增chats输出口，输出多轮对话。
新增clear_chats,当为Ture的时候，只能image输入什么图片修改什么图片，不支持显示上下文对话。
当为Flase的时候，支持对上一次生成的图片进行二次修改。支持显示上下文对话。并且支持多图模式下新增图片参考。

<details>
<summary>查看更新/Update </summary>  
 
![2eaf76b077612170647f6861e43e2af](https://github.com/user-attachments/assets/1c4c484f-c3c6-48c6-96c5-58c4ef4e59d5)

![6a43cb051fece84815ac6036bee3a4c](https://github.com/user-attachments/assets/f0fbf71e-8cfb-448e-87cd-1e147bb2f552)

</details> 

20250425：


`Chatgpt节点`: 
新增Comfly_gpt_image_1和Comfly_gpt_image_1_edit官方gpt_image_1模型api接口节点。

模型名都是gpt_image_1，区别只是分组不同：

一共四个分组：default默认分组为官方逆向，价格便宜，缺点就是不稳定，速度慢。按次收费。不支持额外参数选择。这个分组的apikey只能用于ComflyChatGPTApi节点。

其他三个组都是官方api组，最优惠的目前是ssvip组。分组需要再令牌里面去修改选择。这3个官方分组优点就是速度快，稳定性高。支持官方参数调整。
缺点就是贵，但是也比官方便宜。大家可以按照自己的情况选择。这3个分组的令牌的apikey只能用在下面2个新节点上面！！！

1. Comfly_gpt_image_1 节点：文生图，有耕读参数调整，支持调整生图限制为low。

2. Comfly_gpt_image_1_edit 节点：图生图，支持mask遮罩，支持多图参考。

<details>
<summary>查看更新/Update </summary>  
 
![3bc790641c44e373aca97ea4a1de47e](https://github.com/user-attachments/assets/1a7a0615-46e5-46b3-af04-32246a23d6f4)

![5efe58fcf7055d675962f40c1ad1cbb](https://github.com/user-attachments/assets/8a90eab5-4242-43bb-ae01-74493b90b6ce)

</details> 

20250424：
`Chatgpt节点`: ComflyChatGPTApi节点新增官方gpt-image-1，按次计费 0.06，
旧版的gpt4o-image，gpt4o-image-vip，sora_image, sora_image-vip可以做为备选。首选gpt-image-1。

`jimeng即梦节点`: 即梦的ComflyJimengApi节点新增参考图生成图片，image url图片链接参考生成图片。
注意：参考图生成图片会额外消耗上传图片的token费用（具体根据你图片大小来，大部分都是0.000几到0.00几元不等。图片链接有时效性，不做长期储存），
这个只适用于你没有image url图片链接的前提下使用。
如果你有image url图片链接，就直接填写在image url里面既可以。

<details>
<summary>查看更新/Update </summary>  
 
![e1abc11e855680b70985ec9f339a967](https://github.com/user-attachments/assets/6d77c103-d35a-4c6b-804a-4b5add172bcf)

![307e5ea0d789b785fd0a60f01f2b8cf](https://github.com/user-attachments/assets/5c8a7984-ae5e-4cbf-aa47-b09bc7e6f8d6)

</details> 

20250422：
`Chatgpt节点`: ComflyChatGPTApi节点新增chats输出口，输出多轮对话。
新增clear_chats,当为Ture的时候，只能image输入什么图片修改什么图片，不支持显示上下文对话。
当为Flase的时候，支持对上一次生成的图片进行二次修改。支持显示上下文对话。

<details>
<summary>查看更新/Update </summary>  

![cad243f2bf4a3aa11163f1a007db469](https://github.com/user-attachments/assets/ef0f6a34-3de7-42a2-8543-c1930575e1bb)

![bd6493050affdf156143c8dc5286988](https://github.com/user-attachments/assets/0906caf3-35ec-4061-bfc9-5f611a19abf2)

![e5b3d375b700dcbf921b12a8aa527c4](https://github.com/user-attachments/assets/75537100-e5d2-403c-b2e0-1f662680092f)


</details> 
