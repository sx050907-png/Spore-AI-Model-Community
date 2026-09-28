# Spore AI模型开放社区

**[查看全部模型图片 → 模型图鉴](docs/模型图鉴.md)**

面向 Spore AI 心智娘与九大灾厄的 YSM 与其他格式模型分享、二次创作与投稿社区，由霜星维护。

本仓库开放模型资源，不包含 SporeAI 主模组或外观附属的 Java 源码、构建工程和源码压缩包。

## 下载与使用

[下载外观附属与心智娘模型包](https://github.com/sx050907-png/Spore-AI-Model-Community/releases)

- 外观附属：`spore_ai_ysm-1.0.0-beta.1.jar`，放入客户端 `mods` 文件夹。内含 10 套心智娘与九灾厄及其状态，共 67 个模型目录。
- 仅心智娘模型：下载 `SporeAI-MindGirl-Models-1.0.0-beta.1.zip`，将其中 10 个模型目录解压到 `config/yes_steve_model/custom/`，避免多套一层目录。
- 需要 Minecraft 1.21.1、NeoForge 21.1.248+、Java 21、SporeAI 2.8.0-beta.1+ 与 YSM **2.6.5-neoforge+mc1.21.1**。主模组的 Spore 等依赖照常需要。
- 首次进入世界等待 YSM 编译、同步后按 F8，选择心智娘模型。未安装 YSM 时 F8 不打开外观界面。
- 附属自动安装模型；同名本地模型存在修改时整套保留。采用新版本前可把对应旧目录移到 `custom` 外备份，勿清空第三方模型。卸载附属不会自动删除已导出的模型。

## 心智娘模型

10 套服装：温柔共生 v1、温柔共生发饰版 v2、春日共生、菌花巡游、暮色守望、绯樱和风、晨光学园、林间旅装、菌伞轻裙、孢子学院裙。

[阅读心智娘服装介绍](docs/心智娘模型介绍.md) · [浏览可编辑模型](models/official)

心智娘模型可在 F8 界面按心智分别选择；可下载独立模型包，也可通过附属自动安装。

## 九大灾厄模型

Sieger（攻城者）、Howitzer、Stahl（蚀刃魔）、Hohlfresser、Gazenbreacher、Kraken、Leviathan、Hindenburg、Verfall（朽翼魔）。

[阅读九大灾厄介绍](docs/灾厄模型介绍.md) · [下载包含灾厄模型的外观附属](https://github.com/sx050907-png/Spore-AI-Model-Community/releases)

九种灾厄连同状态变体共 57 个模型目录，随附属 JAR 提供。各自拥有对应的服装、特征与动作适配，用于灾厄实体，不作为心智娘服装显示在 F8 列表中。

![F8 游戏内界面](docs/F8实机截图.png)

## 投稿

**[YSM 模型投稿](https://github.com/sx050907-png/Spore-AI-Model-Community/issues/new?template=model-submission.yml) · [非 YSM 模型投稿](https://github.com/sx050907-png/Spore-AI-Model-Community/issues/new?template=non-ysm-model.yml)**

Blockbench、Blender、glTF、FBX、OBJ、PMX 等模型也可投稿，详见 [非 YSM 投稿说明](docs/非YSM模型投稿.md)。非 YSM 资源单独审核、分类存放，不能直接放入当前 F8 模型列表。所有投稿禁止违规与侵权内容，须遵守 [统一协议与内容规范](CONTRIBUTING.md)。

欢迎原创心智娘服装、灾厄外观、发饰与孢子主题模型！请先阅读 [投稿协议](CONTRIBUTING.md)。

推荐 Fork 后把模型放入 `models/community/<作者>/<模型ID>/` 并提交 Pull Request。不会使用 Git 的作者可以通过 [模型投稿 Issue](https://github.com/sx050907-png/Spore-AI-Model-Community/issues/new?template=model-submission.yml) 提交文件下载链接、预览和授权信息。投稿经维护者审核后收录，不自动进入附属发行版。

## 作者与许可

当前收录的部分模型改作基于酒狐模型，原酒狐模型，当前角色及服装改作：**霜星**。动画、材质等完整原始贡献记录在每套模型的 `ATTRIBUTION.json` 内，展示作者列表不替代完整署名。

模型采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)：署名、非商业、相同方式共享，并说明修改。遵守原作者与第三方素材授权，不把投稿视作转让著作权。

附属成品保留其内部许可：模型 CC BY-NC-SA 4.0，安装器 MIT。本仓库不发布模组程序源码，也不以仓库开放改变已有许可。详见 [许可范围](LICENSE.md)。

## 验证范围

当前发行候选已有 2468 项自动测试通过记录。实机验证覆盖 F8 可选联动、首次加载 67 个目录和学院裙曲柄动作；未完成多人全流程、全部灾厄战斗与损伤状态及所有动作穿模回归。最新署名与介绍修订仅重新构建打包，未重复实机验收。
