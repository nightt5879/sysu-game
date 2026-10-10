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

背景照片来自[中山大学官网「校园风光」](https://www.sysu.edu.cn/zdkd1/xyfg1.htm)的广州校区南校园图库：[怀士堂照片原图](https://www.sysu.edu.cn/images/22/03/17/1ylx961qyh/hst.jpg)。保存官网原图，页面以 CSS 居中裁切显示。照片版权属于原权利人，来源信息也保存在 [assets/credits.txt](assets/credits.txt)。
