# v0.7.0-beta 更新日志
_**(注意,此版本更新了部分存档格式,虽经过测试应当无问题,但为防止存档因升级而小概率损坏,请自行备份)**_
## 方块
* 现在蜘蛛网可以被空手破坏,但不会掉落线,用剑破坏时的耐久消耗降至80点
* 现在原矿块被爆炸破坏后会掉落0-9个随机的原矿
* 降低了铁以上的金属箱子的硬度,略微提高了银,铜箱子的硬度
* 现在可以使用铁镐破坏金箱子
* 现在下界疣不需要在下界也能生长,但需要光照小于等于3
* 现在方块的爆炸摧毁,掉落非本体物品的效果将同时应用于处于掉落物状态的方块和已放置的方块
## 物品
* 添加了黑曜石小刀的配方
* 现在红石火把和灵魂火把分别可以烧制5个和0.5个物品
* 现在工具仅会在破坏其能起加速效果的方块时才会损失耐久(即现在镐子破坏泥土不会损失耐久,使用镐子破坏自己的低于镐子等级的金属箱子不会损失耐久)
* 现在所有的箭均能通过与滞留药水合成来变为带有药水的箭
* 现在盾牌能与旗帜合成来改变盾面
* 现在红砖和下界砖均能通过使用进行投掷,投掷伤害为1点和2点
* 现在艾德曼锁链护甲也会拥有艾德曼护甲一半的魔法抗性和击退抗性效果
* 降低钨工具和武器0.5的伤害,以保持装备伤害梯度的一致性
* 添加了经验瓶的可获得的经验值提示
* 修改了部分附魔所能应用的物品
  + 锋利: 现在仅能应用在剑, 战斧, 镰刀上
  + 亡灵杀手: 仅能应用在战锤上
  + 截肢杀手: 仅能应用在剑上
  + 现在镰刀也可以附魔效率和精准采集
  + 现在镰刀,三叉戟也能附魔迅捷, 吸血, 击晕, 抢夺
## 生物
* 修改了大地元素的相关机制
  + 现在可以不使用工具攻击黏土元素
  + 未被熔岩覆盖的大地元素在岩浆中(或黏土元素在火中)会积攒**热量**
  + 当大地元素的**热量**积攒至100时会转变为带熔岩纹路的大地元素(对于黏土元素则会变为陶瓦元素,陶瓦元素不会带有纹路,但仍有**热量**)
  + 对于处在寒冷方块(如冰,雪块等)或雨中的带有熔岩纹路的大地元素,其**热量**会缓慢下降,直至**热量**小于100时变为不带熔岩的大地元素(陶瓦元素不会退化为黏土元素)
  + 被雷击中的大地元素会直接转换为带熔岩纹路的大地元素,同时获得大量**热量**
  + 被带熔岩纹路的大地元素攻击会有40%概率着火
  + 大地元素的熔岩纹路的明暗程度会反映其所含的热量
* 现在末影人将对带有末影之眼或末影珍珠的玩家发起攻击
* 现在骑乘被驯服的马不需要冷却, 喂食冷却降至200秒
* 现在熟兔肉的蛋白质值改为48000,回复饥饿值改为6点,生兔肉回复饥饿值改为3点
* 原矿块的分解获得数量改为9个
## 世界生成
* 现在地底世界地牢箱子新增远古金属币,远古金属桶,远古金属盾牌,远古金属匕首,远古金属鱼竿生成
* 现在各类地牢普通等级(如人工矿道,海底遗迹,沙漠神殿等)的宝箱中新增锈铁盾牌,金币,铜币,银币,铜桶以及锈铁和铜系列低耐久工具武器的生成
* 下界的灵魂沙峡谷新增骷髅公爵的生成
* 略微提高了地下世界生物群系的温度
## 进度
* 现在进度"均衡饮食"和"资深怪物猎人","怪物猎人"进度加入MITE相关物品或怪物
## 其他
* 现在玩家死亡后胰岛素反应值将保留
* 现在抛出的粘液球击中后也会产生破碎粒子效果
* 现在物品的耐久度显示可以通过开关高级物品提示或按SHIFT进行控制
* 更新了宝石碎片,桶,矿石方块和部分实体的材质(由luck_He提供)
* Fabric加载器版本更新至0.16.10
## Bug修复
* 修复了使用瓶子或碗从炼药锅接水时物品消失的Bug
* 修复了水碗无法往装了水的炼药锅中继续装水的Bug
* 修复了其他类型的桶在与炼药锅交互后变为铁桶的Bug
* 修复了发射器无法发射新增加的箭矢的Bug
* 修复了床被爆炸摧毁后仍会掉落本体的Bug
* 修复了蓝莓和甜浆果无法生长的Bug
* 修复了栅栏门无法被玩家跳过的Bug
* 修复了在苔藓块上种植草会将苔藓块变为草方块的Bug
* 修复了干草块无法被空手破坏的Bug
* 修复了南瓜苗,西瓜苗无法生成南瓜,西瓜的Bug
* 修复了鱼竿在抛出后材质仍为未抛出的Bug
* 修复了各类远程攻击生物的抛物轨道不正确的Bug
* 修复了恶魂由于与玩家高度相差较多而被清除的Bug
* 修复了黑曜石鱼竿和燧石鱼竿无法使用的Bug
* 修复了在马喂食间隔的时候进行喂食会导致物品在客户端被消耗的Bug
* 修复了各类环境生物无法正常生成的Bug
* 修复了附有中毒的弓射出的箭会转为药水箭的Bug
* 修复了盔甲的护甲值在重进世界或以特定顺序装备时不正确的Bug
* 修复了碗在以掉落物的形式装水时,获得的水碗突破堆叠上限的Bug
* 修复了半砖无法横向延伸的Bug
* 修复了水碗在参与合成后不返还碗的Bug
* 修复了在物品合成即将完成的一瞬间关闭合成界面可以得到物品而不消耗原料的Bug
* 修复了末地艾德曼矿石无法生成的Bug
* 修复了进行世界更新时维度消失的Bug
* 修复了甜菜根生病时材质错误的Bug
* 修复了砂岩熔炉的翻译错误
---

# v0.6.9-beta 更新日志
## 方块
* 为许多方块添加了被爆炸破坏后的独特掉落物,且掉落物会被爆炸击退
  + 床: 1-2木棍, 1-2丝线
  + 木制品: 1-2木棍
  + 羊毛: 1线
  + 书架: 2-4纸
  + 砖块: 1-2红砖
  + 煤块: 0-9煤炭
  + 圆石类制品: 1砂砾
  + 深板岩圆石: 1圆石
  + 干草块: 0-9小麦
  + 下界砖类: 1-2下界砖块
  + 红石灯: 0-4个红石
  + 红沙岩类: 1-2红沙
  + 沙岩类: 1-2沙子
  + 熔炉类: 其材质方块的爆炸掉落物
  + 下界石英矿石,绿宝石矿石,钻石矿石类: 1对应的宝石碎片
  + 青金石矿石类: 3-6青金石
  + 铜及其氧化系列: 根据氧化程度及切制程度掉落0-9个铜锭(每层氧化减3个)
  + 绿宝石,钻石块: 9对应宝石碎片
  + 青金石块: 0-9青金石
  + 红石块: 0-9红石
  + 石英块: 4下界石英
  + 南/西瓜: 1南/西瓜种子
  + 仙人掌,下界岩,花盆类,煤矿石类,头颅,甘蔗,火把: 不掉落
* 绯红菌索现在有0.1硬度
* 为一些方块添加摔落减伤:
  + 绯红菌索,诡异菌索,蕨,大型蕨,草,枯死的灌木,缠根泥土,农作物,树苗: 20%
  + 苔藓地毯,下界苗: 10%
  + 雪: 每层提供10%
  + 树叶: 60%
* 现在可以通过对作物使用动物粪便来为其下方的耕地施肥
* 蕨,草种植在泥土上时可将其下方的泥土变为草方块
* 砂砾在被非玩家因素破坏时将固定掉落其本身
* 草现在被非玩家因素破坏时不掉落种子
* 丛林中的橡树树叶现在可能会掉落橘子,丛林树叶可能会掉落香蕉
* 脚手架合成表中的线可用皮革绳代替
* 不使用精准采集挖掘煤炭块将掉落9个煤炭
## 游戏机制
* 大幅修改了掉落物的逻辑
  + 掉落物着火时无法被玩家捡起
  + 生肉类掉落物若被火烤制,在被烤制一段时间后将变为熟肉并掉落对应烧制经验\
    但熟肉会附带生肉剩余的燃烧时间,若熟肉被烧制稍长时间将直接消失
  + 在火中烧制的物品将有概率使火焰熄灭(物品数量越多概率越大)
  + 各类有耐久的物品在火焰中烧制或被爆炸击中将会降低耐久值
  + 无耐久的普通方块掉落物被爆炸损坏会掉落其方块形式时被爆炸破坏产生的特殊掉落物,若无特殊掉落物则直接消失
  + 除装备外的纯金属物品(金属粒,金属锭,桶,金属币等)的掉落物不会被爆炸损坏
  + 雪块,冰块,水桶,牛奶桶掉落物会浇灭熔岩,生成黑曜石或圆石,水桶或牛奶桶则会变为空桶
  + 空桶在水中会变为水桶
  + 熔岩桶在水中会变为石头桶
  + 雪块,冰块,雪球,雪的掉落物或在背包中的物品会在较炎热的群系中蒸发消失
  + 糖,面粉此类粉类食物会在水中溶解消失
  + 燧石,钻石,绿宝石被爆炸破坏后会变为对应碎片
## 物品
* 现在碗可以像水瓶一样从炼药锅取水或倒水入炼药锅
* 现在不同材质的桶均可以像铁桶一样与炼药锅进行液体交换
* 现在使用热值低于煤炭的燃料烧制4个沙子/红沙将得到沙岩/红沙岩
* 现在骨粉可以在草方块上催生植物或催生苔藓块
* 燧石铲现在需要皮革绳来制作(放在第二排的木棍右侧)
* 现在可以用金苹果和经验瓶来合成附魔金苹果
* 击退抗性等百分比属性现在会以百分比在物品提示中显示
* 银质护甲现在可以抵挡部分负面效果(负面效果抗性)
  + 对中毒,窒息以及夜翼和暗影食尸鬼的失明: 按百分比降低效果持续时间
  + 对尸妖攻击造成的经验流失: 按百分比降低流失的值
* 银工具和武器现在会对亡灵生物造成25%额外伤害
* 镰刀现在可以进行横扫攻击,并且横扫攻击额外附加50%攻击伤害
* 略微修改了盔甲的护甲值随耐久降低的计算公式,现在应该更加平滑
* 现在甜菜根具有4800的胰岛素反应
* 现在下界疣和西瓜,南瓜,甜菜种子可以被食用
* 现在剪刀可以直接右键剪下普通植物,树叶,羊毛,蜘蛛网
* 鞍现在可以通过5个皮革和2个铁粒合成
* 现在箭矢只能烧制半个物品
## 游戏机制
* 现在玩家在水中攻击实体至少会有1点伤害
## 生物
* 狼现在被玩家击杀会掉落0-2个皮革(受抢夺加成)和5点经验
* 羊现在被击杀会掉落0-1个皮革(受抢夺加成)
* 流浪者现在掉落锈铁箭而不是铁箭
* 战锤现在会对骷髅类生物造成双倍伤害
* 苦力怕的爆炸现在只能破坏一些低硬度的方块
* 深板岩变种的大地元素现在掉落深板岩圆石而不是深板岩
* 现在怪物默认使用的箭类型变为锈铁箭
* 现在岩浆怪免疫投掷物伤害
* 现在除绿色史莱姆之外的史莱姆在接触熔岩桶物品时将会受到5点伤害并将桶变为石头桶
* 现在地底世界不会出现小僵尸
* 现在使用附魔金苹果可以将虚弱的僵尸村民瞬间变为村民
* 附魔师村民的经验瓶交易现在变为祛魔瓶交易
* 史莱姆的移动速度随尺寸增长的比例减半
## Bug修复
* 修复了盔甲护甲值在退出后重进失效的Bug
* 修复大地元素不免疫摔落伤害的Bug
* 修复用牛奶桶浇灭火元素时崩溃的Bug
* 修复相位蜘蛛索敌创造或旁观玩家的Bug
* 修复了鞘翅和海龟壳无法被修复的Bug
* 修复了斧头挖掘便携方块会损失耐久的Bug
* 修复了鹤嘴锄无法对锄头能加速挖掘的物品加速挖掘的Bug
* 修复了结构在未解锁进度时就生成的Bug
* 修复了美西螈不会生成的Bug
* 修复了一些中文翻译错误
---

# v0.6.8-beta 更新日志
## 物品
* 将熔岩桶提供的烧制时间从20000降为3200(16个标准物品)
* 钟的合成改为1个红石与8个金粒, 指南针的合成改为1个红石与8个铁粒
* 现在四个圆石可以合成一个石头
* 金质物品现在不会被腐蚀
## 方块
* 枯死的灌木现在无法被立即采集,而是有0.1的硬度
* 提高灰化土的硬度为0.62,与草方块保持一致
* 如果箱子在底面为完整面的方块下方,将无法被打开
* 南瓜和西瓜苗现在也会生病和枯死
* 蘑菇在长大的时候会将其下方的泥土变为菌丝
* 菌丝会在其上方随机生成棕色蘑菇
* 灵魂沙现在为重力方块
## 世界生成
* 现在在掠夺者前哨站的箱子内会生成指向林地府邸的地图
* 现在在地底世界会随机生成繁茂洞穴地形和紫晶洞
* 地底世界两层中间基岩层的厚度增加了两格,但大幅增加了空洞出现的可能性
* 现在只有解锁了掠夺者哨站的结构进度后才会在世界中随机生成灾厄小队
## 生物
* 兔子现在也会生病
* 添加了新的怪物: 幽魂
  + 会在地底世界生成
  + 血量为18点,攻击力为2点
  + 会在空中漂浮并像恼鬼一样冲向玩家进行攻击
  + 所处位置越黑其外形越透明,当其中心所在位置的亮度小于0.3时将完全不可见并且无法被攻击
* 幻术师现在会释放混乱法术,对其目标敌人施加`混乱`效果,持续10秒
  + 施法时间: 5秒, 初始延迟: 20秒, 冷却: 8秒
* 现在幻术师射箭时也会进行自动预判
* 卫道士现在将手持铁战斧,并且有5%的概率在生成时变为红眼卫道士
  + 红眼卫道士现在会掉落1-2个绿宝石
  + 普通卫道士现在会掉落2-4个绿宝石碎片
* 现在潜影贝在关闭状态下不会受到玩家的伤害
* 现在腐蚀性史莱姆的攻击会让玩家加速饥饿
* 略微削弱了牛受惊后逃跑的速度
* 现在兔子在自然生成时有0.1%的概率变为杀手兔
* 现在成年兔子会固定掉落一个兔肉
* 现在鱿鱼不会锁定脚下踩的不是水的玩家
* 在河流中的每个区块最多生成1只鱿鱼
* 降低了鱿鱼距离玩家过远时(24格外)的游动频率,并降低了鱿鱼的游动速度
* 删除了制图师的林地府邸藏宝图的交易
## 状态效果
* 添加了`混乱`效果
  + 拥有此效果时,每两秒,玩家的前后和左右移动操作会分别随机变为正向或反向
* 现在女巫诅咒玩家时,还会在左下角显示独特的界面效果
## 其他
* 更新了`结构`进度界面的背景苔石砖贴图
## Bug修复
* 修复了下界上层地幔层会刷怪的问题
* 修复了实体AI导致偶发崩溃的问题
* 修复了动物恐慌无限传染的问题
* 修复了下落的水流变为无限水的Bug(已知因此导致的Bug: 在方块下方放水会立即消失)
* 修复了秘银工具的挖掘效率过高的Bug
* 修复了钨矿材质不正确的问题
---

# v0.6.7-beta 更新日志
## 物品
* 艾德曼锭现在可以通过烧制艾德曼相关矿石获得或通过合成获得:
  + 需要一个潜影壳,一个钨锭,一个下界合金锭,一个紫颂花,一个末影之眼来合成一个艾德曼锭
* 现在钨装备或工具需要2个艾德曼锭即可升级为艾德曼装备或工具
* 每一件艾德曼护甲现在将会提供0.5的**魔法抗性**
## 方块
* 现在漏斗在转移熔炉中烧制好的物品后,也会将熔炉中存储的经验值以经验球的形式生成在漏斗中
* 将硬化黏土熔炉重命名为陶瓦熔炉,并改为陶瓦合成,以匹配高版本的命名
* 篝火(及灵魂篝火)改动:
  + 篝火现在不再是默认点燃的,且拥有燃烧等级,最大三级,燃烧等级会随着时间缓慢下降
  + 放出来的篝火可以通过打火石直接点燃或使用木棍多次右键来钻木取火点燃(可能成功也可能失败,均会消耗一个木棍)
  + 篝火烧制食物的速度取决于篝火的燃烧等级,燃烧等级越高烧制用时越短
  + 篝火在达到最大燃烧等级时会点燃并伤害其上方的实体,点燃而非最大等级时只会造成伤害而不会点燃
  + 通过对篝火使用木板(消耗4个提升1级燃烧等级)或木棍(消耗8个提升1级)或煤炭(消耗1个提升3级燃烧等级)
* 虫蚀方块改动:
  + 新增**被虫蚀的下界岩**方块,用于生成爆炸蠹虫
  + 虫蚀方块在默认情况下在被破坏时会根据其所在环境确定蠹虫类型\
    (下界:爆炸蠹虫, 地底世界:白化蠹虫, 周围3格范围内有铜矿石: 铜毒蠹虫, 其他: 普通蠹虫)
  + 当蠹虫主动进入一个拥有被虫蚀变种的方块时,该方块被挖掘后生成的蠹虫类型将会被固定为所钻入的蠹虫的类型
* 小蘑菇(红色和棕色)现在可以被直接种植在上方有水的泥土上,同时降低了蘑菇的生长速度
* 添加了下界钨矿和末地艾德曼矿石
## 生物
* 现在红色,绿色,黄色史莱姆在触碰到农作物时会使其生病;黑色,白色史莱姆在触碰农作物时会将其直接破坏且不掉落
* 动物现在会自动在周围掉落物中找寻自己的食物并自己吃下
* 再次提高了动物寻找水源的间隔,以减少性能开销
## 世界生成
* 删除了地底世界的钨矿生成和下界的艾德曼矿石生成
* 在下界添加了下界钨矿生生成,在末地添加了末地艾德曼矿石生成
* 大地元素现在可以在恶地地形的地表,和末地生成
* 现在被虫蚀的石头会在所有地形生成,但降低了单区块生成数量
* 地底世界会自然生成白化蠹虫
* 削减了石岸的矿物生成量和砂砾生成量并降低了矿物生成层数
* 黑寡妇蜘蛛现在会在丛林地形自然生成
## 游戏机制
* 添加了**魔法抗性**属性,每一点魔法抗性能给予一点对于魔法伤害的护甲(即计算方式是和护甲一样的)
* 末地水晶现在使用钨镐即可破坏
* 玩家的装备在熔岩中会以正常的10倍速度损坏
* 新的饥饿度计划
  + 站在温暖/冷的/冰的水里，饥饿速度分别增加+0%/+25%/+50%
  + 浸在温暖/冷的/冰的水里，饥饿速度分别增加+0%/+50%/+100%
  + 站在普通雨/暴雨里面，饥饿速度分别增加+25%/+50%
  + 站在冷水里面，并且如果还有普通雨/暴雨的话，饥饿速度分别增加+37.5%/+50%
  + 任何一种形式的营养不良，饥饿速度增加+50%
  + (温暖的水的意思就是在沙漠里面的水)
* 现在玩家可以通过在附魔台反复放入拿出物品来刷新附魔
## Bug 修复
* 修复了在获取各类结构进度后,寻找结构的各种方式无法定位到第一个正常生成的结构的问题(如无法用末影之眼找到地牢)
* 修复了远古金属制品能在铁砧修复的问题
* 修复了模组添加的原木可以被空手挖掘的问题
* 修复了某些模组在渲染字体时崩溃的问题(尚不确定是否真的修复)
* 修复了严重损坏的钨砧顶部贴图错误的问题
* 修复了镰刀采集部分植物没有速度加成的问题
* 修复了斧子附魔时运打草后种子掉落数量不正常的问题
* 修复了能够通过合成突破物品堆叠上限的问题
* 修复了怪物会攻击僵尸马和骷髅马的问题
* 修复了在添加了其他音效修改的模组后MITE的音效无法播放的问题
* 修复了食尸鬼不会攻击村民的问题
* 修复了用剪刀剪下植物时剪刀的音效没有正确播放的问题
* 修复了部分拥有发光眼睛的实体眼睛的透明材质不正确的问题
* 修复了一些翻译,材质和当前版本不统一的问题
* 修复了粘土块无法在黏土熔炉中烧制的问题
* 修复了在蓝月无限生成动物的问题(现在蓝月最多在整个主世界生成64只动物)
## 其他
* 补充上了弃用物品的第二条提示
* 移除了新手提示中关于用手采集原木的内容
* 现在结构生成需求对应的进度内容采用自动生成,将不会出现未翻译的内容
* 模组工具的默认耐久现在改为3200点
---

# v0.6.6-beta 更新日志
## 物品
* 现在镰刀能提高对甘蔗的采掘速度
* 现在锄头能提高马铃薯,胡萝卜,甜菜根的采掘速度
* 移除了传统(三个小麦)的面包的合成表
* 增加了小麦分解为小麦种子的合成表
* 远古残骸需要烈焰棒并在下界岩熔炉中才能烧制
* 艾德曼装备现在由四个艾德曼锭以及对应艾德曼装备在锻造台升级而成
* 艾德曼锭的获取方式改为钨锭和下界合金锭在锻造台合成而得以及烧制艾德曼矿石获得
* 提高了艾德曼装备的腐蚀抗性
* 附魔金苹果提供的抗性提升时间降低至30秒,防火降低至90秒
* 剑每次攻击消耗耐久下降至35点
## 附魔
* 摔落保护每级提供的保护值提高了1点
## 方块
* 远古残骸现在需要秘银级及以上的镐子类工具才能挖掘
* 加入了蓝莓丛,其相关机制与1.6.4-MITE相同
* 作物生病时将在其周围产生粒子效果,以便玩家能够更方便地识别,尤其对于模组作物
* 栅栏和围墙对玩家的碰撞高度变为1格
* 将模组矿物的默认挖掘等级提高至秘银级
## 生物
* 降低了动物寻找水源的范围并优化了怪物的攻击AI以减少性能开销
* 提高了动物周围有效水源的检测范围至2格半径
* 提高了墨鱼朝玩家移动时的速度
* 将末影人的攻击伤害提高至15点
* 将疣猪兽和僵尸疣猪兽的攻击力提高至10点
* 提高了相位蜘蛛躲避攻击并瞬移的几率
* 将猪灵蛮兵的武器改为金战斧
* 降低掠夺者的移动速度,提高其在每个区块的生成数量上限至3个,且在袭击时会优先攻击玩家而不是接近村庄
* 降低了卫道士的移动速度,提高其基础攻击力至8点,且在袭击时会优先攻击玩家而不是接近村庄,并在锁定玩家后即使看不到玩家也会朝玩家靠近
* 降低了灾厄巨兽的攻击力至12点,攻击击退能力提升至2点
* 女巫现在生成后不会自然消失,并且在非建筑的自然生成时不会进行诅咒(为防止模组大量生成持续添加诅咒)
## 游戏界面
* 现在进度界面的结构相关进度将拥有一定层次,但不影响实际获取顺序
## 游戏机制
* 现在私人箱子的主人可以在不使用工具的情况下轻易地破坏私人箱子
* 调整了猪灵物物交易中的物品的权重和数量,以降低其强度,但现在可以交易出1-2个远古残骸
* 玩家淋雨时饥饿速度提高10%
* 新增创建世界后的新手保护期,由游戏规则`startProtectionDay`决定,默认为10,其含义为: \
  在天数小于该值时,\
  怪物生成间隔 = 怪物生成基础间隔值(由游戏规则`mobSpawnInterval`确定) + (`startProtectionDay` - 天数)\
  天数大于设定值则怪物生成间隔即为怪物生成基础间隔值
* 村民用煤炭交换绿宝石时需要的煤炭基础数量改为15个
* 劫掠改动:
  + 劫掠时生成的女巫不会添加盔甲排斥诅咒
  + 在劫掠中剩余三个劫掠者时将会对其添加发光效果以方便定位
  + 在劫掠中添加幻术师,在第6波后生成,每波增加一个数量,至多3个
  + 略微提高了劫掠时掠夺者的数量
* 加快了局部难度的增加速度
## 世界生成
* 移除了主世界的蘑菇地生物群系
* 移除了猪灵堡垒箱子中的秘银装备和工具,但增加了远古残骸
* 地底世界的水域中将生成发光鱿鱼,有每个区块1个的上限
* 下界堡垒的熔岩井下会生成一个远古残骸
* 降低了下界地下远古残骸的生成量
* 下界中生成的下界化石下方将随机生成远古残骸
* 降低了下界绯红森林和下界荒地的僵尸猪灵每组生成数量
* 掠夺者前哨站将会生成少量的卫道士
* 绿宝石矿石现在会在所有地形生成且生成数量增加
* 建筑生成需求改动:
  + 雪屋所需天数需求改为80天,钨镐改为秘银镐,等级改为30级
  + 林地府邸天数需求改为100天
  + 地牢天数需求改为100天
  + 删除了末地城的生成需求
* 提高了地底世界蘑菇地的数量
* 降低幻翼生成的间隔
## Bug 修复
* 修复了模组中的触及范围扩展功能无法正确应用的问题
* 修复了在添加了一些实体动画模组后怪物材质显示不正确的问题
* 修复了大地元素在光影或渲染模组下显示不正确的问题
* 修复了古尸守卫等实体的发光眼睛在光影下无法正确发光的问题
* 修复了女巫诅咒和胰岛素反应的效果能被牛奶清除的问题
* 修复了怪物不会正确地拾取更好的武器和装备的问题
* 修复了女巫在非击杀原因消失时玩家诅咒不会消除的问题
* 修复了砍树附魔高度比理论高度的少一格的问题
* 修复了一些弃用物品与模组之间的兼容性问题
* 修复了剪刀无法对草使用并剪下的问题
* 修复了抢夺对动物仍有效果的问题
* 修复了女巫诅咒玩家时双端不同步导致的显示问题
* 修复了劫掠中劫掠波数与劫掠配置数不匹配导致的崩溃
## 其他
* 暂时禁用了粘液块在被活塞拖动时粘附方块的功能,因其会引发崩溃,计划后续修复
* `xp`命令现在允许使用负数
---

# v0.6.5-beta 更新日志
## 方块
* 现在绊线必须使用剪刀破坏才会掉落
* 现在绊线钩无法放置在活板门和其他门以及活塞上
* 现在脚手架破坏后将不掉落任何东西(一次性)
* 增加了青金石矿石挖掘后掉落青金石的数量,现在挖掘青金石矿会掉落10-15点经验值
* 降低了竹子,竹笋,可可豆,甘蔗的生长速度
* 降低了深板岩的爆炸抵抗性
* 将深层艾德曼矿石改为下界艾德曼矿石
* 地狱疣现在只能种在下界,且生长速度降低
* 提高了破坏红石矿石时掉落的经验
## 物品
* 删除了秘银装备强化为艾德曼装备的合成表
* 提高了附魔之瓶给予的基础经验至30点
* 全部弓射出的箭矢速度降低了10%
* 弩射出的箭矢速度降低了20%
* 丢在地上的碗现在在非水源处也可以接水
* 附魔金苹果的生命恢复时间提升至90秒,抗性提升时间降低至90秒,抗火时间降低至180秒
* 剪刀现在可以右键剪掉草
* 牛奶桶和牛奶碗可以解除身上的状态效果
* 剑对蜘蛛网的挖掘速度提升3倍
## 生物
* 蜘蛛的移动速度降低0.035,追踪距离降低至25格
* 修改了骷髅类怪物的属性
  + 骷髅近战时的移动速度降低0.05
  + 普通骷髅追踪距离降低至25格
  + 所有骷髅武器伤害加成提高20%
  + 所有骷髅武器将会随着天数提高而强化
  + 骷髅领主的血量降低5点,追踪距离降低至36格
  + 骷髅领主现在最多召唤10个骷髅
  + 古尸守卫的攻击伤害提高至8点
  + 古尸生命值提高至8点,伤害提高至6点
* 僵尸类怪物(溺尸,影子潜伏者,尸壳,僵尸村民)追踪距离降低至25格,武器伤害加成提高30%,召唤援军的数量减少
* 僵尸猪灵移动速度降低0.03,基础攻击力提升至7点,追踪距离改为25格,并且现在可以捡起装备
* 洞穴蜘蛛生命值降低2点
* 苦力怕追踪距离提高至25格
* 溺尸拥有三叉戟的几率降低,且三叉戟溺尸攻击间隔提高1秒,攻击范围降低4格
* 大地元素的攻击现在会无视护甲
* 末影人的血量提升至50点,攻击力提升至9点,且现在会对背包中有末影珍珠的玩家主动攻击
* 尸妖,食尸鬼,黑色食尸鬼现在不会拥有装备
* 地狱犬现在在攻击时有60%的概率让目标着火
* 怪物生成时持有武器的概率提高,装备的升级概率提高
* 相位蜘蛛现在更容易躲避玩家的攻击
* 猪灵蛮兵的基础攻击力提高至8点
* 提高了破坏深板岩时生成黑色史莱姆的概率
* 黑色史莱姆现在免疫墙内窒息伤害
* 唤魔者的施法速度翻倍,起手时间缩短2秒
* 幻术师的移动速度提高0.1,血量提升至38点,装备提升至秘银弓,且拥有通用预判能力,
  + 致盲法术施法时间减半,起手时间缩短3秒
  + 隐身法术施法时间减半,起手时间缩短2秒
* 掠夺者的弩攻击距离提高至12格,移动速度提高0.3,血量提高至35点,近战基础伤害提高至6点,追踪距离提高至36格
* 恼鬼血量提升至18点,基础伤害提高至5点
* 卫道士移动速度提高0.1,追踪距离提高至24格,血量提高至30点,基础伤害提高至6点
* 修改了村民交易相关的机制
  + 村民现在一天只会补一次货
  + 极大的削弱了村民的交易,兑换绿宝石的交易每次补货只能进行一次,并提高了所需要的物品数量
  + 降低了农民兑换苹果的数量和次数
  + 不再能兑换秘银装备
## 世界生成
* 主世界
  + 蜘蛛,苦力怕,史莱姆的每组生成数量下降
  + 骷髅领主生成权重增加
  + 减少了钻石矿石的每处最大生成数量并将生成层数下调10层
  + 增加了上层铜矿石,生成层数为50-100层,生成数量为3,每处最大数量为10
  + 中层铜矿石每处生成最大数量增加,最高层数降低15层
  + 减少了高层铁矿石和小型铁矿石的生成数量
  + 增加了绿宝石的生成数量并将最低层数上调10层
  + 增加了银矿石的生成数量,生成最低层数下调30层
  + 秘银的生成数量提升,最大生成层数上调20
* 地底世界
  + 溺尸的生成权重减少,每组生成数量减少
  + 地狱苦力怕,恶魔蜘蛛,远古骷髅领主生成权重增加
  + 古尸每组生成最小数量增加
  + 增加地狱犬的生成,权重为20,每次生成一个
  + 金矿最低生成层数上调20层
  + 青金石,银最低生成层数上调30层
  + 铁,铜最低生成层数上调16层
  + 秘银的生成次数略微降低
  + 钨矿石的每处最大生成数量减少,生成次数增加,最大生成层数降低25
  + 中间基岩层的空洞大小增加
* 下界
  + 增加了大地元素的生成
  + 增加地狱艾德曼矿石的生成,在0-40层生成,生成数量为3
## 游戏机制
* 玩家现在只有全身没入水中才会使攻击力减半
* 受到伤害时经护甲降低后最低伤害下调至0.8,提高盔甲韧性的保护效果
* 现在怪物生成间隔可以通过游戏规则`mobSpawnMinTick`控制,默认为3,越大怪物生成越慢
* 现在玩家使用物品间隔可以通过游戏规则`itemUseInterval`控制,默认为4,越大使用间隔越久(设置为0也会有1tick的间隔)
* 劫掠总波数提高至8波,怪物装备附魔概率全等级提升20%
* 玩家36格之外不会刷新怪物
## Bug修复
* 修复了果汁雪糕合成表中缺失碗的问题
* 修复了用非铁剪刀破坏树叶和其他植物不掉落的问题
* 修复了无法挖掘符文石的问题
* 修复了红色史莱姆不会吞食鱼类的问题
* 修复了发射器使用剪刀时剪刀的耐久消耗不正确的问题
* 修复了发射器无法使用非铁剪刀的问题
* 修复了胡萝卜作物方块有碰撞体积的问题
* 修复了破坏末地水晶所需镐子挖掘等级不正确的问题
* 修复了在地底世界和地域大地元素的生成和种类不正确的问题
* 修复了斧头破盾无法正常触发的问题
* 修复了穿梭世界时玩家的服务端客户端数据不同步(血量不正确,经验不正确)的问题
* 修复了从末地传送门回到主世界经验清零,状态效果消失的问题
* 修复了在多人游戏中合成进度显示不正确的问题
## 其他
* 现在在地底世界使用符文门时会尽量避免传送到水中
* 现在客户端和服务端的Fabric模组必须完全一致才能接入服务器

---

# v0.6.4-beta 更新日志
## 物品
* 铁的烧制经验提升至15点
* 拥有耐久的物品在火里时不再会瞬间消失,而是每秒减少200点耐久
* 羊毛现在最多可以堆叠8个
* 剪刀现在可以右键直接剪下蜘蛛网
* 增大了剪刀剪羊毛和藤蔓的速度
* 降低了虫子吃玩家物品栏中的物品的速度
## 方块
* 添加了共32个秘银和艾德曼符文石方块,用于搭建符文传送门
* 脚手架现在不能瞬间破坏
* 加入了符文传送门,颜色为深蓝色,在搭建普通传送门时在四角放上相同材料的符文石来建造,可以进行远距离随机传送\
  (秘银符文石传送半径为32768格,艾德曼为262144格)
* TNT的爆炸范围增加1格
## 生物
* 增大了挖掘石头时生成灰色史莱姆的概率
* 现在怪物装备随天数增长的速率可以通过游戏规则`mobStrengthGrowFactor`控制,默认为1.0,越大增长越快
* 史莱姆攻击玩家时不再消耗玩家背包中的金苹果
* 地狱苦力怕爆炸触发范围由3格半径增加至4格半径
* 将远古骷髅公爵的血量降低至30点
* 将骷髅公爵的血量降低至25点
* 将蜘蛛的血量降低至20点
* 将吸血蝙蝠的血量降低至9点
* 将洞穴蜘蛛的血量降低至18点,且其攻击时变为有50%的概率触发中毒
* 带有三叉戟的溺尸的投掷准确度增加
* 骷髅拾取骨头后回血由50%最大生命值降低为20%最大生命值
* 灰色史莱姆现在不再免疫方块掉落伤害
* 提高了灰色史莱姆的移动速度
* 降低了史莱姆攻击玩家时消耗玩家物品的数量
* 降低了小僵尸20%速度和30%的伤害
## 世界生成
* 极大地降低了沉船和埋藏宝藏的物资丰富程度,同时沉船的生成几率变为原来的二分之一
* 怪物生成最大数量降低30%
* 前期怪物生成降低保护的现在在第10天结束
* 降低了主世界史莱姆的生成权重
* 丛林神庙现在不需要条件即可生成
* 降低了钻石和铜矿的每次生成大小
* 降低了高层铁矿和钻石的生成数量
* 降低了恶地的额外金矿数量
* 提高了蠹虫石头的生成数量
* 提高了绿宝石的生成数量
* 溺尸将在地底世界生成
## 游戏机制
* 玩家疾跑时饥饿速度降低
* 降低了河豚在钓鱼中获得的权重
## Bug修复
* 修复了能使用特殊手段在水中放门(或栅栏门)的Bug,现在放门(或栅栏门)需要四周都没有水
* 修复了在潜行时无法使用剪刀剪树叶的Bug
* 修复了生成在水下结构中的可含水方块没有正确含水的问题
* 修复了秘银盾牌合成表不正确的Bug
* 修复了线合成羊毛所需制作等级不正确的Bug
* 修复了狼有时导致崩溃的Bug
* 修复了狼群在攻击动物时相互攻击的Bug
* 修复了岩浆怪掉落物不正确的Bug
* 修复了尸妖攻击没有伤害的Bug
* 修复了鸡下蛋逻辑不正确的Bug
* 修复了动物在生病后无法恢复的Bug
* 修复了护甲耐久不正确的Bug
## 游戏界面
* 现在玩家在睡觉时也能看到自己的饱食度和血量
## 附魔
* 水下呼吸附魔现在改为25%*<等级>的几率下一秒不消耗氧气
## 其他
* 恢复了一些原版的方块/物品以保持兼容性,但这些方块/物品并没有实际作用
* 服务器出生点保护默认关闭
* 支持了更多的Fabric模组,包括且不限于:
  + architectury-4.11.93-fabric
  + bettercombat-fabric-1.6.2+1.18.2
  + combatroll-fabric-1.1.5+1.18.2
  + crittersandcompanions-fabric-1.18.2-1.0.2
  + dual_riders-1.18.2-1.1.1-fabric
  + emotecraft-for-MC1.18.2-2.2.7-b.build.50-fabric
  + InventoryProfilesNext-fabric-1.18.2-1.10.6
  + libIPN-fabric-1.18.2-3.0.2
  + mcw-bridges-2.0.3fabric-mc1.18.2
  + paladin-furniture-mod-1.1.1-fabric-mc1.18.2
  + jei-1.18.2-fabric-10.2.1.1005

---

# v0.6.3-beta 更新日志
## 方块
* 降低了水的流动速度
* 现在挖掘泥土有10%的几率掉落虫子
## 物品
* 现在虫子会吃玩家物品栏和箱子内的植物和肉类
* 现在玩家可以使用剪刀右键剪下蜘蛛网
* 现在用剪刀剪植物将消耗20点耐久
## 生物
* 将骷髅的投掷物精确瞄准应用在烈焰人,恶魂,女巫上
* 添加了深板岩变种的大地元素
* 降低了近战骷髅的移动速度
* 鸡在生病的时候不会下蛋,且最短下蛋时间增加2倍
## 游戏机制
* 现在在主世界以外的世界睡觉不会发生爆炸
* 玩家在死亡后将会在一段时间后自动重生,默认时间为2分钟(可用游戏规则autoRespawnTime修改)
* 玩家在物品栏有虫子的时候可以消耗虫子使钓鱼速度翻倍(若没钓到鱼会返还虫子)
* 将开始计算摔落伤害的高度提高一格(3.5格)
* 降低了火元素的刷新频率
* 空的碗丢入水中后会自动装水
* 岩浆桶在玩家没入水中后会变为石头桶,需要进行合成来还原回空桶
* 玩家复活后将不会重置营养值
* 提高了前期的刷怪速度
## 附魔
* 取消了战斧的抢夺,截肢杀手,亡灵杀手,时运,抢夺附魔
* 取消了战锤的截肢杀手,抢夺,效率,时运,抢夺,精准采集附魔
* 取消了剑的耐久附魔
* 取消了镰刀,锄头,鹤嘴锄的时运附魔
* 降低了耐久和钓饵的附魔难度,使100经验也可以对鱼竿进行附魔
* 删除了杀害附魔
* 击退附魔现在为战锤专属
* 降低了附魔台所得到的附魔的品质
* 耐久附魔现在最高为5级
## 世界生成
* 将下界的顶部和底部的基岩改为了地幔
## 合成
* 增加了秘银弓和远古金属弓的合成表
## 其他
* 现在玩家可以通过在破坏方块时按下右键进入便捷挖掘模式,无需长按即可挖掘相同方块,再次按下左键取消(开启后会在左下角进行提示)
* 现在玩家在进行合成后仍可使用shift点击将合成改为全部合成
* 更新了桶和大部分实体和盾牌的材质
## Bug修复
* 修复了进度的等级和天数要求与文本提示不相符的问题
* 修复了熔炉热值判断不正确的问题
* 修复了铜镐无法挖掘金矿的Bug
---

# v0.6.2-beta 更新日志
## 物品
* 为所有羊毛制物品补全了正确的合成时间
* 现在蠕虫将会吃掉玩家物品栏中的植物制品和肉制品
## 生物
* 怪物现在会每2秒检查并攻击周围最近的玩家
* 下调骷髅的血量至6点
* 降低苦力怕的爆炸范围
* 降低怪物装备的成长速度和装备的品质等级
* 怪物在穿着较好的装备时不会掉落装备
* 相位蜘蛛只有在能看到玩家的情况下才能瞬移至玩家身边,降低了相位蜘蛛的血量
* 箭矢在射到灰色和黑色史莱姆时会被销毁
* 降低了僵尸的血量至20点
* 小僵尸将在16天后才生成
* 降低了鸡,牛,猪的逃跑时移动速度
## 游戏机制
* 现在怪物生成将会有20秒的间隔,随着天数减少,50天时降为0
## Bug修复
* 修复了缴械附魔在不正确的情况下触发的Bug
* 修复了负等级负面效果未正确应用的问题
* 修复了部分附魔未在创造物品栏显示的问题
* 修复了服务端性能不足时合成速度大幅降低的问题

---

# v0.6.1-beta 更新日志
## Bug修复
* 修复了漏斗有时仍可吸取玩家无法拾取的物品的Bug
* 修复了在Fabric下进入世界时维度丢失的问题
* 修复了更新世界版本时维度丢失的问题
* 修复了耐力附魔最高等级不正确的问题
* 修复了击晕附魔所给予的缓慢效果时长不正确的问题
* 修复了缴械附魔缴械概率过高的问题
* 修复了迅捷附魔在计算攻击速度时算法与描述不符的问题

---

# v0.6.0-beta 更新日志
## 物品
* 现在弓可以使用各种类型的箭,并拥有对应的伤害加成和回收几率
* 降低了用粒合成锭需要的工作台等级
## 方块
* 高炉和烟熏炉现在的热值等级为2
* 降低10倍竹子的生长速度
* 植物将在血月的时候有概率生病
## 附魔
* 提高了附魔的强度
* 增加了大量新附魔,具体信息如下表:

|  名称  | 稀有度  | 最大等级 |   可用装备   |                       作用                       |
|:----:|:----:|:----:|:--------:|:----------------------------------------------:|
|  凿击  |  稀有  |  V   |    镐子    |                  攻击时无视<等级>点护甲                  |
| 灵活移动 | 不常见  |  IV  |    护腿    |              在被减速时提供20%*<等级>的移动速度              |
|  收获  | 不常见  |  V   |    农具    |        收获工具所对应的作物时有10%*<等级>的几率得到一个额外的作物        |
|  缴械  |  稀有  |  V   |    剑     |           攻击怪物时有8%*<等级>的几率使怪物的手持物品掉落           |
|  精准  |  常见  |  V   |   远程武器   |                每级增加25%射出物体的精准度                 |
|  中毒  |  稀有  |  I   |   远程武器   |                 使射出的箭额外增加中毒效果                  |
|  屠宰  | 不常见  | III  |    匕首    |           杀死家畜时会额外掉落[1,1+<等级>)个额外肉类            |
|  击晕  | 不常见  |  V   |    武器    | 攻击目标时有10%*<等级>的概率给予对方2+5*<等级>的持续2.5*<等级>秒的缓慢效果 |
|  吸血  | 非常稀有 |  V   | 非银或秘银制武器 | 每次攻击有10%*<等级>的概率触发吸血,恢复造成伤害量的50%的血量(对亡灵和傀儡无效)  |
|  回收  | 不常见  |  V   |   远程武器   |             每级有20%额外概率使射中实体的箭矢可回收              |
|  肥沃  | 不常见  |  V   |    农具    |    当使用锄头耕地或使用镰刀收割成熟作物时有20%*<等级>的几率使下方的耕地肥沃     |
|  砍树  | 不常见  |  V   |    斧子    |            当砍伐原木时会同时破坏上方<等级>个连续的原木             |
|  再生  |  稀有  |  V   |    胸甲    |              提供50%*<等级>的自然生命恢复速度               |
|  速度  |  稀有  |  V   |    靴子    |                提供5%*<等级>的额外移动速度                |
|  耐力  | 不常见  |  IV  |    胸甲    |      降低破坏、放置方块，攻击，投掷，耕地，拉弓时20%*<等级>的饥饿速度       |
|  迅捷  | 不常见  |  V   |    武器    |                提供20*<等级>的额外攻击速度                |
|  杀害  |  稀有  |  V   |    斧子    |                    相当于"锋利"                     |
+ 注1:远程武器不包括三叉戟,农具为锄头,鹤嘴锄,镰刀
+ 注2:缴械时若为怪物自带的武器,则掉落后玩家无法捡起该武器,若为怪物捡起的玩家的武器则玩家可以捡起,缴械后掉落的物品均有3秒的捡起延迟
+ 注3:女巫,村民无法被缴械
* 修改了一些原版附魔的效果,如下:
+ 保护: 改为增加12.5%*<等级>的额外护甲值
+ 时运: 现在有10%*<等级>的几率使掉落物翻倍
+ 耐久: 现在会减少约0%至15%*<等级>的耐久度损耗(符合均匀统计分布)
+ 快速装填: 现在也可以用于弓上
## 生物
* 现在凋零骷髅生成时持锈铁剑,僵尸生成时默认所持的铁质物品现在均为锈铁物品
## 药水效果
* 现在防火效果不再能防止岩浆伤害,只能防止火焰伤害
* 现在抗性提升改为每级提供5点护甲
## 怪物生成
* 降低了怪物的最大数量
## 游戏机制
* 现在玩家投掷物的精准度与等级有关,等级越高,精准度越高
* 现在射到生物上的箭会在生物死亡时按其回收几率掉落
* 现在锄地和投掷史莱姆球也会消耗饥饿值
* 现在末影水晶只能由艾德曼及以上等级的镐子破坏
* 现在岩浆伤害将无视护甲
## 其他
* 更新了许多作物和食物的材质(材质来源: luck_He)
## Bug修复
* 修复了世界生成时生成熔炉导致的崩溃问题
* 修复了秘银弓和远古金属弓拉弓动画的错误
* 修复了地底世界远处迷雾颜色错误
* 修复了无法使用金箭的问题
* 修复了熔炉可以通过合成书向物品槽内放入不合理的物品的Bug
* 修复了通过特殊按键可以立即合成的Bug
## Fabric支持
* 现在Fabric loader版本更新为0.14.21, Fabric API版本更新为 0.76.1
* **_注意!!!!_**:当前Fabric版本仍存在进入世界后有些维度丢失的问题,请先不要使用Fabric版本进入旧存档
---

# v0.5.9-beta 更新日志
## 物品
* 新增物品: 祛魔之瓶\
  使用水瓶,木炭和地狱疣制作,饮用后可以清除女巫诅咒,或在磨石中用于清除装备的附魔
## 生物
* 女巫现在在生成时会诅咒玩家,玩家需要杀死诅咒他的女巫才能去除诅咒\
  女巫的对玩家的诅咒的名称和描述如下表:

  | 名称     | 描述                                |
        |--------|-----------------------------------|
  | 腐蚀性皮肤  | 你发现你的的装备、 武器与工具的耐久度下降的更快(每秒掉2点耐久) |
  | 不能屏住呼吸 | 你发现你不能在水下停留很长时间                   |
  | 不能疾跑   | 你发现你不能疾跑                          |
  | 不能食肉   | 你发现你不能食用任何动物制品                    |
  | 不能食素   | 你发现你不能食用任何植物制品                    |
  | 不能喝汤   | 你发现你不能食用任何汤、煲类食物                  |
  | 末影仇恨   | 你发现末影人总是对你无缘无故的发起攻击               |
  | 智力下降   | 你发现制作物品变得十分困难(时间为正常的两倍)           |
  | 植物恐惧   | 你发现你很难穿越藤蔓等植物                     |
  | 盔甲排斥   | 你发现你不能穿上护甲                        |
  | 箱子恐惧   | 你发现你不能使用箱子                        |
  | 无法入睡   | 你发现你无法使用床                         |
  | 蜘蛛恐惧   | 你发现你很难对蜘蛛发起有效进攻                   |
  | 恶狼恐惧   | 你发现你很难对狼发起有效进攻                    |
  | 苦力怕恐惧  | 你发现你很难对苦力怕发起有效进攻                  |
  | 亡灵恐惧   | 你发现你很难对亡灵生物发起有效进攻                 |

* 提高地底世界中溺尸的生成几率
* 现在怪物的装备会随着天数提升
* 提高蜘蛛射出的蜘蛛网的准度
* 提高所有家畜和马的逃跑时移动速度
## 游戏机制
* 怪物现在会在玩家上下10-20层的范围内刷新
* 玩家所在高度越高,刷怪范围越大,最大64格,最小24格

---

# v0.5.8-beta 更新日志
## 附魔
* 现在附魔将消耗对应经验点数的经验
* 附魔台现在可以吸收周围两圈书架的魔力,提供更多的附魔加成
* 附魔台现在不再需要也不再消耗青金石
* 现在附魔时无法查看第一个附魔属性
* 附魔得到好属性的概率大幅降低
## 物品
* 盔甲提供的护甲值会在耐久度小于一半时随着耐久的降低而降低
* 将盔甲和装备的附魔能力调整至MITE相应水平
* 增加了各种硬币用于存储经验,可以右键使用(不会返还金属粒),可通过在任意附魔台附魔相应的金属粒获得
* 附魔金苹果现在需要200经验来获得
## 方块
* 增加了绿宝石附魔台,使用绿宝石进行制作,附魔的最大等级为钻石附魔台的一半
## 生物
* 为所有怪物提升了40%的生命值
* 所有蜘蛛发射蜘蛛网的间隔增大至30秒
* 地狱苦力怕生成的层数提高
* 亡魂的生成几率和生成权重提高
* 黑色食尸鬼生成层数提高
* 极大地降低了火元素在岩浆周围的生成几率
## 游戏机制
* 怪物现在会在无法到达玩家位置一段时间,且距离玩家水平距离大于16,且看不到玩家时消失
* 怪物在距离玩家竖直距离过大时也会消失
* 血月白天的地表只会生成苦力怕和蜘蛛
* 更改了护甲计算,遵循以下公式: `受到伤害 = max((伤害 - 护甲) / max(盔甲韧性 / 4,1))`
* 再次降低了怪物的最大数量至每玩家36个,怪物的立即消失距离上调至64格
* 降低了血月怪物的刷新量
* 蓝月现在会正确的拥有蓝色的月亮,并且会让地表动物重新生成,抑制怪物的生成
* 降低了多人游戏的怪物数量
* 改变了随着层数降低,怪物生成距离降低的公式: `不刷怪半径 = 0.25 * 纵坐标 + 24` (最近24格),且该公式现在只对主世界有效
* 现在只有主世界的刷怪数量会受血月影响
## 其他
* 降低了箭实体的消失时间
* 局域网服务器的最大人数上调至20人
## Bug 修复
* 修复了负等级刷经验的Bug
* 现在射出什么箭就会捡起什么箭,而不是固定的铁箭
* 修复了秘银弓,远古金属弓附魔能力不正确的问题
* 现在使用不同的箭矢会正确的造成不同的伤害

---

# v0.5.7-beta 更新日志
## 生物
* 蜜蜂移速增加20%。
* 病牛现在还能产奶，改成生病的牛不能接奶。
* 怪物刷新上限增加至每玩家64个
* 整体怪物血量增加40%
* 末影龙血量翻倍,投掷武器攻击处头部以外其他部位无效
## 方块
* 现在熔炉前面有遮挡物会熄灭
## 物品
* 工具攻击怪物现在消耗40耐久度
* 打火石耐久度从64降低至16
* 蜂蜜现在会提供14400的胰岛素抵抗
## 合成
* 磁石合成表中心改为一个秘银锭
## 游戏机制
* 随着层数降低,怪物生成距离降低,公式如下: `不刷怪半径 = 8.17875 * 纵坐标 + 18` (最近16格)
* 玩家死亡后物品掉落的范围扩大
* 怪物的消失距离减少至48格
## 多人游戏
* 服务器外面的外加能看到时间。
* 玩家进入服务器时会进行模组校验,若模组不符合服务器规定则无法连接服务器
## 世界生成
* 沼泽,雪地,树林,动物增加
* 主世界深沉岩的钻石生成率降低
## 其他
* 现在可以使用 `/xp` 命令来查看自己的总经验
## Bug修复
* 修复怪物能隔着很薄弱的地方攻击玩家的问题

---

# v0.5.6-beta 更新日志
## 物品
* 现在剪刀能剪羊毛
## 方块
* 粗铜一个矿石掉落5个改成掉落2个
* 旗帜不能放在水下
* 树苗的生长时间提升两倍
* 降低水的流动速度
* 现在所有的含水方块暂时无法用桶主动注水
* 增加了各种金属箱子,只有放置者可以打开,也只能被比箱子等级高一级的镐子挖掘,若被非放置者破坏时会发出全服通知
## 生物
* 远程骷髅攻击力降低20%.
* 除近战骷髅外全体怪物移速增加10%
* 相位蜘蛛攻击速度减少50%
* 相位蜘蛛将不再自带药水效果
* 相位蜘蛛瞬移时将会有末影人瞬移的声音
* 现在怪物没看到玩家也会尝试向玩家靠近
## 合成
* 秘银矿石现在只能黑曜石炉子才能烧制,且需要岩浆作为燃料
## 游戏机制
* 现在怪物在玩家周围外24格生成
* 在水里开船会消耗饥饿值
* 在较大面积岩浆流体中若周围有玩家,将会有几率生成火元素
## 其他
* 手中的方块用完后若背包中有同种方块,则会填充自动到手中
## Bug 修复
* 修正砂岩的最大堆叠数量
* 修复桶对铁轨使用后消失的问题

---

# v0.5.5-beta 更新日志
## 物品
* 现在饮用奶桶无法清除状态效果
* 现在用剪刀剪树叶有8tick的冷却
## 方块
* 甜浆果的生长速度与原版MITE的蓝莓同步
* 栅栏门,告示牌现在不能放在水中
* 红石矿石每个掉落红石的数量改为1至3个
## 游戏机制
* 吃过多甜食会得糖尿病,加速饥饿,提高进食用时,若继续食用含糖食物(有胰岛素抗性数值)将得到缓慢,虚弱,反胃效果\
  在效果消失前不吃含糖食物即可解除
* 现在玩家可以通过金属砧修复护甲
## 合成
* 6个木板现在只能合成1个门
## 生物
* 近战骷髅血量增加20%至7.2点,移速增加30%至0.39点
* 降低白色史莱姆50%移动速度
* 增加玩家攻击白色史莱姆时工具损耗的耐久度,现在白色史莱姆还会腐蚀他碰到的物品
* 现在无法接山羊奶
## 世界生成
* 怪物生成最大数量下调至52格
* 上调地狱苦力怕,尸妖,土元素,骷髅公爵,吸血蝙蝠,夜翼的刷新权重
* 降低主世界钻石的生成数量
* 增加了主世界的艾德曼矿
* 主世界秘银矿和钻石矿的最低生成层数改为-64格
## 其他
* 玩家在使用桶经验放置流体源时会有经验的声音提示
## Bug 修复
* 修复奶桶饮用后不加饥饿值的问题
* 修复已有附魔的装备能在金属砧上追加附魔的Bug
* 修复多人游戏进入世界时玩家血量显示的问题
* 修复种植甜菜会崩溃的Bug
* 修复给耕地施肥后手部无动作的Bug

---

# v0.5.4-beta 更新日志
## 合成
* 粗铜块,粗金块,粗铁块现在变为4个为一块
* 合成玻璃板一次16个改成一次8个
* 现在4个沙子才能烧一个玻璃.
## 世界生成
* 矿脉的生成率减少百分之50%
* 甜浆果生成率降低90%,每处生成的数量减低60%
* 青金石生成层数降低12格和生成概率降低20%
## 物品
* 现在沙拉同时增加1点饱食度和饱和度
## 方块
* 甜浆果每处右键拾取从3个减少到1个
* 甜浆果只能种在露天的地方
* 现在挖掘一个青金石矿石掉落1至3个青金石
* 橡树树叶掉落苹果的概率降低70%
* 门现在不能放在水里
* 沙子,砂砾等下落方块可以压坏火把
* 蘑菇现在可以在亮度小于9的地方生长成大蘑菇,若周围有过多小蘑菇则会阻止其生长
* 农作物现在具有生病机制
  + 作物在周围没水,或者所处生物群系不适合生长时会有大概率生病,其他时候有小概率生病
  + 在血月时作物将有大概率生病
  + 生病时作物表现为发白
  + 生病的作物不会掉落任何物品
  + 生病的作物会向四周传染
  + 可以用骨粉治愈生病的作物
  + 作物生病时将有概率直接枯萎
## 游戏机制
* 现在没有饥饿值也能攻击，只不过攻击力减半
* 营养不良效果现在生效,一级营养不良增加50%饥饿速度,二级进一步降低75%自然回血速度
* 玩家死亡重生后只有一半植物营养素和蛋白质
* 钓鱼调到附魔书和附魔武器的概率降低50%
* 雷雨天气环境光照减慢的速度变为原来的十分之一
* 主世界60层以上晚上刷怪的所需最小亮度改为5,即在约晚上七点以后才开始刷怪
* 怪物单次刷新的最大个数均限制至2个
## 附魔
* 时运附魔只能将矿物翻倍,每级时运增加10%翻倍几率
## 界面
* 现在玩家无法在附魔台看到能得到什么附魔
## Bug修复
* 修复玩家死亡后点击 _返回标题_ 按钮可以重新回到0级的问题
* 修复沙拉提供的植物营养素数值不正确的问题

---

# v0.5.3-beta 更新日志
## 生物
* 地狱苦力怕现在不再怕火
* 地狱蜘蛛现在不怕火
* 相位蜘蛛只能生成在40层以下,且追踪范围减少至16格
* 苦力怕的生成减少30%,追踪范围减少到24格
* 其余怪物追踪范围统一40格
* 减少蜘蛛发射蜘蛛网的频率至原来一半
* 动物的繁殖冷却时间变为原来的三倍(48000 tick)
* 水碗现在可以喂给动物
## 游戏机制
* 玩家现在最多只能负到50级
* 现在怪物刷新在玩家18格以外
* 怪物的最大刷新数量减少至64个
* 减少10%的饥饿速度
## 物品
* 碗现在可以接水
* 现在南瓜派现给予5点饱食度
* 木棒现在无法破坏蜘蛛网
* 修复一些方块的最大堆叠数量错误
* 修正铁质和金质工具的攻击伤害
## 合成
* 金苹果合成表现在可以用金粒来解锁
* 更正了大部分铁质和金质物品的合成表及和合成等级
* 一个箭矢可以烧一个物品
## 世界生成
* 删除了主世界地表的岩浆喷泉
* 减少了南瓜单次生成数量
* 减少蒲公英的生成
## 附魔
* 删除经验修补和无限附魔
* 附魔消耗多少经验就扣除相应的等级。
* 增加绿宝石附魔台,附魔强度不超过钻石附魔台
* 附魔台现在可以给金苹果附魔,变为附魔金苹果
* 附魔台现在不需要消耗青金石
## 界面
* 现在玩家的植物营养素和蛋白质会在玩家背包上方显示
## Bug 修复
* 修正了桶的放置距离
* 修复了喂水给动物后不返回容器的Bug
* 修复了金属砧掉落崩溃,以及掉落后耐久度错误的问题
* 修复了鱼竿在手部的渲染问题
* 修复了用桶喂水给动物后不返还桶的问题

---

# v0.5.2-beta 更新日志
## 游戏机制
* 苹果的掉落率改为木棍的一半
* 增加马掉牛肉的概率
* 现在驴掉落羊肉
## 合成
* 硬化粘土炉由砖块合成
* 现在一个燃料可以一次性烧４个粘土
* 大部分物品的合成速度与原版MITE同步
* 修改望远镜的合成表,将紫晶碎片改为玻璃板
## 方块
* 为掉落方块添加伤害
  + 泥土基础伤害1点,最大4点
  + 燧石基础伤害2点,最大4点
  + 沙子基础伤害1点,最大2点
## 世界生成
* 绿宝石石只能生成在山地地形,且层数在最底层至25层,并削减了数量
* 甜浆果只能生成在森林地形
## 物品
* 加上所有MITE内的食物外加合成表
* 金质工具耐久减半
* 金苹果和附魔金苹果的饱食度和饱和度下调
* 甜浆果的各数值调至与原版MITE蓝莓相同,作为蓝莓的高版本替代品
## 其他
* 工具下显示的为攻击力加成,而不是手持攻击力

---

# v0.5.1-beta 更新日志
## 物品
* 糖可以食用,增加0.3饱和度和4800胰岛素抵抗
* 鸡蛋可以食用,增加3点饱食度和0.3饱和度以及24000点蛋白质
* 吃鸡肉有概率得到7.5秒中毒,而不是饥饿
* 减少燧石短斧40点耐久
* 木棒增加一倍耐久度
## 方块
* 增加了工作台的硬度
## 游戏机制
* 种子的掉率1/8改成1/5
* 燧石碎片掉率由1/8改成1/7
* 橡树掉落苹果的概率增加一倍
* 降低玩家周围不刷怪的范围至14格,移除出生点的刷怪保护
## 生物
* 增加怪物的仇恨距离到64格
* 怪物会主动攻击离自己最近的玩家
* 马匹每4000刻才能骑一次
* 蜜蜂会主动攻击周围玩家
* 苦力怕爆炸范围削弱20%
* 驴现在有几率掉落牛肉
## 合成
* 全部合成的用时改为2秒
## 界面
* 玩家列表可以查看所有玩家等级
## Bug 修复
* 修复了没有饱食度可以无等待合成的Bug

---

# v0.5.0-beta 更新日志
## 方块
* 为一些方块增加了摔落缓冲
* 刷怪笼默认只能生成15只生物,生成完后不再工作
## 物品
* 南瓜种子可以吃
* 将物品堆叠修改为与MITE基本一致
## 合成
* 一个南瓜现在只能合成1个南瓜种子
## 游戏机制
* 物品和弓箭可以穿过树叶
* 主世界的刷怪笼箱子内会生成胡萝卜和马铃薯
* 修改了攻击伤害与护甲的计算方式
* 饥饿速度变为原来的70%
## 天气
* 增加了月相
  + 血月: 每32天发生一次,所有世界方块都会浮上一层猩红的血色,一轮血月挂在空中\
    怪物得到增强,数量翻倍并大量生成在地表上,白天同时会伴有闪电,玩家整夜无法睡觉,
  + 蓝月: 每128天的血月将会被替换为蓝月, 所有世界方块浮上一层幽深的蓝色.\
    怪物生成受到抑制,动物重新生成
## 渲染
* 将地底世界的天空改为了黑色
## 世界生成
* 加入了岸边的砂砾沉积层
## 生物
* 怪物可以透过树叶看到玩家
* 相位蜘蛛闪避时不会受到伤害
* 骷髅被闪电击中后将骑上具有速度1的骷髅马,同时被给予力量1效果
* 蜘蛛只能吃鸡
* 僵尸不再挖掘可以通过的方块
## 其他
* 服务端世界难度默认设为困难

---

# v0.4.7-beta 更新日志
## 生物
### 动物
* 可以用水瓶或水桶喂食动物,给其补充水分
* 所有剪刀都可以剪羊毛,和用右键剪树叶
* 为家畜动物(牛羊鸡猪)增加了健康系统
  + 动物需要水,若周围没有可见的水动物将生病
  + 动物需要食物,若周围没有食物(草,高草)则会生病,也可手动喂养
  + 动物需要空间,若周围生物过多则会生病
  + 动物会主动在周围寻找水和食物,并主动到空间宽敞的地方
  + 若动物生病(显示为动物发灰),则击杀后不会掉落任何物品
  + 生病时不会掉落任何物品
  + 生病的动物生出的小动物也会继承父母双方中健康值最差的一方的健康值
  + 若动物因非饥饿的其他因素而生病,则无法喂食
  + 动物在满生命值且不饥饿,不生病时才能繁殖
* 可以用碗接牛奶
* 猪也可以以棕色蘑菇为食物
* 动物被攻击后会使周围的动物均惊慌
* 动物间惊慌传递的冷却提升至10s,以防止惊慌循环传播
* 将动物喂食后再次喂食的冷却增加至800秒
### 史莱姆
* 岩浆怪在攻击玩家时会使玩家着火,着火时间为史莱姆大小乘以三秒
* 改变了史莱姆吞食玩家背包内物品和损坏玩家工具的计算方式
* 史莱姆伤害计算方式更改,不同类型的史莱姆有不同的伤害
  + 普通史莱姆1倍
  + 褐色史莱姆2倍
  + 白色史莱姆和红色史莱姆3倍
  + 黑色史莱姆4倍
* 红色史莱姆攻击玩家时有四分之一的几率给予2.5s的缓慢5效果
* 灰色史莱姆在挖石头的时候有百分之一的几率出现
* 黑色史莱姆在挖深板岩的时候有百分之一的几率出现
* 所有的史莱姆都会寻找并攻击动物
### 其他
* 骷髅有25%的概率近战,75%的概率,近战骷髅在10天以下使用木棒,10天以上20天以下使用锈铁短剑,20天以上有50%概率使用锈铁短剑,50%概率使用锈铁剑
* 更新了僵尸的AI,让他更加"智能"
* 土元素将免疫摔落伤害
* 骷髅不主动攻击动物
## 游戏机制
* 玩家携带一桶牛奶，如果游泳（就是水位到达眼睛的位置），就会变成水
* 钓鱼时间改为45-60秒
* 下雨时钓鱼时间减半
* 钓鱼时间越接近黎明或黄昏钓鱼速度越快(公式为 `减少tick = 200 sin((2 π)/(7000) x+5350)+200)(x为当天时间,2000<x<16000)`)
* 在非开放水域中无法钓到钓鱼
* 地底世界使用床不会爆炸,但是无法躺下
* 空手攻击怪物反伤改为有八分之一的几率触发
## 世界生成
* 地底世界钻石生成率增加20%,每处钻石生成个数增加1个
* 地底世界岩浆生成概率增加一倍，刷怪笼生成率增加30%
* 地底世界刷怪笼的刷怪种类改为古尸
* 移除了地底世界的僵尸,骷髅,食尸鬼,亡魂,骷髅领主生成
* 将吸血蝙蝠,吸血巨幅,夜翼的生成类型改为怪物
* 地底世界蘑菇地生成率减半
## 渲染
* 为古尸守卫添加了红色眼睛
* 修改了熔岩土元素的渲染,使其熔岩纹路发光(但现阶段有些透明)
## Bug 修复
* 修复用铁桶接牛奶变成金牛奶桶的Bug
* 修复了吸血蝙蝠,吸血巨蝠,夜翼无法被攻击的问题

---

# v0.4.6-beta 更新日志
## 游戏机制
* 中毒现在会导致玩家死亡,中毒时造成伤害的速度减慢至5秒一次
* 玩家现在无法从流动的流体向上游(但是还是可以浮在流动流体表面)
* 玩家吸引经验球的距离由8格改至2格,且玩家死亡时掉落的经验球不会被其他玩家吸取
* 玩家的部分属性现在将随着等级的提升而提升
  + 每级提升2%挖掘速度和合成速度(均为最后计算)
  + 每级提升0.5%基础近战伤害(在暴击后,附魔前计算)
  + 负等级则起相反作用,但基础近战伤害每负一级减少2%
## 方块
* 绿宝石方块和钻石方块受到爆炸会掉落9个对应的碎片
* 竖纹石英块,錾制石英,(平滑)石英块,(平滑)石英楼梯爆炸后掉落0-4个石英,(平滑)石英台阶爆炸后掉落0-2个石英
* 绿宝石矿石,钻石矿石,下界石英矿石受到爆炸会掉落1个对应的碎片
* 炸掉黑曜石会掉落0-6个黑曜石碎片
* 炸掉煤矿石不会掉落物品
* 踩在岩浆块上必定会着火2秒,无论是否蹲下或拥有冰霜行者附魔
* 降低黑曜石的爆炸抗性至10(原来的1/120)
## 生物
* 牛的血量上升至20点
* 地狱犬和火元素会自动绕开水源
* 骷髅可以和僵尸一样拾取骨头回复生命值,冷却也是20s
* 驯服狼现在有5秒冷却
* 马一天只能喂养一次
* 骷髅现在掉落燧石箭
* 现在远古骷髅公爵不会掉落身上的装备
* 现在骷髅公爵掉落远古金属箭而不是铁箭
* 动物(牛羊猪鸡)受到伤害后会将恐慌传递给周围的动物
* 骷髅不会受到仙人掌的伤害
* 食尸鬼可以和僵尸一样挖方块
* 火元素和烈焰人对火焰附加的剑和燃烧的箭免疫
* 烈焰人现在只能用附魔武器攻击
* 岩浆怪只受到能够破坏石头的武器伤害,也就是锤子和镐子
## 合成
* 现在树苗能烧制1个物品,粪便能烧制2个物品,热值均为最低
## GUI
* 现在在任何时候都可以看到装备的耐久
## Bug 修复
* 修复了铁砧和损坏铁砧的翻译错误
* 修复没有饥饿值也能放方块的Bug

---

# v0.4.5-beta 更新日志
## 世界生成
* 移除了地表的岩浆湖
## 合成
* 一个火把现在能烧4个物品
* 一张纸现在能烧0.125个物品
* 一个钓鱼竿能烧1个物品
* 一本书能烧0.5个物品
* 烤马铃薯不会再获得经验
* 现在骨头只能分解为1个骨粉
## 方块
* 现在下界岩,绯红菌岩,诡异菌岩需要铁镐才能采集,且硬度增加至2.6
* 玄武岩硬度增加至2.7
* 玩家挖掘功能类方块时的挖掘速度加快四倍
* 烟熏炉和高炉现在可以使用空手采集
* 所有熔炉的硬度由3.5降至2.5
* 现在不使用精准采集破坏任意颜色玻璃将掉落6个玻璃碎片,破坏任意颜色玻璃板将掉落1个玻璃碎片
* 玻璃板在受到较大速度的抛射物撞击时将会破裂
## 生物
* 重新加入了小僵尸
* 僵尸将主动捡起地上的较好装备
* 怪物将可以通过玻璃看到你,并尝试绕过玻璃攻击你
* 僵尸可以挖掘方块来攻击玩家,若有工具,则会加快挖掘的速度,以及能挖掘同等级的方块
## 物品
* 暂时使骨粉失效,无法用于催熟和催出草等功能,待之后的版本再进行进一步更改
* 发光浆果改为和种子一样提供0.3的饱和度
## 游戏机制
* 再次增加了走路,跑步,游泳,涉水行走的饥饿消耗速度
* 玩家在水中使用弓会无法向上游且取消游泳姿态
* 玩家在水中或岩浆中的攻击伤害降低一半,发射出的抛射物(包括箭,鸡蛋,末影珍珠等)的准确度也下降
## Bug 修复
* 修复了从旧版本升级到新版本后下界和末地消失的问题

---

# v0.4.4-beta 更新日志
## 生物
* 马现在会掉落0-2个牛肉(不要问我为什么是牛肉)
* 鱼类逃脱攻击者的速度提升至3.5,逃避玩家时的远距离速度为2,近距离基础速度为3.5,且在玩家七格内时,鱼的速度会不断加快
* 地狱苦力怕现在可以破坏主世界的各种石头和下界的各种石头
* 提高骷髅射击的准确度,其攻击范围及追踪增至32格
* 现在僵尸类生物将会通过拾取地上的肉来回复50%生命值,冷却时间为20秒
## 游戏机制
* 放置方块的延迟增加到7 tick
* 怪物生成最大数量增加至100,自然消失距离增至160格
* 提升怪物生成的尝试次数和生成尝试范围
* 放置方块的饥饿消耗提升160%
* 玩家在没有饱食度和饱和度时无法破坏方块,放置方块,攻击生物,合成物品
* 玩家未使用工具或骨头,木棍攻击敌对生物时将受到1点反击伤害
* 移除了难度对生物造成伤害的提升
## Bug 修复
* 修复火把不能作为燃料的Bug
* 修复金矿石均不能烧的Bug

---

# v0.4.3-beta 更新日志
## 药水效果
* 现在 **_缓慢_** 效果会减缓玩家镜头的移速
## 生物
* 鱿鱼
  + 现在会主动追击水中的玩家并给予10s缓慢2和15秒溺水效果
  + 将主动攻击船只并将船撞毁
* 猪灵和僵尸猪灵将主动攻击玩家
* 怪物会攻击动物,且被怪物击杀的动物不掉落物品
* 蜘蛛
  + 最大生命值改为12点,移动速度增加至0.35,攻击力增加至4点,跟随距离降至28格
  + 会朝玩家吐蛛网以减慢玩家的移动速度同时给予玩家3s缓慢2的效果
* 僵尸
  + 僵尸攻击力提高至5点,跟随距离提高至40格
  + 移除小僵尸
* 骷髅最大血量改为6点,移动速度增加至0.3,近战攻击伤害改为4点
* 鱼类将不会掉落经验
## 游戏机制
* 方块放置距离减短(空手时对方块:2.75格,空手时对实体:1.5格)
* 限制方块放置间隔为5tick
* 放置方块时会消耗饱食度
* 修改一些怪物的刷新区域和刷新规则(注: 以下生成规则均需要亮度满足,即除惧狼外都需要可供怪物刷新的低亮度环境):
  + 骷髅领主在主世界32格以下或地底世界生成
  + 食尸鬼在主世界56格以下或地底世界生成
  + 尸妖在主世界48格以下或地底世界生成
  + 吸血蝙蝠在主世界48格以下或地底世界生成,最大单次生成数量为4,归为环境类
  + 巨型吸血蝙蝠在地底世界生成,最大单次生成数量为4,归为环境类
  + 夜翼在主世界32格以下或地底世界生成,最大单次生成数量为2,归为环境类
  + 相位蜘蛛在主世界48格以下或地底世界生成,最大单次生成增加至数量为4
  + 僵尸领主在主世界44格以下或地底世界生成
  + 影子潜伏者在主世界40格以下或地底世界生成
  + 恶魔蜘蛛在主世界32格以下或地底世界生成
  + 黑色食尸鬼在主世界32格以下或地底世界生成
  + 大地元素在主世界40格以下或地底世界生成并且下方要有适合的方块
  + 古尸在地底世界生成
  + 远古骷髅领主在地底世界生成
  + 惧狼在主世界针叶林普通狼可生成的地方生成
  + 木蜘蛛在主世界周围有树叶或原木的地方生成
  + 火元素,爆炸蠹虫,铜毒蠹虫,白化蠹虫这类特殊生成的生物不会使用世界生物生成器自然生成
## Bug 修复
* 修复了艾德曼桶在发射器中表现为打火石的问题
* 修复了更新反馈的网址不正确的问题

---

# v0.4.2-beta 更新日志
## 配方
* 添加了烧制深板岩铜矿石,深板岩铁矿石,粗铜和粗铁的配方
* 将用高炉烧制金属矿石的所需热值改为2
## 方块
* 高炉最高热值限制为2
## 生物
* 僵尸和僵尸村民现在不再掉落铁锭
* 相位蜘蛛进攻时追击实体传送最小触发距离改为8格 ~~(现在也不会到处乱飞了)~~
## 游戏机制
* 现在玩家睡觉时将加速回血
## Bug修复
* 修复了在Fabric加载时,使用水桶会崩溃的问题
* 修复了发射器放出水桶均变为铁桶的问题
* 修正相位蜘蛛的实体碰撞箱大小
* 修复了退出游戏重进后区块生成不连续的问题

---

# v0.4.1-beta 更新日志
## 生物
* 添加了几种原版MITE里的史莱姆
  + 灰色史莱姆
  + 红色史莱姆
  + 褐色史莱姆
  + 黑色史莱姆\
    **其设定大部分和1.6.4MITE的相同**
* 极大地减少了溺尸在水中的移动速度 ~~(现在他不会飞着过来打你了)~~
## 方块
* 现在原木被炸毁时不会掉落任何东西
## 物品
* 添加了各种可以扔出的史莱姆球
  + 绿色史莱姆球: 造成 2 点伤害
  + 灰色史莱姆球: 造成 3 点伤害,并腐蚀方块和实体
  + 红色史莱姆球: 造成 3 点伤害
  + 褐色史莱姆球: 造成 2 点伤害
  + 黑色史莱姆球: 造成 4 点伤害,并腐蚀方块和实体
* 添加了各种金属桶,并对桶进行了修改
  + 桶无法放置流体源,除非按住ctrl键并花费100xp
  + 现在你需要使用桶并按住ctrl键来捞起液体的源头
  + 桶可以捞起流动的液体
  + 桶在捞起岩浆的时候有几率损坏(损坏的几率可以通过在空桶上按住shift查看)
* 现在玻璃瓶也可以从非水源处盛水
## 配方
* 增加了地底世界矿石的烧制配方
## Bug 修复
* 修复了动物不生成的Bug
* 重新更新了数据包
* 修复了下界合金工具没有耐久度的问题
* 修复了空桶右键火元素即可对其造成伤害的问题

---

# v0.4.0-beta 更新日志
## 生物
* 添加了以下几种MITE的怪物
  + 相位蜘蛛
  + 大地元素
  + 食尸鬼
  + 尸妖
  + 亡魂
  + 古尸
  + 吸血巨蝠
  + 吸血蝙蝠
  + 夜翼
  + 地狱爬行者
  + 地狱犬
  + 火元素
  + 史莱姆球
  + 远古骷髅领主
  + 骷髅领主
  + 铜毒蠹虫
  + 白化蠹虫
  + 爆炸蠹虫
  + 影子潜伏者
  + 黑寡妇蜘蛛
  + 恶魔蜘蛛
  + 惧狼
  + 暗影食尸鬼
  + 木蜘蛛\
    以上各生物的具体属性和生成区域与MITE1.6.4大致相同
## 物品
* 增加了秘银弓和各种箭矢(具体属性和合成方式尚未增加)
## Fabric支持
* 从该版本开始,本模组将兼容Fabric加载器和Fabric API
* 当前已支持的模组请参阅 [此处](./README_CN.md)(README.MD)

---

# v0.3.1-beta 更新日志
## 方块
* 再次极大地降低了黑曜石的硬度
* 降低了深板岩圆石和其对应形态所有矿石的硬度
## 物品
* 为深板岩矿石添加了烧纸合成表
* 现在绿宝石,钻石,青金石,下界石英可以右键使用来获得经验值
  + 绿宝石每个250点
  + 钻石每个500点
  + 青金石每个25点
  + 下界石英每个50点
## 世界生成
* 修改了地底世界的温度,天空和雾的颜色
* 地下世界现在会生成菌丝地,上方有棕色蘑菇生成
## 其他
* 现在按下`shift`键即可查看物品高级属性
## Bug 修复
* 修复了玩家负等级刷经验的Bug
* 修复了村庄生成时由于熔炉崩溃的Bug

---

# v0.3.0-beta 更新日志
## 方块
* 添加了地幔和秘银,银,艾德曼的深板岩矿石
* 添加了地底世界,主世界,主世界出生点传送门
  + 主世界在Y轴-32层以下搭建传送门即可生成地底世界传送门
  + 主世界其他地方搭建传送门将会生成出生点传送门,进入后将传送至世界出生点
  + 地底世界在地幔上方搭建传送门即可进入下界
## 世界生成
* 添加了地底世界
  + 地底世界主要由深板岩组成,其中分布大量矿物
  + 地底世界最底层为地幔,上方有两层基岩,其中分布有空洞,可以通过挖掘到达地幔层
  + 越往下矿物越多,其中艾德曼在第二层基岩下,钨矿在第一层基岩下才会生成
  + 地表上会随机生成刷怪笼,内含远古金属和其他物品
## 物品
* 燧石斧的合成表中添加皮革绳
* 甜浆果恢复的饱食度下降为1点(半格)
* 木棒最大耐久提升至500
## 游戏机制
* 加快玩家移动时饥饿的速度,现在各种动作饥饿速度从大到小排序如下
  1. 疾跑(饥饿系数:0.09)
  2. 水中游泳(饥饿系数:0.07)
  3. 浸没水中行走(饥饿系数:0.05)
  4. 半身在水中行走(饥饿系数:0.03)
  5. 陆地上行走(饥饿系数:0.01)
## Bug修复
* 修复了睡觉无法跳过夜晚的问题
## 其他
* 更新了燧石铲的材质

---

# v0.2.1-beta 更新日志
## 物品
* 将金苹果的生命回复效果持续时间从5s提升至60s
* 镐子和锤子的耐久消耗提高50%
## 方块
* 降低了煤炭矿石的方块硬度
## 进度
* 为沉船,埋藏的宝藏,传送门遗迹,堡垒遗迹,掠夺者前哨站添加了相应的进度,条件如下:
  + 沉船 和 埋藏的宝藏:20级 30天 获得一套铁盔甲,铁砧
  + 地表的传送门:进入下界生成
  + 猪灵堡垒:获得艾德曼镐
  + 掠夺者前哨生成:获得所有农作物(胡萝卜,小麦,土豆,甜菜根)
## 世界生成
* 现在服务端默认生成世界类型改为巨大生物群系,与单人游戏保持一致
* 现在人工矿洞,水下遗迹,下界堡垒,下界化石不需要解锁即可生成
## 命令
* 修改了`time`命令的用法,现在用法为: `time <(day <set <天数> | query>) | (daytime <set (<本日时间>|<day>|<night>|<noon>|<midnight>) | query>) | (gametime <set <游戏时间> | query>)>`
## GUI
* 现在在F3调试界面下可以看到当前的天数
## 材质
* 将MITE内的大部分物品和方块的材质更换为*luck_He*提供的材质,在此感谢*luck_He*为高版本迁移提供适配材质
## Bug修复
* 修复了饱食度到0点时立刻掉血的Bug
* 修复了熔炉在保存存档后进入出现热值过高的Bug
* 修复了使用`time`命令后世界时间不正确的问题
## 其他
* 更改`version.json`内版本号为MITE版本号
* 在制作人员名单中加入了MITE1.18的制作人员

---

# v0.2.0-beta 更新日志
## 物品
* 将现有食物的各项数值同步为与1.6.4MITE相同
* 使各种的金属盾牌,拥有不同的冷却时间,伤害减免,击退抗性,如下表所示

| 材质   | 耐久  | 冷却时间(秒) | 伤害减免 | 击退抗性 |
|------|-----|---------|------|------|
| 铜    | 32  | 7       | 20%  | 30%  |
| 银    | 32  | 7       | 20%  | 30%  |
| 锈铁   | 16  | 7.5     | 10%  | 20%  |
| 铁    | 64  | 6       | 30%  | 40%  |
| 金    | 48  | 6.5     | 25%  | 35%  |
| 远古金属 | 128 | 5       | 40%  | 50%  |
| 秘银   | 256 | 4       | 50%  | 60%  |
| 钨    | 512 | 3       | 60%  | 70%  |

## 世界生成
* 只有玩家达成了特定的进度后才会生成结构,详见"**结构**"进度(_生存20天,获得10级解锁_)
## 方块
* 添加了各种金属砧
* 减少了黑曜石的硬度(_50 -> 20_)
## 游戏机制
* 修复装备不再需要消耗经验,只需要消耗对应的金属粒,但是需要对应或更高级的金属砧,且消耗砧耐久
* 金属砧会在耐久消耗完后破裂消耗掉
## Bug 修复
* 修复了有些金属盾牌不显示的问题
* 修复了部分金属砧无法打开的问题
* 修复了无法在背包合成某些染料的问题
* 修复了部分方块达到挖掘等级但无法挖掘的问题

---

# v0.1.1-beta 更新日志
## 物品
* 修复了武器耐久消耗不正确的问题,现在每次攻击消耗45点耐久
* 修复了背包无法制作火把,南瓜种子,木棍的问题
## 生物
* 动物不再掉落经验
## 游戏机制
* 玩家白天也能睡觉
* 玩家无法在室外或保护不够的地方睡觉

---

# v0.1.0-beta 更新日志
## 世界生成
* 现在生成世界时只能选择放大化或巨型生物群系
* 移除了在湖底和河底的砂砾沉积盘
* 添加了石头内随机生成的砂砾
* 每128天才会重新生成一次动物
## 方块
* 使泥土和沙子一样受重力影响
* 添加了各等级的熔炉(粘土熔炉,硬化粘土熔炉,石熔炉,黑曜石熔炉,下界岩熔炉)
* 添加了各等级的工作台
* 破坏树叶有几率得到木棍
* 熔炉可以用手挖掘
* 强化了泥土,黏土,砂砾,树叶等方块的硬度
* 挖掘砂砾将掉落燧石,燧石碎片,以及其他金属粒和碎片,掉落几率见下表:

| 掉落物品    | 几率      |
|---------|---------|
| 沙砾（它本身） | 3/4     |
| 燧石碎片    | 5/32    |
| 铜粒      | 1/18    |
| 银粒      | 1/54    |
| 燧石      | 1/96    |
| 金粒      | 1/162   |
| 黑曜石碎片   | 1/486   |
| 绿宝石碎片   | 1/1458  |
| 钻石碎片    | 1/4374  |
| 秘银粒     | 1/13122 |
| 艾德曼粒    | 1/26244 |

## 游戏机制
* 现在制作物品需要耗时,且工作台要有足够的等级
* 现在玩家无法挖掘挖掘等级未达到的方块
* 玩家出生时,最大生命值和最大饱食度为3格,每升5级提升1格,最高为10格
* 升级需要更高经验值:\
  设等级为n;每级所需经验=10(n+1);每级总经验=5n²+15n
* 死亡掉落死前经验的三分之一，如果没有等级则会掉为负数
* 玩家饱食度满时无法快速恢复生命值,但只要有饱食度,每隔64秒即可恢复1点生命值,躺在床上时,每隔32秒即可恢复1点
* 饥饿速度增加为原来的1.25倍
* 只要玩家有饱食度或饱和度就可以进行疾跑
* 缩短了玩家的触及半径(空手时对方块是2.8格,对实体是1.75格)
* 使玩家的挖掘速度明显变慢
## 物品
#### 食物
* 添加了沙拉,食用后恢复1点饱食度
* 使小麦种子可以食用,恢复0.3点饱和度
* 苹果恢复的饱食度降低至1点
* 使棕色蘑菇和红色蘑菇可以食用,恢复一点饱食度和0.1点饱和度\
  但食用红色蘑菇将会给予玩家10s的中毒和60s的反胃效果
#### 工具和武器
* 添加了各种金属对应的工具和武器以及钓竿
* 工具和武器可以给玩家提供触及半径加成
* 木棍和骨头也会给予玩家触及半径加成(均为0.5格),但会有几率在攻击时损坏(骨头1/6,木棍1/4)
## 反作弊
* 创建世界时无法选择创造模式和作弊,也无法选择数据包和奖励箱以及游戏规则
* 创建局域网世界时,无法选择游戏模式和作弊
* 亮度被锁定在昏暗且无法修改
* 难度锁定为困难
## GUI
* 世界选择界面只会显示支持的世界(由MITE1.18创建的世界)
* F3无法查看所在的区块和坐标以及面对的方块或流体