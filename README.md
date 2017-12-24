### Foobar2000

[Foobar+BBE插件](https://pan.baidu.com/s/1boQosiF)

链接：https://pan.baidu.com/s/1boQosiF 密码：bg1x

软件整体效果如下：

![](http://omvbl46i3.bkt.clouddn.com/1b9204fecc08f5c1ce4b9e6c93e074b7.png)

小状态栏效果如下：

![](http://omvbl46i3.bkt.clouddn.com/3c27b343d04760c794efe0cb52fd3616.png)

功能设置界面如下：

![](http://omvbl46i3.bkt.clouddn.com/68942a8fda15cbeed411768d530c4ea0.png)

#### 功能
- 自带专辑封面显示
- 桌面歌词显示(据说还可以联网下载歌词，本人没有验证过)
- 支持音乐列表查询
- 支持自定义音效插件

#### 插件BBE

BBE技术不是简单的增强高频波，而是把延迟了的高频波时间提前，将其重新置于基波之前，它也是用一些增强技术来恢复一些被削弱了的高频波。

![](http://omvbl46i3.bkt.clouddn.com/2f479d5f2820b8fd50239ef30f602e00.png)

![](http://omvbl46i3.bkt.clouddn.com/7c60c8c7463f09c3799e379bda68ed99.png)

![](http://omvbl46i3.bkt.clouddn.com/a31bfc69f2de74dfa75d33c2f00abc56.png)

##### 安装步骤
- 安装BBE.Sound.All.Plugins.Bundle.VST.RTAS.v1.0.9.20r3.x86.x64-ASSiGN
- 复制foo_vst_0903/foo_vst.dll到foobar目录中的components里面
- 打开设置界面选择组件模块会新增`VST plug-ins`,然后选择add去添加你刚刚安装文件夹里面的组件默认路径`C:\Program Files (x86)\Steinberg\Vstplugins\BBE Sound`
- 设置-播放-DSP管理器-选择`D82 Sonic Maximizer`-配置所选

最后会出现如下图所示的插件

![](http://omvbl46i3.bkt.clouddn.com/cb9702fe3412a2d2bb858b23230f0218.png)

`in`表示`Maximizer on`

- LO CONTOUR: 调节低频激励的量，调整低频部分的相位补偿量
- PROCESS: 调节高频激励的量，调整高频部分的相位补偿量
- OUTPUT LEVEL: 调节处理后信号的电平。可以有效的避免当音频经过处理后，因为电平过载所产生的爆音。

右侧的两排LED灯用来显示BBE D82 Sonic Maximizer输出信号的大小（处理以后的信号大小）。每个LED指示灯代表一定单位数量的输出电平的大小，单位是分贝。例如："0"代表0dBFs信号音量，"-6"代表-6dBFs，以此类推。在固定输入信号大小的情况下，增加BBE Process和LO Contour的数量将提升输出信号音量，LED显示也会更加明亮。顶部Clip的LED灯可以用来监视输出信号大小，当输出信号超过0dBFs时Clip的LED灯将亮起来，这也就意味着输出信号失真了。


具体效果怎么样可以自己用耳朵反复去试听，然后选出自己合适的效果

[youtube软件测试对比效果](https://www.youtube.com/watch?v=sif-cOYWLfY)
