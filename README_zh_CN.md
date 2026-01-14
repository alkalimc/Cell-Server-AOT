# Cell Server AOT

**🌐 语言 / Language**  
[English](README.md) | [中文](README_zh_CN.md)

---

## 📖 概述

**Cell Server AOT** 是一个精心策划的客户端 Minecraft 模组包，专为 Minecraft 1.21.1 设计，使用 Fabric 模组加载器。此模组包专注于通过性能优化、生活质量改进、视觉增强和游戏内容添加来增强原版 Minecraft 体验，同时保持稳定性和兼容性。

模组包包含：
- **72 个模组**，涵盖性能、视觉、实用工具和游戏玩法
- **Plain Craft Launcher 2（PCL2）**，便于安装和管理
- **25+ 个资源包**，用于自定义视觉效果
- **3 个光影包**，用于增强图形效果
- 完整的中文支持，具有自动翻译功能

**设计目标：**
- 优化客户端性能，实现流畅的游戏体验
- 在不牺牲性能的情况下增强视觉质量
- 添加生活质量功能，改善用户体验
- 在保持原版游戏玩法的同时添加实用工具
- 支持单人和多人游戏体验

---

## 🎮 版本兼容性

| 组件 | 版本 |
|------|------|
| **Minecraft** | 1.21.1 |
| **模组加载器** | Fabric Loader 0.18.4 |
| **Java 版本** | Java 21（必需） |
| **启动器** | Plain Craft Launcher 2（已包含） |

---

## 📦 模组列表

模组包包含 72 个按类别组织的模组：

### 性能优化

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| Sodium（钠） | 0.6.13+mc1.21.1 | 核心渲染优化 - 显著提高 FPS |
| Lithium（锂） | 0.15.1+mc1.21.1 | 服务端优化，提高 tick 性能 |
| Krypton（氪） | 0.2.8 | 多人游戏网络堆栈优化 |
| FerriteCore（铁氧体磁芯） | 7.0.2-hotfix | 内存使用优化 |
| ImmediatelyFast | 1.6.9+1.21.1 | 即时模式渲染优化 |
| ModernFix（现代化修复） | 5.25.1+mc1.21.1 | 各种错误修复和性能改进 |
| Enhanced Block Entities（方块实体优化） | 0.10.2+1.21 | 优化方块实体渲染 |
| Entity Culling（实体渲染机制优化） | 1.9.5-mc1.21.1 | 跳过隐藏实体的渲染 |
| More Culling | 1.0.6 | 额外的剔除优化 |
| Alternate Current | 1.9.0 | 红石线优化 |

### 视觉增强

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| Iris Shaders | 1.8.8+mc1.21.1 | 光影支持，兼容 OptiFine 光影 |
| Distant Horizons | 2.4.5-b | 添加远距离地形 LOD 渲染 |
| Continuity | 3.0.0+1.21 | 连接纹理支持 |
| Better Days | 3.3.6.2 | 增强的昼夜循环视觉效果 |
| Presence Footsteps（脚步声） | 1.11.1+1.21 | 基于方块的动态脚步声 |
| Sound Physics Remastered（物理声效重制版） | 1.5.1 | 逼真的声音物理和混响 |
| Physics Mod Pro | v172k | 方块和实体的逼真物理效果 |
| YSM（是，史蒂夫模型） | 2.6.2 | 增强的玩家模型自定义 |
| Do a Barrel Roll | 3.7.3+1.21 | 添加飞行器风格的相机滚动 |

### 用户界面与 HUD

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| Jade（玉 🔍） | 15.10.4 | 高级工具提示系统（WAILA 替代品） |
| AppleSkin（苹果皮） | 3.0.6 | 显示饱和度和疲劳信息 |
| Xaero's Minimap（Xaero 的小地图） | 25.3.5 | 功能丰富的小地图 |
| Xaero's World Map（Xaero 的世界地图） | 1.40.6 | 带路径点的世界地图 |
| BetterF3（更好的 F3） | 11.0.3 | 改进的 F3 调试屏幕 |
| JEI（JEI 物品管理器） | 19.27.0.340 | 配方查看器和物品搜索 |
| Modern UI（现代化 UI） | 3.12.0.2 | 现代化用户界面 |
| Mod Menu（模组菜单） | 11.0.3 | 游戏内模组配置菜单 |
| Reese's Sodium Options（Reese 的钠视频界面） | 1.8.3+mc1.21.4 | 增强的钠选项屏幕 |
| Status Effect Bars | 1.0.6 | 状态效果的可视化条 |
| Chat Animation（聊天动画） | 1.1.3 | 流畅的聊天消息动画 |
| Chat Tools（聊天工具箱） | 2.3.15 | 增强的聊天功能 |

### 生活质量

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| Inventory Profiles Next（一键背包整理 Next） | 2.2.3 | 高级库存管理和整理 |
| InvMove（边拿边走） | 0.9.3+1.21.1 | 在库存界面中移动 |
| Zoomify | 2.14.6+1.21.1 | 流畅的缩放功能 |
| XPlus Contingame IME（游戏内输入法 XPlus 版） | 1.2.1 | 游戏内中文输入法 |
| XPlus Auto Fish（自动钓鱼 XPlus 版） | 1.3.4 | 自动钓鱼 |
| I18nUpdateMod（自动汉化更新） | 3.7.0 | 自动中文翻译更新 |
| JECharacters（通用拼音搜索） | 4.5.23 | 中文拼音搜索支持 |
| Fast IP Ping | 1.0.8 | 更快的服务器列表 ping |
| KeybindFix Plus | 2.0.0 | 修复按键绑定冲突 |

### 游戏玩法添加

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| TaCZ: Refabricated（TaCZ：重织） | 0.4.0 | 战术作战系统，带枪械 |
| Better Combat | 2.3.1+1.21.1 | 增强的战斗机制 |
| Touhou Little Maid（车万女仆：织姬） | 0.5.1 | 可爱的女仆伙伴（东方 Project 主题） |
| Kaleidoscope Doll（森罗物语：玩偶） | 1.0.9 | 装饰性玩偶实体 |
| Kaleidoscope Cookery（森罗物语：厨房） | 1.0.1 | 额外的食物和烹饪 |
| Serene Seasons（静谧四季／季节） | 10.1.0.1 | 四季系统 |
| Serene Seasons Plus | 4.2.2 | 扩展季节功能 |
| Terralith | 2.5.8 | 改进的世界生成 |
| Elytra Slot（鞘翅插槽／鞘翅槽位） | 9.0.1+1.21.1 | 专用鞘翅装备槽 |
| Trinkets | 3.10.0 | 饰品槽系统 |
| Clumps（经验机制改革） | 19.0.0.1 | 合并经验球以提高性能 |

### 库与 API

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| Fabric API | 0.116.7+1.21.1 | 核心 Fabric API |
| Fabric Language Kotlin | 1.13.8+kotlin.2.3.0 | 模组的 Kotlin 支持 |
| Architectury | 13.0.8 | 多平台模组库 |
| Cloth Config | 15.0.140 | 配置屏幕库 |
| Forge Config API Port | 21.1.6 | Fabric 上的 Forge 配置支持 |
| Yet Another Config Lib | 3.8.2+1.21.1 | 现代配置库 |
| Cicada Lib | 0.14.3+1.21 | 共享库 |
| GlitchCore | 2.1.0.0 | 核心库模组 |
| Gabou Libs | 1.4 | 库模组 |
| LibIPN | 6.6.2 | Inventory Profiles Next 库 |
| Player Animation Lib | 2.0.4+1.21.1 | 玩家动画 API |
| Placeholder API（文本占位符 API） | 2.4.2+1.21 | 文本占位符系统 |

### 实用工具与管理

| 模组名称 | 版本 | 描述 |
|----------|------|------|
| Advanced Backups | 3.7.1 | 自动世界备份系统 |
| Spark（火花） | 1.10.109 | 性能分析器 |
| No Chat Reports（禁用聊天举报） | 2.9.1 | 禁用聊天报告 |
| Patchouli（帕秋莉手册） | 92 | 游戏内文档系统 |
| Experimentalist | 2.0.2+1.21.x | 启用实验性功能 |
| Model Fix | 1.6 | 修复各种模型渲染问题 |
| Scalable Lux | 0.1.0.1 | 动态照明优化 |
| CWB（Custom Window Bar） | 3.0.0+mc1.21 | 可自定义的窗口标题栏 |
| Sodium Extra（钠 · 扩展） | 0.6.0+mc1.21.1 | 额外的钠功能 |

---

## 🚀 安装说明

### 前提条件

1. **Java 21**：从 [Oracle](https://www.oracle.com/java/technologies/downloads/#java21) 或 [Adoptium](https://adoptium.net/) 下载并安装
2. 最低 4GB RAM（推荐 8GB+）
3. Windows、macOS 或 Linux 操作系统

### 安装步骤

1. **下载模组包**
   - 克隆或下载此存储库
   - 将所有文件解压到您选择的位置

2. **启动 Plain Craft Launcher 2**
   - 运行 `Plain Craft Launcher 2.exe`（Windows）
   - 对于 macOS/Linux，确保有兼容的 Wine 设置或使用原生启动器

3. **选择模组包**
   - 启动器应自动检测"Bunker Server AOT"实例
   - 位于 `.minecraft/versions/Bunker Server AOT/`

4. **配置 Java 设置**（推荐）
   - 打开启动器设置
   - 将 Java 版本设置为 Java 21
   - 分配 4-8GB RAM（调整 `-Xmx` 参数）
   - 推荐的 JVM 参数：
     ```
     -Xmx6G -Xms4G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
     ```

5. **启动游戏**
   - 在 PCL2 中点击"启动"
   - 等待模组加载（首次启动可能需要更长时间）
   - 尽情享受！

---

## ⚙️ 配置指南

### 关键配置文件

模组包包含预配置的设置，但您可以自定义它们：

#### Sodium 选项 (`config/sodium-options.json`)
- **图形质量**：预设为平衡的质量/性能
- **高级设置**：已启用区块渲染优化

#### Xaero 的小地图和世界地图
- **小地图配置**：`.minecraft/versions/Bunker Server AOT/config/xaero/minimap/`
- **世界地图配置**：`.minecraft/versions/Bunker Server AOT/config/xaero/world-map/`
- 包括雷达类别、路径点和显示设置

#### 聊天工具 (`config/chat_tools.json`)
- 增强的聊天功能配置
- 自定义聊天格式和工具

#### 高级备份 (`config/AdvancedBackups.properties`)
```properties
# 自动备份配置
# 编辑以调整备份频率和保留
```

#### 按键绑定
- 大多数按键绑定使用默认值
- 在游戏中查看**选项 > 控制**以自定义
- KeybindFix Plus 解决常见冲突

### 模组特定设置

通过以下方式访问模组配置：
1. **模组菜单**（游戏内）：主菜单 > 模组
2. **配置文件**：`.minecraft/versions/Bunker Server AOT/config/`

---

## 🎨 资源包和光影

### 包含的资源包（25+）

模组包包含精心挑选的资源包，可增强纹理和模型：

- **零雾构想** v5003 - 增强的雾效果
- **05RD（05 红显）** - 红石视觉改进
- **完美玻璃模型** - 改进的玻璃纹理
- **无缝玻璃**（100%、75%、常规） - 连接的玻璃纹理
- **完美草方块侧面** - 增强的草方块纹理
- **3D 模型** - 门、工作台和常规方块
- **连接纹理** - 自然和木板
- **矿物描边** - 连接的矿石纹理
- **树叶模型** - 带衰变状态的繁茂树叶模型
- **流体方向显示** - 可视化流动指示器
- **音符盒信息显示** - 显示音符盒信息
- 以及更多视觉增强！

### 光影包（3）

- **Helian MMCO** v0.4.7c - Sundial-lite Edit
- **Sundial Core Dev Packup**（2025-12-02）
- **iterationRP Alpha** 0.8.9

激活光影：
1. 按 **Esc** > **选项** > **视频设置** > **光影包**
2. 从列表中选择一个光影
3. 点击**完成**

---

## 🎯 游戏玩法特性

### 性能

- **优化渲染**：Sodium + Lithium 提供 3-5 倍 FPS 提升
- **远距离 LOD**：使用 Distant Horizons 查看最多 512 个区块的地形
- **智能剔除**：实体和方块剔除减少渲染负载
- **内存优化**：FerriteCore 显著减少 RAM 使用

### 视觉增强

- **逼真物理**：方块和实体对物理做出反应
- **声音沉浸**：逼真的脚步声和声音物理
- **光影支持**：通过 Iris 兼容 OptiFine 光影
- **连接纹理**：无缝玻璃、矿物描边等
- **季节变化**：动态季节影响视觉和游戏玩法

### 生活质量

- **库存管理**：一键整理和组织
- **配方查看**：JEI 提供即时配方查找
- **小地图导航**：路径点、雷达和世界地图
- **游戏内输入法**：无需离开游戏即可输入中文
- **缩放功能**：流畅缩放以提高可见性
- **在库存中移动**：管理物品时行走

### 游戏玩法添加

- **战术作战**：TaCZ 添加逼真的火器
- **女仆伙伴**：东方 Little Maid 提供有用的 NPC
- **增强战斗**：Better Combat 改进近战战斗
- **食物多样性**：Kaleidoscope Cookery 添加新配方
- **世界生成**：Terralith 生物群系供探索
- **季节系统**：四季具有独特的机制

---

## 💡 提示和建议

### 性能提示

1. **调整渲染距离**：从 12-16 个区块开始，如果性能允许则增加
2. **启用垂直同步**：防止画面撕裂，限制 FPS
3. **监控 FPS**：使用 Shift+F3 查看性能指标
4. **光影性能**：某些光影比其他光影更耗资源
5. **Distant Horizons LOD**：在视频设置 > Distant Horizons 中调整质量

### 游戏玩法提示

1. **阅读 Patchouli 书籍**：复杂模组的游戏内指南
2. **使用路径点**：对于大型世界导航至关重要
3. **定期备份**：Advanced Backups 自动运行，但建议手动备份
4. **JEI 搜索**：悬停在物品上时按"R"（配方）或"U"（用途）
5. **季节意识**：不同季节作物生长不同

### 多人游戏

- 兼容原版 1.21.1 服务器
- 某些仅客户端模组不会影响服务器游戏
- 加入模组服务器时禁用不兼容的模组

### 故障排除

**低 FPS：**
- 减少渲染距离
- 禁用光影
- 降低 Distant Horizons 质量
- 分配更多 RAM

**启动时崩溃：**
- 验证已安装 Java 21
- 检查 RAM 分配（最低 4GB）
- 查看 `.minecraft/logs/` 中的崩溃日志

**缺少纹理：**
- 确保资源包顺序正确
- 某些资源包可能冲突 - 尝试禁用一些

**模组冲突：**
- 检查 `latest.log` 中的错误消息
- 逐个禁用可疑模组

---

## 📂 存储库结构

```
Cell-Server-AOT/
├── .minecraft/
│   ├── versions/
│   │   └── Bunker Server AOT/
│   │       ├── mods/              # 72 个模组文件
│   │       ├── config/            # 配置文件
│   │       ├── resourcepacks/     # 25+ 个资源包
│   │       ├── shaderpacks/       # 3 个光影包
│   │       └── Bunker Server AOT.json  # 版本清单
│   └── PCL.ini                    # PCL 配置
├── PCL/                           # 启动器文件
│   └── Setup.ini
├── Plain Craft Launcher 2.exe     # 启动器可执行文件
├── README.md                      # 英文文档
├── README_zh_CN.md                # 此文件（中文）
└── LICENSE                        # 许可证文件
```

---

## 📝 许可证

此模组包根据 [LICENSE](LICENSE) 文件中指定的条款分发。各个模组有自己的许可证 - 请尊重每个模组作者的条款。

---

## 🙏 致谢

此模组包整合了许多才华横溢的模组开发者的工作。特别感谢：

- 所有模组作者的出色工作
- Fabric 团队的模组加载器
- Plain Craft Launcher 2 开发者
- 资源包和光影包创作者
- Minecraft 模组社区

---

## 📞 支持与联系

- **问题**：报告特定于此模组包配置的问题
- **模组错误**：向各个模组作者报告
- **更新**：检查存储库以获取更新和更改日志

---

**尽情享受 Cell Server AOT 带来的增强 Minecraft 体验！** 🎮✨
