<!--
 * @Description: 
 * @Author: Bullet.S
 * @Date: 2019-12-09 10:04:51
 * @LastEditors  : Bullet.S
 * @LastEditTime : 2019-12-20 14:34:44
 * @Email: animator.bullet@foxmail.com
 -->

# 1. 安装脚本

---

![install_1](_img/install.gif)  

!> 注意选择对应版本的 3ds Max 目录，一般来说改个盘符就行了  

## 1.1 添加工具栏

- 进入 3ds Max 点击菜单栏 “Customize” -- “Customize User Interface...” -- “Toolbars”<br /><br />

![toolbar](_img/toolbar.jpg)

!> 注意第一次安装可能需要重启 Max，或拖入压缩包内的 .ms 脚本到 max（打开插件后脚本可删）  

# 2. 脚本界面

---

![ui](_img/UI.jpg)

!> v0.8.4 版本时UI，后面可能会修改，有建议欢迎交流~

# 3. 简要说明<sub> （建议 Ctrl + F 搜索关键词）</sub>

---

- <mark>开关:</mark>  
首先中键点击界面空白处或者直接点击“中键关闭”即可关闭脚本  
- <mark>起始帧，结束帧</mark>  
改变帧栏范围，功能简单也不常用（emmm？）  
- <mark>(*｀▽´*)颜文字</mark>  
界面切换开关，简易和多功能模式，可能后面会加右键更丰富功能~（待鸽~）  
- <mark>移动帧数</mark>  
输入或者默认的按钮5帧，累加5帧，切换负帧，对应下面的移动帧功能  
- <mark>link？勾选框</mark>  
移动的帧中是否包含Link帧（Max原因，Link帧比较麻烦所以单拎出来，平时没有时可加快效率）  
- <mark>移动按钮</mark>  
分别是 选择滑条前面关键帧，选择所有关键帧，选择滑条后关键帧，（均包含帧栏外），`有选择物体则处理选择，否则处理全部物体的帧,`白色按钮为移动帧，左右键分别可选是否自动给帧范围扩充移动帧数  
- <mark>Box</mark>  
切换Box线框显示，反正我是习惯用线框模式~  
- <mark>冻结模型</mark>  
冻结 Mesh 或者 Poly 模型，取消check即解冻  
- <mark>隐藏骨骼</mark>  
左键隐藏 Bone，右键隐藏 Biped，再点可显示，  
`只处理当前显示的骨骼~`也有习惯直接处理所有骨骼（包括隐藏骨骼），看后面反馈  
- <mark>美好时光</mark>  
简易文件管理工具，打开文件收藏目录等，后面做详细说明。[传送门]()