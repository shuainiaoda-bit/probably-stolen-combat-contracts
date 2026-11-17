# 深空当铺：战斗委托 / Combat Contracts

作者：是大帅鸟。当前版本：0.4.14。

《深空当铺：可能是偷的 / Probably Stolen》原生C#模组，包含七方悬赏、回合制战斗、装备、成长与店内自卫。

- [下载 0.4.14 安装包](https://github.com/shuainiaoda-bit/probably-stolen-combat-contracts/releases/tag/v0.4.14)
- [Steam创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3834364038)
- QQ讨论群：1129395905。欢迎在小黑盒关注「是大帅鸟」。

## 0.4.14更新

修复远征背包内改装长枪反复读档后逐次移动的问题，保留保存时的位置、朝向和镜像。已经偏移的枪请手动摆回一次，之后读档会保持新位置。委托入口、节点修复和此前功能继续保留。

## 下载和安装

1. 退出游戏并备份存档，在发行页的Assets下载 **CombatContracts-0.4.14.zip**。
2. 解压，将 **CombatContracts** 文件夹放入游戏的 **Mods** 文件夹。更新时替换旧的同名文件夹，保留其他模组。
3. 核对 **Mods/CombatContracts/manifest.xml** 与 **Mods/CombatContracts/CombatContracts.dll** 均存在，文件夹不要重复套一层。
4. 启动游戏，在原生模组菜单启用本模组，按提示确认后完整退出并重启。
5. 在王哥的“服务”中解锁战斗委托，前置为“市场委托”。已有存档可继续使用。

同一个模组只保留一种安装来源。从手动版切换工坊版时，先移出本地 **Mods/CombatContracts** 副本，以免旧文件优先加载。

**SHA256SUMS.txt** 提供安装包校验值。GitHub自动生成的Source code压缩包只包含仓库文档；安装请下载上述zip附件。

兼容声明：**0.46D / 1.0.0.14 / 1.0.0.15**。支持全部11种官方语言。当前beta实机验收为 **Build26711633 / 1.0.0.15**；正式版接口编译及旧读档路径回归通过。

停用前先返店结束战斗、处理待领物资及板甲打印，取出打印芯片，保存退出并备份。新增物品和模组进度随存档保留，重新启用可恢复。

## English

Version 0.4.14 by 是大帅鸟 for Probably Stolen. Includes faction bounties, turn-based combat, equipment, progression and shop defense. All 11 official game languages are supported.

This update fixes fitted long guns shifting inside the expedition backpack after repeated loads. Saved positions, rotation and mirroring are preserved. Reposition any gun moved by an older version once; later loads keep that placement.

1. Exit the game and back up your saves. Download **CombatContracts-0.4.14.zip** from the [release Assets](https://github.com/shuainiaoda-bit/probably-stolen-combat-contracts/releases/tag/v0.4.14).
2. Extract **CombatContracts** into the game's **Mods** folder. Replace the old folder when updating and keep other mods.
3. Check that **Mods/CombatContracts/manifest.xml** and **Mods/CombatContracts/CombatContracts.dll** exist without an extra nested folder.
4. Enable the mod through the native Mod menu, confirm any prompt, then fully exit and restart.
5. Unlock Marketplace Requests, then Combat Contracts in Wang's Services. Existing saves are supported.

Use one installation source for this mod. Remove the local **Mods/CombatContracts** copy when switching to Workshop, so an older manual copy cannot take priority.

**SHA256SUMS.txt** contains the installer checksum. GitHub's automatic Source code archives contain repository documentation; use the zip asset above to install.

Declared game versions: **0.46D / 1.0.0.14 / 1.0.0.15**. Native game tests used **open_beta Build26711633 / 1.0.0.15**; stable-version compilation and legacy load-path regression checks also passed.

Before disabling, return to the shop, finish combat, collect supplies, resolve armor printing, remove the printing chip, save, exit and back up. Mod items and progress remain in the save and can be restored by re-enabling.
