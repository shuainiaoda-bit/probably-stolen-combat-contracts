# 深空当铺：战斗委托 / Combat Contracts

作者：是大帅鸟。当前版本：0.4.18。

《深空当铺：可能是偷的 / Probably Stolen》原生C#模组，包含七方悬赏、回合制战斗、装备、成长与店内自卫。

- [GitHub 版本下载](https://github.com/shuainiaoda-bit/probably-stolen-combat-contracts/releases)
- [Steam创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3834364038)
- QQ讨论群：1129395905。欢迎在小黑盒关注「是大帅鸟」。

## 0.4.18

- 已接战斗委托固定在夜间地图第一页。当晚不能出发时，委托卡仍会显示为不可前往。
- 在「设置 → 战斗委托」中，枪械战斗属性可选「始终显示」或「按住 Ctrl 显示」。默认始终显示，设置同时适用于原版物品提示和战斗里的枪械提示。
- 修复战斗随身列表横向错位导致道具卡片被裁切的问题。列表可纵向滚动，战利品列表也使用固定宽度的可视区域。

## 0.4.17 兼容更新

同一份安装包支持默认公开版 Build26525552 和 open_beta Build26772488（1.0.0.16）。已完成两个分支的后台静音实机回归。请在游戏原生 Mod 菜单确认本机授权，并在更新前备份存档。

English: The same package supports public Build26525552 and open_beta Build26772488 (1.0.0.16). Silent native runtime checks passed on both branches. Confirm permissions through the native Mod menu and back up saves before updating.

## 0.4.16更新

新增9件战斗改装配件，总数达到15件。解锁战斗委托并达到80改造体声望后，义体维修师铆钉会来当铺。120、170声望开放更多货品。原来的6件仍可在改造体委托交付时三选一。

## 下载和安装

1. 退出游戏并备份存档。打开要安装的版本对应的 **CombatContracts** ZIP 文件。
2. 解压，将 **CombatContracts** 文件夹放入游戏的 **Mods** 文件夹。更新时替换旧的同名文件夹，保留其他模组。
3. 核对 **Mods/CombatContracts/manifest.xml** 与 **Mods/CombatContracts/CombatContracts.dll** 均存在，文件夹不要重复套一层。
4. 启动游戏，在原生模组菜单启用本模组，按提示确认后完整退出并重启。
5. 在王哥的“服务”中解锁战斗委托，前置为“市场委托”。已有存档可继续使用。

同一个模组只保留一种安装来源。从手动版切换工坊版时，先移出本地 **Mods/CombatContracts** 副本，以免旧文件优先加载。

**SHA256SUMS.txt** 提供安装包校验值。GitHub自动生成的Source code压缩包只包含仓库文档；安装请下载上述zip附件。

兼容声明：**0.46D / 1.0.0.14 / 1.0.0.15**。支持全部11种官方语言。当前beta实机验收为 **Build26711633 / 1.0.0.15**；正式版接口编译通过。

停用前先返店结束战斗、处理待领物资及板甲打印，取出打印芯片，保存退出并备份。新增物品和模组进度随存档保留，重新启用可恢复。

## English

Version 0.4.18 by 是大帅鸟 for Probably Stolen. Accepted contracts appear on the first page of the night map. Combat inventory cards remain aligned in the scroll area. Under Settings → Combat Contracts, choose Always show or Show while holding Ctrl for firearm combat stats. This applies to native item tooltips and in-battle firearm tooltips.

Nine new combat augments bring the total to 15. After unlocking Combat Contracts, reach 80 Augmented reputation to get a visit from Rivet. More stock unlocks at 120 and 170. The six classic augments remain available through Augmented contracts.

1. Exit the game and back up your saves. Open the **CombatContracts** ZIP for the version you want to install. [GitHub releases](https://github.com/shuainiaoda-bit/probably-stolen-combat-contracts/releases)
2. Extract **CombatContracts** into the game's **Mods** folder. Replace the old folder when updating and keep other mods.
3. Check that **Mods/CombatContracts/manifest.xml** and **Mods/CombatContracts/CombatContracts.dll** exist without an extra nested folder.
4. Enable the mod through the native Mod menu, confirm any prompt, then fully exit and restart.
5. Unlock Marketplace Requests, then Combat Contracts in Wang's Services. Existing saves are supported.

Use one installation source for this mod. Remove the local **Mods/CombatContracts** copy when switching to Workshop, so an older manual copy cannot take priority.

**SHA256SUMS.txt** contains the installer checksum. GitHub's automatic Source code archives contain repository documentation; use the zip asset above to install.

Declared game versions: **0.46D / 1.0.0.14 / 1.0.0.15**. Native game tests used **open_beta Build26711633 / 1.0.0.15**; stable-version compilation also passed.

Before disabling, return to the shop, finish combat, collect supplies, resolve armor printing, remove the printing chip, save, exit and back up. Mod items and progress remain in the save and can be restored by re-enabling.
