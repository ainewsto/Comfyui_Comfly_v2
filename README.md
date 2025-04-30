
# 👋🏻 Welcome to Comfly

此版本为无悬浮按钮版本，只有节点。


# 更新 Update：

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

视频教程： https://www.bilibili.com/video/BV1jxLUz9ECX

`Chatgpt节点`: 
新增Comfly_gpt_image_1和Comfly_gpt_image_1_edit官方gpt_image_1模型api接口节点。

![image](https://github.com/user-attachments/assets/9d08d5fc-dde9-4523-955c-31652a74f1a5)

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

20250418：
`jimeng即梦节点`: 新增即梦的ComflyJimengApi节点。
目前只支持文生图，使用的是 https://ai.comfly.chat 的 api key

参数说明：
use_pre_llm：开启文本扩写，会针对输入prompt进行扩写优化，如果输入prompt较短建议开启，如果输入prompt较长建议关闭。
scale：影响文本描述的程度，默认值：2.5，取值范围：[1, 10]
width，height：生成图像的宽和高，默认值：1328，取值范围：[512, 2048]
add_logo：是否添加水印。True为添加，False不添加。默认不添加
opacity：水印的不透明度，取值范围0-1，1表示完全不透明，默认0.3

<details>
<summary>查看更新/Update </summary>  
 
![3c1a498bea1853be7aafda2d7ea41b1](https://github.com/user-attachments/assets/13b84330-25d0-420b-9111-8e653f3ada99)

![16be3f66454ae4a74c7c5bc723f847f](https://github.com/user-attachments/assets/96351739-bbcb-476b-a516-1a6a265151db)

</details> 


20250401：
`所有节点`: 所有调用apikey的节点新增apikey输入框。优化可灵图生图视频节点。

20250329：
`Chatgpt节点`: 新增openai的ComflyChatGPTApi节点，。
目前单图和多图输入，文本输入，生成图片，图片编辑.使用的是 https://ai.comfly.chat 的 api key
固定一次生成消耗0.06元（显示是逆向api，稳定性还不高，想尝鲜的可以注册网站用免费送的0.2美金玩玩）
速度不快，因为官网速度也不快，所以需要点耐心。 files输入接口还没有完善，先忽略。
用sora_image现在先对稳定点

<details>
<summary>查看更新/Update </summary>  
 
![fdedd73cffa278d2a8cf81478b58e90](https://github.com/user-attachments/assets/36e78cdd-33b2-41ed-a15c-ad9c1886bede)


![0a2394c0b41efe190a5d0880f4c584b](https://github.com/user-attachments/assets/267fbe73-7113-4120-a829-a7aa2247bd4d)

</details> 


20250325：

`Kling节点`: 新增可灵Comfly_lip_sync对口型节点，生成效果还行吧。速度也一般般。支持中文和英文。

`Gemmi节点`: ComflyGeminiAPI节点resolution新增：object_image size,subject_image size,scene_image size根据输入的图片的尺寸来确定输出图片的尺寸。增加image url输出接口。

`Doubao豆包节点`: ComflySeededit节点文字驱动生成图片，编辑图片。支持添加自己的水印logo。目前只支持单图修改和参考。使用的是 https://ai.comfly.chat 的 api key

用于编辑图像的提示词 。建议：

添加/删除实体：添加/删除xxx（删除图上的女孩/添加一道彩虹）

修改实体：把xxx改成xxx（把手里的鸡腿变成汉堡）

修改风格：改成xxx风格（改成漫画风格）

修改色彩：把xxx改成xx颜色（把衣服改成粉色的）

修改动作：修改表情动作（让他哭/笑/生气）

修改环境背景：背景换成xxx，在xxx（背景换成海边/在星空下）

1：图片格式：JPG(JPEG), PNG, BMP 等常见格式, 建议使用JPG格式.

2：图片要求：小于4.7 MB，小于4096*4096

3：长边与短边比例在3以内，超出此比例或比例相对极端，会导致报错

<details>

<summary>查看更新/Update </summary>

![95836fbdda83551ca81ebc3db93b2d5](https://github.com/user-attachments/assets/0ce70dd3-eb0a-4e2e-bf6c-68642a48288d)

![563e17009b9100533f169aa1d87b37f](https://github.com/user-attachments/assets/48bd20e9-9d87-43d7-aa81-370c7c7f1bec)


</details>

20250321：`Gemmi节点`: 谷歌ComflyGeminiAPI节点支持生成文生多图（最多4张，控制时间）。
支持多图片参考，我是借用google labs的whisk思路，我感觉比较实用，并不需要太多参考图，3种足够.无需谷歌账户和梯子魔法就能用。使用的是 https://ai.comfly.chat 的 api key
<details>
<summary>查看更新/Update </summary>  
 
![微信图片_20250321225149](https://github.com/user-attachments/assets/593f479b-51d5-476e-bcf7-f36c4f01eb29)

</details> 

20250319：`Gemmi节点`: 新增谷歌ComflyGeminiAPI节点，gemini-2.0-flash-exp-image多模态模型。
目前只支持简单的单图输入和输出，图片回复，图片编辑.
<details>
<summary>查看更新/Update </summary>  
 
![微信图片_20250319214344](https://github.com/user-attachments/assets/4ef9216d-1a27-4b71-a5f9-ad4ef4bfc7eb)


</details> 

20250318：`kling节点`: 新增可灵文生视频，图生视频，视频延长（只支持v1.0模型）3个节点.
可灵视频生成时间大概要5-6分钟左右，使用的是 https://ai.comfly.chat 的 api key.
<details>
<summary>查看更新/Update </summary>  
 
![微信图片_20250318201313](https://github.com/user-attachments/assets/96836710-95f7-4100-96ed-58e5d6553124)

</details> 


