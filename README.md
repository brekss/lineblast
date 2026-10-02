# 连线封格 · 网页试玩

单人霓虹拼线游戏：拖放线段图形，补齐四边得分并清边。

支持手机触屏与电脑鼠标。三个道具分别为旋转、换形、橡皮擦。

## 发布到 GitHub Pages

这是已构建的独立网页包，无需在线安装 Cocos 或执行编译。

将目录内容上传到仓库 main 分支。仓库 Settings → Pages → Source 选择 GitHub Actions，然后运行 Publish game to GitHub Pages 工作流。

也可以在 Pages 中选择 Deploy from a branch → main → /(root)，无需工作流。

index.html 必须位于发布根目录。所有资源使用相对路径，支持 username.github.io/repository/ 子路径。

本包只含运行网页和发布配置，不含对话资料或 Cocos 编辑器缓存。
