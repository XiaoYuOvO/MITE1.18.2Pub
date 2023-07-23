[English Version](https://github.com/XiaoYuOvO/MITE1.18.2Pub/blob/master/README.md)
# MITE1.18
**_一个人不可能只是搞了几个胡萝卜然后制成夜视药水，去到地底世界挖钻石就一夜暴富_**
## 特性
* 让你更难采集资源
* 怪物更具有攻击性
* 续航性更差
* 添加多种怪物、食物、工具、护甲

## 客户端安装
* 客户端安装请查看[此视频](https://www.bilibili.com/video/BV1MS4y117mk/)

## 开发者模式
* 本模组有开发者模式,客户端可通过在游戏启动参数中加`--devMode`开启

## 制作服务端
* 现版本制作服务端只需要使用安装器在安装时勾选安装服务端,然后再启动器中选择带-server后缀的版本启动即可
* 请注意在HMCL启动服务端时需要打开查看日志才能够查看服务端日志信息,默认的服务端窗口将不会显示日志
### 注意事项&常见问题
* 服务器的目录就是在客户端的根目录,若要更改,请修改启动脚本中`cd /D`后的路径
* 如果服务器一开启就退出,并显示如下内容:\
    `You need to agree to the EULA in order to run the server. Go to eula.txt for more info.`\
  请到服务器根目录(默认即为客户端根目录)下寻找`eula.txt`,并将其中的`eula=false`改为`eula=true`\
  保存然后重启服务器
* 若服务器崩溃,请将logs的latest.log发送过来并说明发生问题时玩家的动作
* 若要修改服务器最大内存,请修改启动脚本中`-Xmx`后的数值
    
## 赞助
* 你可以给我赞助,并获得测试版的体验资格,链接:
   #### [爱发电](https://afdian.net/@XiaoYu233)  

## Fabric支持
从MITE1.18.2 v0.4.0-beta版本起本模组已兼容Fabric模组加载器和Fabric API
### 已知兼容的模组
* sodium-fabric-mc1.18.2-0.4.1+build.15
* Xaeros_Minimap_22.7.0_Fabric_1.18.2
* ferritecore-4.2.1-fabric
* phosphor-fabric-mc1.18.x-0.8.1
* appliedenergistics2-11.0.0 *(部分支持)*
* architectury-4.11.93-fabric
* bettercombat-fabric-1.6.2+1.18.2
* combatroll-fabric-1.1.5+1.18.2
* crittersandcompanions-fabric-1.18.2-1.0.2
* dual_riders-1.18.2-1.1.1-fabric
* emotecraft-for-MC1.18.2-2.2.7-b.build.50-fabric
* InventoryProfilesNext-fabric-1.18.2-1.10.6
* libIPN-fabric-1.18.2-3.0.2
* mcw-bridges-2.0.3fabric-mc1.18.2
* paladin-furniture-mod-1.1.1-fabric-mc1.18.2
* jei-1.18.2-fabric-10.2.1.1005