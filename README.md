# Z-Anatomy 简体中文支持版

本仓库是基于 [Z-Anatomy 原项目](https://github.com/Z-Anatomy/Models-of-human-anatomy/blob/master/Z-Anatomy.zip) 的修改版本，  
在保留原项目所有内容的基础上，**增加了简体中文语言支持**。

## 与原项目的区别
- 原项目中的标签支持 5 种语言（英语；拉丁语；法语；西班牙语；葡萄牙语）。本版本为标签显示新增了简体中文支持，现共支持 6 种语言。
- 在原项目中'z-anatomy.py'文件中，添加了 Noto Sans CJK SC 作为中文字体，但由于没有字体文件也可显示中文，出于轻量化考虑，**并没有添加相应的字体文件**。
- 原项目中'z-anatomy.py'文件中第1514行所用的blf.size()函数与最新版本的blender不匹配，已修改。
- 将原项目中的“中國人”改为“中文”。



## 许可证
本项目采用与原始项目相同的 **Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)** 许可证。  
详见仓库中的 [License.txt](./License.txt) 文件。

## 署名

### 原项目作者（完整名单见 License.txt）
- Kousaku OKUBO (Original model ‘BodyParts3D’)
- Gauthier KERVYN (Design, 3D, anatomy)
- Marcin ZIELIŃSKI (Blender add-on)
- Lluis VINENT (Unity development)
- Ana Teresa BIGIO (Portuguese translation)
- Carlos TORRES VILLAR (Spanish translation)
- Paola Perin, Daniele Cossellu, Elisa Vivado (Italian translation)
- Jadwiga Palosz (Polish translation)
- Shariar Ahmadpour (Parsi translation)

### 本修改版的贡献者
- **Dean Song** – 简体中文翻译及语言支持集成

## 说明
- 中文标签显示对应词典自动化生成，可能有部分与指示部位不恰当，可供参考，但具体请以权威版本为准。
- 本修改版遵循 CC BY-SA 4.0 许可证，再分发或修改时请保留此许可证并注明出处。
- 原项目中部分模型使用了不同版本的 CC 许可证（如 CC BY-SA 2.1 JP、CC BY-NC-SA 4.0 等），详情请参阅 [License.txt](./License.txt) 中的 ATTRIBUTIONS 部分。