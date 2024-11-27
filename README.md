# Minecraft-Panorama

`Three.js` 实现 Minecraft 主菜单背景中显示的缓慢转动的广角视图。

[点击查看效果](https://wcze.github.io/minecraft-panorama/index.html)



> **全景图（Panorama）**，官方称之为**立方体贴图（Cubemap）**，是一幅在主菜单背景中显示的缓慢转动的真实游戏世界（广角视图）。



------




### 更换图片：

- 替换 `/background` 目录下的**panorama图片**。

```javascript
const image_src = [
	'./background/panorama_0.png',
	'./background/panorama_1.png',
	'./background/panorama_2.png',
	'./background/panorama_3.png',
	'./background/panorama_4.png',
	'./background/panorama_5.png',
];
```



- *图片加载顺序如图所示：*
![image](https://github.com/user-attachments/assets/7825b428-4069-4d74-9972-1be8b18f67eb)



- 图片可在`.minecraft\resourcepacks\assets\minecraft\textures\gui\title\background`中获取。

- 或在[Panorama - Minecraft Wiki](https://minecraft.wiki/w/Panorama)中下载图片获取。