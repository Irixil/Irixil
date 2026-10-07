# 素材与字体

云海底图使用内置 imagegen 生成，未调用独立模型 API 脚本。文字、个人通行证和动图由本项目的 Pillow 程序重新绘制。未使用参考网站截图、商标、商业字体或功能代码作为交付素材。

视觉构图参考：[dope.security](https://dope.security/) 的暮光云海与黑底功能入口。参考只用于观察构图和动效，未包含在发布候选包中。

四种字体均来自 [Google Fonts 开源字体库](https://github.com/google/fonts)，使用 SIL Open Font License 1.1，许可证保存在 licenses 目录。发布候选包只包含渲染图片与许可证，不包含字体二进制文件。

- [Noto Sans SC](https://github.com/google/fonts/tree/main/ofl/notosanssc)：中文无衬线。
- [Noto Serif SC](https://github.com/google/fonts/tree/main/ofl/notoserifsc)：中文衬线。
- [Cormorant Garamond](https://github.com/google/fonts/tree/main/ofl/cormorantgaramond)：英文斜体。
- [Space Mono](https://github.com/google/fonts/tree/main/ofl/spacemono)：入口与辅助字。

猫头鹰插画使用用户提供的原图，等比缩小后完整置于卡片中；未裁切红围巾与剑。发布图片不带原文件元数据。

## 底图生成提示

Use case: stylized-concept. Asset type: original atmospheric background for a 1200x720 GitHub profile README hero, NO typography or interface. Create a premium cinematic twilight cloudscape from above the clouds, composed for an editorial tech personal introduction. Deep midnight indigo sky at the top blending into saturated cobalt, muted violet and delicate blush peach glow along a low distant horizon at 75 percent height. Soft volumetric cloud banks with realistic delicate silver-lilac edges occupy the bottom quarter and right edge; darker soft clouds hug the far left edge while the left central region remains a smooth calm blue area for white text and the right central region supports a translucent panel added later. Cloud-sea mood elegant, ethereal, airy, with softly glowing distant warm light, restrained cinematic contrast and very subtle film grain. Wide landscape aspect ratio 5:3, no framing. Must be an original composition: no words, no lettering, no logos, no website UI, no ticket, no QR/barcode, no characters, no architecture. Avoid extreme space nebula look, avoid cartoon clouds and busy dense foreground. Leave generous continuous negative space in middle and upper parts.
