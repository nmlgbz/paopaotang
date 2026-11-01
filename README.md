# Q版泡泡堂（Bomb It）触屏版

用 [Ruffle](https://ruffle.rs) 在浏览器里运行原版 Flash 游戏 `game.swf`，加上触屏十字键和放泡泡按钮，iPhone / iPad / 安卓都能玩。

- 打开 `index.html` 所在的网址即可游玩（需要通过 http/https 访问，直接双击本地文件打不开）。
- iPhone：Safari 分享 → 添加到主屏幕，可全屏游玩；第一次加载后会缓存，之后离线也能打开。
- 单人：左下角摇杆 = 方向键，右下角红色按钮 = 空格。
- 双人同屏：左边摇杆和按钮给 P1（WASD + 空格），右边给 P2（方向键 + 回车）。
- 左上角菜单：切换单人/双人、调按键大小和透明度、拖动按键位置。

## 部署到 GitHub Pages

把本文件夹里的所有文件上传到一个公开仓库的根目录，然后在仓库 Settings → Pages 里选择 `main` 分支、`/ (root)`，保存后等一两分钟即可。

## 版权

- 游戏 Bomb It © Agame。
- Ruffle 以 MIT / Apache-2.0 双许可证发布，见 `ruffle/LICENSE_*.txt`。
