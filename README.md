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

<details>
<summary><b> Troubleshooting / 常见问题（点击展开）</b></summary>

- **动画不生效？** → 确认 ETF + EMF 已安装且版本匹配，然后完全重启游戏
- **模型穿模/错位？** → Alpha 版已知问题，请反馈具体动作场景
- **帧率下降？** → 尝试关闭其他高清资源包，本包本身性能开销较低
- **多人服务器能用吗？** → 纯客户端资源包，服务器无需安装

</details>

---

##  What's Done / 已完成

> This pack completely overhauls vanilla Minecraft player animations.  
> 本资源包彻底重做原版玩家动画，动作更丝滑、更自然、细节拉满。

###  Core Locomotion / 核心移动

| Feature | Status | Description |
|:---|:---:|:---|
| Idle 待机呼吸 |  | 不再僵硬站桩，有自然呼吸起伏，胸腔微幅扩张收缩 |
| Walk 慢走 |  | 步伐自然，手臂摆动协调，不再"滑步" |
| Run 跑步 |  | 身体前倾感明显，手臂摆动幅度加大，脚步有力 |
| Sprint 冲刺 |  | 冲刺姿态压低重心，速度感拉满 |
| Backward 后退走/跑 |  | 不再"倒着滑"，有真实后退步伐 |
| Strafe 侧移 |  | 走/跑/潜行侧移时身体自然倾斜 |
| Sneak 潜行 |  | 身体压低，脚步放轻，头部微收 |
| Crawl 爬行 |  | 全身贴地爬行，四肢协调摆动 |
| Climb 攀爬 |  | 梯子/脚手架攀爬时手脚协调交替 |
| Ladder Lock 爬梯锁定 |  | 爬梯时锁定朝向，转身不会乱转 |

###  Water & Air / 水空动作

| Feature | Status | Description |
|:---|:---:|:---|
| Swim 游泳 |  | 四肢划水动作，手臂交替前伸 |
| Upward Swim 上游 |  | 身体上仰，双腿蹬水向上游 |
| Water Tread 踩水 |  | 浅水踩水姿态，头部保持露出水面 |
| Wade 涉水 |  | 浅水/熔岩行走时腿部有阻力感，步伐变慢 |
| Jump 起跳 |  | 腿部蹬地蓄力，身体向上弹起 |
| Fall 下落 |  | 身体蜷缩，手臂自然上举保持平衡 |
| Land 着陆 |  | 膝盖弯曲缓冲冲击，身体微蹲后恢复 |
| Elytra Glide 鞘翅滑翔 |  | 身体平展，披风与身体同步滑翔 |
| Elytra Dive 鞘翅俯冲 |  | 身体前倾加速俯冲，速度感强烈 |

### ️ Interaction & Combat / 交互战斗

| Feature | Status | Description |
|:---|:---:|:---|
| Attack 攻击 |  | 挥砍动作有惯性，手臂带动武器弧线运动 |
| Interaction 交互 |  | 开门/放置/右键等交互动作自然流畅 |
| Mount 骑乘 |  | 马/驴/骡/猪等骑乘时身体随坐骑起伏 |
| Sleep 睡觉 |  | 躺下放松姿态，呼吸平缓 |
| Equip Transition 切换过渡 |  | 切换物品时平滑过渡，不再瞬移跳变 |
| Torch Hold 火把持握 |  | 竖立持握，不再躺平，火光方向正确 |
| Lantern Hold 灯笼持握 |  | 高举灯笼，行走时有轻微弹跳反馈 |

###  Visual / 视觉效果

| Feature | Status | Description |
|:---|:---:|:---|
| Tight Armor 紧身盔甲 |  | 盔甲贴合身体，不再臃肿方块感 |
| Body Lean 身体倾斜 |  | 移动时身体自然倾斜，更有动感 |
| Cape 披风 |  | 物理模拟飘动，随风/运动方向摆动 |
| Head Yaw/Pitch 头部转向 |  | 头部独立动画，转头/抬头自然 |
| First-Person Hand 第一人称手部 |  | 持物时有正确姿态，手臂位置准确 |

---

##  Work In Progress / 开发中

### 🪣 Bucket Family — 水桶家族（11 items）

> 目标：3D 桶身 + 液体晃动/生物探头 + **强烈弹跳反馈**（参考基岩版 *Access and Stuff*）

| Item | ID | Animation Plan | Progress |
|:---|:---|:---|:---:|
| 空桶 | `bucket` | 3D 铁桶模型 + 手持弹跳反馈 |  |
| 水桶 | `water_bucket` | 桶身 + 水面晃动效果 + 倒水时甩动动画 |  |
| 熔岩桶 | `lava_bucket` | 桶身 + 熔岩发光粒子 + 滴落感动画 |  |
| 牛奶桶 | `milk_bucket` | 白色液体面晃动，倾倒时流动感 |  |
| 细雪桶 | `powder_snow_bucket` | 霜冻质感 + 雪花飘落粒子 ️ |  |
| 鳕鱼桶 | `cod_bucket` | 小鱼探头张望 + 尾巴轻摆 |  |
| 鲑鱼桶 | `salmon_bucket` | 鱼身左右摆尾，跳跃感 |  |
| 热带鱼桶 | `tropical_fish_bucket` | 彩色鱼夸张摆动，鳍部飘动 |  |
| 河豚桶 | `pufferfish_bucket` | **鼓胀/收缩呼吸动画** ，受惊时膨胀 |  |
| 美西螈桶 | `axolotl_bucket` | 探头 + 眨眼 + 腮部蠕动 + 尾巴摆动 |  |
| 蝌蚪桶 | `tadpole_bucket` | 小尾巴高频摆动，圆身体微颤 |  |

### ️ Weapon Family — 武器家族（7 items）

> 目标：攻击挥砍惯性 + 蓄力后仰 + 命中震动反馈

| Item | ID | Animation Plan | Progress |
|:---|:---|:---|:---:|
| 剑 | `sword` | 挥砍惯性弧线 + 命中短震动反馈 ️ |  |
| 斧 | `axe` | 重劈蓄力明显，下砸力度感强 🪓 |  |
| 镐 | `pickaxe` | 挖掘蓄力上举 + 下砸敲击动作 ️ |  |
| 弓 | `bow` | 拉弓蓄力身体后仰 + 释放回弹  |  |
| 弩 | `crossbow` | 装填上弦动作 + 发射后坐力反馈 |  |
| 铲 | `shovel` | 挖掘铲起动作，泥土飞溅感 🪏 |  |
| 锄 | `hoe` | 翻地动作，手臂挥动幅度大 |  |

###  Planned / 计划中

- [ ] Custom shield blocking animation — 盾牌格挡（举盾手臂前推，受击震动）
- [ ] Equipment & hotbar swap animation — 装备/快捷栏切换动画（平滑过渡）
- [ ] Armor state animations — 不同盔甲材质状态反馈（皮革/铁/金/钻石/下界合金）
- [ ] Player hurt / damage animation — 受伤受击反馈（后仰 + 红闪 + 踉跄）
- [ ] Respackopts configuration support — 可选配置项支持（自定义动画强度/开关）
- [ ] Eating & drinking animation — 进食/饮水动作（手臂抬起，咀嚼反馈）
- [ ] Fishing rod cast & reel — 钓鱼竿抛竿与收线动画
- [ ] Spyglass & compass use — 望远镜/指南针使用姿态

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

>  **Version locked to 1.20.1.**
> 当前仅支持 Minecraft 1.20.1，其他版本可能不兼容。

---

## ️ Tech Stack / 技术栈

- **Animation Framework:** ETF (ExtraTexturesFor) + EMF (Entity Model Features) for Fabric
- **Item Display:** `parent` + `display` override in item model JSON
- **3D Models:** Blockbench modeling → exported as `.emf.json` entity models
- **Animation System:** EMF `timeline` keyframe animation system
- **First-Person:** `player_firstperson.json` arm pose control for hand animations
- **Texture Pipeline:** PNG textures with custom UV mapping for animated elements
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
