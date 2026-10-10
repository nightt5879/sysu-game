# 合成中山大学

[开始游戏](https://nightt5879.github.io/sysu-game/)

复刻自 [plianasp-maker/scut-game](https://github.com/plianasp-maker/scut-game)，保留原版界面、物理碰撞、得分、音效、重开和手机倾斜操作。

左右拖动、松手落下，两个相同的校徽相碰后升级。升级顺序：

华南理工大学 → 同济大学 → 西安交通大学 → 哈尔滨工业大学 → 武汉大学 → 南京大学 → 复旦大学 → 上海交通大学 → 浙江大学 → 北京大学 → 清华大学 → 中山大学。

## 运行和部署

纯静态 HTML / JavaScript，无需安装依赖或构建。可在本目录运行 `python -m http.server 8080` 后访问 `http://localhost:8080`。

GitHub Pages 从 `main` 分支根目录发布，更新文件并推送到 `main` 后自动重新部署。

## 素材来源

校徽素材沿用原仓库。

背景照片：[Swasey Hall of Lingnan University 03 2016-05.jpg](https://commons.wikimedia.org/wiki/File:Swasey_Hall_of_Lingnan_University_03_2016-05.jpg)，作者：猫猫的日记本，许可：[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。本项目使用 Wikimedia 提供的 1280 像素版本，页面以 CSS 居中裁切显示；照片及其缩放版本继续遵循 CC BY-SA 4.0。来源信息也保存在 [assets/credits.txt](assets/credits.txt)。
