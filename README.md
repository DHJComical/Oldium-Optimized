# 基于1.12.2与Relictium的整合包

## 开发动机

### 专为移动端FCL启动器设计，解决移动端旧版OptiFine效率低下的问题：
- **性能痛点**：
  - 常规地图平均70 FPS（2区块渲染距离）  
  - 空岛地图约100 FPS

---

## 核心架构

### 核心模组


-  Relictium - Sodium的1.12.2移植版
-  BetterFPS - 更好的FPS
-  Alfheim Lighting Engine - 光照改进
-  Universal Tweaks - 通用修改
### 视觉增强(如造成卡顿可关闭)
-  NeverEnoughAnimation - 增强物品动画系统
-  Aqua Acrobatics - 现代版游泳机制
-  Blur - 界面背景模糊效果
-  Modern Splash - 高版本加载界面 桌面端独占
-  Smooth Font - 平滑字体

---

## 性能测试（12区块渲染 | 最高画质）

| 硬件配置                   | 峰值FPS（天空视角） | 最低FPS（区块加载） |
|---------------------------|--------------------|---------------------|
| E5-2666v3 + GTX 1660S @ 1080p | 870               | 500                 |
| 天玑9200+（红米K60至尊版）   | 500               | 110                 |
| E5-2666v3 + GTX 1660S @ 1080p + Opt | 1300           | 500            |
| 天玑9200+（红米K60至尊版）+ Opt   | 130               |60                     |


## 兼容性指南

### ✔️ Windows
- 完整支持

### 📱 Android
- **必须渲染器**：
  - Holy Renderer（推荐方案）
  - ⚠️ 关键设置：禁用游戏设置中的紧凑定点格式模组
  - Krypton Wrapper Renderer（实验性，存在已知问题）
- ⚠️ 关键设置：禁用_Smooth Font_模组

---

## 光影支持现状
**❌Oculus 1.12.2移植版**：
- 开发停滞（最后一次提交于10个月前）
- GitHub Actions构建连续3次失败
- 当前版本不支持光影

---

## 许可协议与贡献
本整合包采用 **MIT 协议**，您可以：
-  创建衍生整合包
-  二次分发（需保留署名）
-  问题反馈渠道：
  - 评论区留言
  - [DHJComical@gmail.com](mailto:DHJComical@gmail.com)

