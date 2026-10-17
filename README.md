<div align="center">

#  DawnAurora Player Animation

**Dapa** · Minecraft 1.20.1 · Fabric · Alpha Early Preview

!<Version>
!<MC>
!<Fabric>
!<ETF+EMF>
!<License>

> Making first-person feel **ALIVE** again. 
> 让第一人称**活过来**。

</div>

---

##  Quick Start / 30秒上手

<details>
<summary><b> Installation / 安装步骤（点击展开）</b></summary>

1. 安装 **Fabric Loader** for Minecraft 1.20.1
2. 安装依赖模组：**ETF** + **EMF**（必须装！没装动画不跑！）
3. 下载最新 `.zip` 资源包
4. 扔进 `.minecraft/resourcepacks/`
5. 游戏内 **选项 → 资源包 → 启用 DawnAurora**
6. **完全重启游戏**（不是 F3+T 刷新！）

</details>

---

##  What's Done / 已完成

> This pack completely overhauls vanilla Minecraft player animations.  
> 本资源包彻底重做原版玩家动画，动作更丝滑、更自然、细节拉满。

###  Core Locomotion / 核心移动

| Feature | Status | Description |
|:---|:---:|:---|
| Idle 待机呼吸 |  | 不再僵硬站桩，有自然呼吸起伏 |
| Walk 慢走 |  | 步伐自然，不再"滑步" |
| Run 跑步 |  | 身体前倾感，手臂摆动加大 |
| Sprint 冲刺 |  | 冲刺姿态，速度感拉满 |
| Backward 后退走/跑 |  | 不再"倒着滑" |
| Strafe 侧移 |  | 走/跑/潜行侧移，身体倾斜 |
| Sneak 潜行 |  | 身体压低，脚步放轻 |
| Crawl 爬行 |  | 全身贴地爬行 |
| Climb 攀爬 |  | 梯子/脚手架，手脚协调 |
| Ladder Lock 爬梯锁定 |  | 爬梯时锁定朝向不乱转 |

###  Water & Air / 水空动作

| Feature | Status | Description |
|:---|:---:|:---|
| Swim 游泳 |  | 四肢划水动作 |
| Upward Swim 上游 |  | 身体上仰向上游 |
| Water Tread 踩水 |  | 浅水踩水，头露水面 |
| Wade 涉水 |  | 浅水/熔岩行走，腿部阻力感 |
| Jump 起跳 |  | 腿部蹬地蓄力 |
| Fall 下落 |  | 身体蜷缩，手臂上举 |
| Land 着陆 |  | 膝盖弯曲缓冲冲击 |
| Elytra Glide 鞘翅滑翔 |  | 身体平展滑翔 |
| Elytra Dive 鞘翅俯冲 |  | 身体前倾加速俯冲 |

### ️ Interaction & Combat / 交互战斗

| Feature | Status | Description |
|:---|:---:|:---|
| Attack 攻击 |  | 挥砍动作 |
| Interaction 交互 |  | 开门/放置等右键动作 |
| Mount 骑乘 |  | 马/驴/骡/猪等骑乘姿态 |
| Sleep 睡觉 |  | 躺下放松姿态 |
| Equip Transition 切换过渡 |  | 切物品平滑过渡不瞬移 |
| Torch Hold 火把持握 |  | 竖立持握，不再躺平 |
| Lantern Hold 灯笼持握 |  | 高举弹跳，清晰可见 |

###  Visual / 视觉效果

| Feature | Status | Description |
|:---|:---:|:---|
| Tight Armor 紧身盔甲 |  | 不再臃肿 |
| Body Lean 身体倾斜 |  | 移动时倾斜更有动感 |
| Cape 披风 |  | 物理模拟飘动 |
| Head Yaw/Pitch 头部转向 |  | 独立动画 |
| First-Person Hand 第一人称手部 |  | 持物有姿态 |

---

##  Work In Progress / 开发中

### 🪣 Bucket Family — 水桶家族（11 items）

> 目标：3D 桶身 + 液体晃动/生物探头 + **强烈弹跳反馈**（参考基岩版 *Access and Stuff*）

| Item | ID | Animation Plan | Progress |
|:---|:---|:---|:---:|
| 空桶 | `bucket` | 3D 铁桶 + 手持弹跳 |  |
| 水桶 | `water_bucket` | 桶身 + 水面晃动 + 倒水甩动 |  |
| 熔岩桶 | `lava_bucket` | 桶身 + 熔岩发光 + 滴落感 |  |
| 牛奶桶 | `milk_bucket` | 白色液体面晃动 |  |
| 细雪桶 | `powder_snow_bucket` | 霜冻质感 + 雪花飘落 ️ |  |
| 鳕鱼桶 | `cod_bucket` | 小鱼探头 + 尾巴轻摆 |  |
| 鲑鱼桶 | `salmon_bucket` | 鱼身左右摆尾 |  |
| 热带鱼桶 | `tropical_fish_bucket` | 彩色鱼夸张摆动 |  |
| 河豚桶 | `pufferfish_bucket` | **鼓胀/收缩呼吸**  |  |
| 美西螈桶 | `axolotl_bucket` | 探头 + 眨眼 + 腮动 + 尾巴摆 |  |
| 蝌蚪桶 | `tadpole_bucket` | 小尾巴高频摆动 |  |

### ️ Weapon Family — 武器家族（7 items）

> 目标：攻击挥砍惯性 + 蓄力后仰 + 命中震动反馈

| Item | ID | Animation Plan | Progress |
|:---|:---|:---|:---:|
| 剑 | `sword` | 挥砍惯性 + 命中短震 ️ |  |
| 斧 | `axe` | 重劈反馈，蓄力明显 🪓 |  |
| 镐 | `pickaxe` | 挖掘蓄力 + 下砸 ️ |  |
| 弓 | `bow` | 拉弓蓄力后仰 + 释放回弹  |  |
| 弩 | `crossbow` | 装填上弦 + 发射后坐力 |  |
| 铲 | `shovel` | 挖掘铲起动作 🪏 |  |
| 锄 | `hoe` | ...是的连锄头都有 |  |

###  Planned / 计划中

- [ ] Custom shield blocking animation — 盾牌格挡（举盾手臂前推）
- [ ] Equipment & hotbar swap animation — 装备/快捷栏切换动画
- [ ] Armor state animations — 不同盔甲材质状态反馈
- [ ] Player hurt / damage animation — 受伤受击反馈（后仰 + 红闪）
- [ ] Respackopts configuration support — 可选配置项支持

---

## ️ Important Warnings / 重要提示

>  **This is a RESOURCE PACK, NOT a mod.**
> 这是资源包，不是模组！不要扔进 `mods` 文件夹！

>  **ETF + EMF are MANDATORY.**
> ETF 和 EMF **必须安装**，否则动画全部不加载！

>  **Alpha = unstable.**
> 早期测试版，可能有动画 glitch、帧跳变、模型穿模等问题。欢迎反馈，请保持耐心～

> ️ **Client-side only.**
> 纯客户端生效，单人/多人服务器都能用，无需服务器安装。

---

## ️ Tech Stack / 技术栈

- **Animation Framework:** ETF + EMF (Fabric)
- **Item Display:** `parent` + `display` override
- **3D Models:** Blockbench → `.emf.json` entity models
- **Animation System:** EMF `timeline` keyframes
- **First-Person:** `player_firstperson.json` arm pose control
- **Format:** Single-line JSON — copy, paste, F3+T, done 

---

##  Contributors / 贡献者

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/你的GitHub用户名.png" width="100px;" alt=""/><br />
      <sub><b>你的名字</b></sub><br />
      <a href="https://github.com/你的GitHub用户名" title="Code"></a>
      <a href="#design-你的名字" title="Design"></a>
      <a href="#ideas-你的名字" title="Ideas & Planning"></a>
    </td>
  </tr>
</table>

> One-person army. All code, all art, all dreams. 
> 一人成军。代码、美术、梦想，全包。

---

##  License / 许可证

**CC-BY-NC-SA 4.0**

-  Personal use, study, modification — 个人使用/学习/修改随意
-  Public distribution with credit — 公开发布请保留原作者署名
-  Commercial use — 禁止商业用途

---

<div align="center">

**Made with  by DawnAurora Team**

*Making Minecraft first-person feel alive again.*

</div>
