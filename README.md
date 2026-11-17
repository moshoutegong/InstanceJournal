# Instance Journal（副本手册）

Instance Journal 参考《魔兽世界》原版副本手册重新制作，专为 OctoWoW 打造。默认按 `Shift+J` 打开，也可以在游戏的按键设置中更改快捷键。

## 功能

- 列出所有地下城和团队副本，包括 OctoWoW 的自定义内容。
- 提供各首领的技能和掉落信息。
- 显示副本中可接取的所有任务及其前置任务要求。
- 支持在聊天中发送技能、掉落物品和任务链接。
- 可通过搜索栏快速查找物品、技能、副本或首领。
- 在世界地图上标出副本入口和首领位置；点击首领标记即可打开手册中的对应条目。
- 改善世界地图的使用体验。
- 支持美式英语（`enUS`）、德语（`deDE`）、西班牙语（`esES`）、法语（`frFR`）、巴西葡萄牙语（`ptBR`）、俄语（`ruRU`）和简体中文（`zhCN`）。

## 截图

<img width="600" height="377" alt="地下城标签页" src="https://github.com/user-attachments/assets/8c700a6a-1de1-49e5-939b-b4fe5ef273c5" />
<img width="634" height="377" alt="副本掉落标签页" src="https://github.com/user-attachments/assets/d5e0e90c-fbed-486e-8c01-61c7348d57d9" />
<img width="634" height="377" alt="技能标签页" src="https://github.com/user-attachments/assets/b7f77a3b-968e-4111-b4a5-21ac4c3dc372" />
<img width="634" height="377" alt="任务标签页" src="https://github.com/user-attachments/assets/de3d5d07-4121-4a2c-857d-b75b53785303" />

<details>
<summary>查看更多截图</summary>

<img width="600" height="377" alt="团队副本标签页" src="https://github.com/user-attachments/assets/599b9c3c-0e1b-4d2e-8a74-fe181807287c" />
<img width="634" height="377" alt="副本概览标签页" src="https://github.com/user-attachments/assets/3a93d1ae-e3e0-4a82-aef3-65ede2f05c36" />
<img width="634" height="377" alt="首领掉落标签页" src="https://github.com/user-attachments/assets/2c98e513-3f14-4b68-9e99-22aa4623d832" />
<img width="600" height="377" alt="搜索结果" src="https://github.com/user-attachments/assets/664671fa-a119-4e12-b105-8ef53261bc71" />
<img width="600" height="427" alt="世界地图上的副本入口" src="https://github.com/user-attachments/assets/37b067da-007a-4089-925c-660ad615ce78" />
<img width="600" height="427" alt="副本地图上的首领位置" src="https://github.com/user-attachments/assets/713da654-6fbd-4c79-a401-b593112ea7e1" />

</details>

## 安装

### 通过 Octo WoW 启动器安装（推荐）

1. 打开 Octo WoW 启动器，切换到顶部的 `ADDONS`（插件）标签页。
2. 点击 `Add new addon`（添加新插件），在输入框中粘贴：`https://github.com/Arthur-Helias/InstanceJournal.git`。
3. 在角色选择界面打开插件菜单，启用副本手册。

### 手动安装

1. 下载插件的[最新版本](https://github.com/Arthur-Helias/InstanceJournal/archive/refs/heads/master.zip)。
2. 解压下载的压缩包。
3. 将解压得到的 `InstanceJournal-master` 文件夹重命名为 `InstanceJournal`。
4. 把重命名后的文件夹复制到游戏目录下的 `Interface\AddOns` 中。
5. 在角色选择界面打开插件菜单，启用副本手册。

## 兼容性

本插件为 Octo WoW 开发，并在该环境中测试过。它与以下插件不兼容：

- Cartographer

如果遇到其他兼容性问题，欢迎到本仓库的 `Issues`（议题）页反馈。

## 扩展功能

与以下第三方模组搭配使用时，副本手册的部分功能会得到增强：

| 模组 | 最低版本 | 增强功能 |
| :--- | :---: | :--- |
| [Nampower](https://gitea.com/Drakensangs/nampower) | 4.6.0 | 通过任务 ID 识别任务，让任务追踪更准确、更可靠。 |

如果未安装相应模组，或安装的版本低于最低要求，插件会自动沿用原有功能。

## 已知问题

- 受游戏引擎限制，部分副本地图无法显示完整区域，例如黑石塔下层／上层（LBRS／UBRS）和通灵学院。
- 部分背景故事可能不准确或不完整。
- 大多数首领的技能资料尚未补全，部分细节可能有误。

遇到问题时，请到本仓库的 `Issues`（议题）页反馈。

## 开发计划

- 补全所有首领战的技能资料。
- 让世界地图上的首领标记显示该首领是否已被击败。
- 开发配套插件，提供自定义选项、小地图按钮和聊天命令等功能。

## 参与贡献

副本手册收录了大量数据，欢迎帮忙核对和完善。如果发现以下问题，可以创建 Issue（议题）或提交 Pull Request（合并请求）：

- 背景故事有误，例如首领介绍或副本背景摘要不准确。
- 首领技能缺失、过时或有误。
- 掉落资料有误，例如漏掉物品、标错掉落首领、装备部位或类型。
- 任务资料有误，例如漏掉任务、奖励不正确、缺少任务要求、任务接取或交付地点有误，或阵营、技能、职业筛选不正确。

小的修正也很有帮助。如果不确定如何修改，提交 Issue 并说明具体问题即可。

## 推荐搭配的插件

以下插件可与副本手册搭配使用：

- [Magnify](https://github.com/lookino/Magnify)：为世界地图添加缩放功能。
- [ModernMapMarkers](https://github.com/tilare/ModernMapMarkers)：在世界地图上标出副本、世界首领和交通点。
- [ZonesLevel](https://github.com/Arthur-Helias/ZonesLevel)：在世界地图上显示各区域的等级范围。
- [Better Character Panel](https://github.com/Arthur-Helias/BetterCharacterPanel)：改进角色面板和观察面板。

## 实现与素材来源

本插件参考游戏截图和实际游戏体验从零实现，未使用暴雪原版副本手册的代码。部分界面素材沿用了暴雪原版手册中的元素。

## 致谢

- [Walter Bennet](https://github.com/Arthur-Helias)：创建插件。
- [暴雪](https://www.blizzard.com)：原版副本手册与界面素材。
- [Speedz](https://forum.turtlecraft.gg/viewtopic.php?t=14904)：协助制作首领美术素材。
- [cat-nep](https://github.com/cat-nep)：协助编写技能说明。
- [thetimel3ss](https://github.com/thetimel3ss)：整理首领技能，更新和清理 OctoWoW 数据。
- [byCFM2](https://github.com/byCFM2)：AtlasTW 数据。
- [tilare](https://github.com/tilare)
- Aeliren：协助核对首领背景故事。

## 许可证

本项目的代码依据 [Unlicense](LICENSE) 贡献至公有领域。无论是否署名，你都可以出于任何目的复制、修改和分发这些代码。

插件使用的部分界面素材属于[暴雪娱乐](https://www.blizzard.com)的知识产权，收录时未取得其明确授权。这些素材**不适用** Unlicense，仍受暴雪娱乐的版权保护。本项目是玩家制作的非商业插件，与暴雪娱乐及 OctoWoW 无关联，也未获两者背书。
