# 合成中山大学

[开始游戏](https://nightt5879.github.io/sysu-game/)

复刻自 [plianasp-maker/scut-game](https://github.com/plianasp-maker/scut-game)，保留原版界面、物理碰撞、得分、音效、重开和手机倾斜操作。

左右拖动、松手落下，两个相同的校徽相碰后升级。升级顺序：

华南理工大学 → 同济大学 → 西安交通大学 → 哈尔滨工业大学 → 武汉大学 → 南京大学 → 复旦大学 → 上海交通大学 → 浙江大学 → 北京大学 → 清华大学 → 中山大学。

## 自定义顺序

点击右上角齿轮打开设置，拖动校徽或使用上下箭头排列 12 所学校。顺序从最小到最大，原版的 12 档球体大小和物理规则保持不变。拖动按钮也支持键盘上下方向键。

保存新顺序后重新开局，并在当前浏览器记住设置；未修改顺序直接保存或取消设置会继续本局。「恢复默认」仅调整设置中的草稿，点击保存后才会生效。最大等级的校徽、游戏标题和合成成功文案会随顺序变化。

中山大学必须排在华南理工大学之后。若保存的草稿不满足这一规则，会显示数据弹窗，拒绝整次修改并恢复上一次成功保存的完整顺序；本局进度也会保留。

弹窗数据采用榜单机构的学校档案：软科 2026 年中国大学排名、世界大学学术排名和世界一流学科排名上榜数量（[中大](https://www.shanghairanking.com/universities/sun-yat-sen-university)、[华工](https://www.shanghairanking.com/universities/south-china-university-of-technology)）；QS 2027 年世界大学排名（[中大](https://www.topuniversities.com/universities/sun-yat-sen-university)、[华工](https://www.topuniversities.com/universities/south-china-university-technology)）。年份、并列名次及排名区间按原始页面标注。

## 运行和部署

纯静态 HTML / JavaScript，无需安装依赖或构建。可在本目录运行 `python -m http.server 8080` 后访问 `http://localhost:8080`。

GitHub Pages 从 `main` 分支根目录发布，更新文件并推送到 `main` 后自动重新部署。

## 素材来源

校徽素材沿用原仓库。

背景照片来自[中山大学官网「校园风光」](https://www.sysu.edu.cn/zdkd1/xyfg1.htm)的广州校区南校园图库：[怀士堂照片原图](https://www.sysu.edu.cn/images/22/03/17/1ylx961qyh/hst.jpg)。保存官网原图，页面以 CSS 居中裁切显示。照片版权属于原权利人，来源信息也保存在 [assets/credits.txt](assets/credits.txt)。
