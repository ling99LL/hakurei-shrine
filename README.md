# 博丽神社 · 幻想乡的一隅

暮色中的博丽神社 —— 一座可自由观赏的幻想乡微缩庭院。

基于 **Three.js** 构建的三维静态网页：无需任何构建步骤，打开即用。庭院为体素风格的神社建筑群，包含鸟居、樱花树、回廊与围栏；红白魔法使「灵梦」会不时分神扫地，伊吹萃香则在一旁小酌。支持：

- 🖱️ **自由视角**：拖动旋转、滚轮缩放、右键拖动平移
- 🌙 **昼夜切换**：白昼 / 夜晚 / 昼夜流转三种模式
- 📱 **触屏适配**：单指旋转，双指缩放和平移

## 本地运行

页面使用 ES 模块，请通过任意静态 HTTP 服务器访问（不要直接双击 index.html）：

```bash
cd site
py -m http.server 8642
# 或
python3 -m http.server 8642
```

然后访问 <http://127.0.0.1:8642/>。

## 目录结构

```
site/
├── index.html                          入口页面
└── assets/
    ├── three-OBJEQaXR.js               Three.js 运行库
    ├── main-BHDJnHWD.js                场景主逻辑
    ├── main-B2pDYefJ.css               样式
    ├── reimu/reimu-sweeping-atlas.png  灵梦扫地动画精灵图
    └── suika/suika-drinking-v2-atlas.png 萃香饮酒动画精灵图
```

## 相关链接

- 原始在线版本：<https://hakurei-shrine.netlify.app/>

---

*东方 Project 及其角色版权归上海爱丽丝幻乐团所有，本项目为同人性质的展示页面。*
