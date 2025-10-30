# 画面切换和音乐戒律的结合

Deforum视频

Parseq参数定序器，Audio Reference音频参考，识别节拍点，转换成为json格式的参数，配合提示词或者动效的关键镇的变化

<img width="449" height="310" alt="image" src="https://github.com/user-attachments/assets/7493d148-7e82-431a-b143-35108f0fbf18" />

节奏

使用stable diffusion创作出来一组符合需要的静态图像的作品

再将他们输入到图生视频的模型当中

controlnet

保留一个logo这样的有准确形体的元素

提取他的线稿或者景深的特征在生成的时候加入controlnet一类的控制生成的模型

风格和色调的一致性，挑选合适的大模型或者lora组合来实现的

comfyUI+AnimateDiff风格转绘短片

弱控制风格转绘， 转绘是在已有的基础上生成的形象类似的但是风格完全不同的新的视频

AnimateDiff现在基本上是风格化转绘的标配

<img width="953" height="532" alt="image" src="https://github.com/user-attachments/assets/b5d31a63-0679-4558-8517-57389578eea0" />

SAM+Grounding DINO的智能扣像的模型

Controlnet是控制人物形象的关键，也是负责维持转绘结果和原画面的相似性的

Depth或者SoftEdge这种比较常见的方案？

<img width="925" height="513" alt="image" src="https://github.com/user-attachments/assets/629b95f7-7429-4ce8-a2da-0293f44b0e21" />

黑白区域具有明显的响应，

白色是100%的控制，黑色是0%的控制。

控制原视频的黑白值来控制生成视频的效果

直接在ppt上绘制黑白图形，控制风格转换的方式

IP-Adapter更加轻量一些

<img width="967" height="506" alt="image" src="https://github.com/user-attachments/assets/49ee8d00-28eb-4f5d-adf2-7adf4b11f66a" />

只是需要上传一张风格的参考图，就可以把人变成看到的火焰，雪花，

<img width="929" height="477" alt="image" src="https://github.com/user-attachments/assets/565e77ea-e6dc-4046-960b-25d56fc6eb67" />

https://www.bilibili.com/video/BV1F8zBYLEKp/
