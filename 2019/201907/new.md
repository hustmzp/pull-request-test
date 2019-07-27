详细更新记录见个人码云项目记录：[码云更新记录](https://gitee.com/Mcmy/Test/blob/master/%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA%E6%8C%87%E5%8D%97.md)

# 开发环境搭建指南
开发环境的搭建简要分为以下步骤：

* [1. Java环境安装](#1)
* [2. 编程工具安装](#2)
* [3. 串口驱动安装](#3)

下面详细对这三个步骤进行介绍

**注：** 因本文档图片较多，首次加载时加载速度相对较慢并且部分图片可能无法显示，可按下键盘的F5键对网页进行刷新直到可完全加载为止。

<h2 id="1">1. Java环境安装</h2>
在开始此步骤之前，如果你不清楚自己的电脑是否安装了Java环境，那么你可以从第2个大步骤开始，先将编程工具解压后尝试进行一次运行，如果出现了2.6步骤中的情况，请返回这个步骤，完成Java环境的下载以及安装。

- 1.1 下载Javasdk,[下载链接](https://www.oracle.com/technetwork/java/javase/downloads/index.html),点击图中圈出的download按钮

	<div align="center" title = "下载Javasdk">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk1101_download.png"  alt="下载Javasdk" align=center  />
	</div>

- 1.2 同意许可协议。默认状态下勾选的是`Decline License Agreement`，请选择`Accept License Agreement`。

	<div align="center" title = "同意许可协议">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_acceptlinceagreement.png"  alt="同意许可协议" align=center  />
	</div>

- 1.3 选择相应的平台。当前使用的电脑是什么就怎么选择，目前windows64位平台居多。

	<div align="center" title = "同意许可协议">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_paltform%20choose.png"  alt="同意许可协议" align=center  />
	</div>

- 1.4 正在下载Javasdk

	<div align="center" title = "正在下载Javasdk">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_downloading.png"  alt="正在下载Javasdk" align=center  />
	</div>

- 1.5 保存Javasdk。下载完成后，部分电脑的安全软件或安全策略可能会提示是否保存已下载的文件，选择保留或是。

	<div align="center" title = "保存Javasdk">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/save_javasdk.png"  alt="保存Javasdk" align=center  />
	</div>

- 1.6 打开Javasdk所在文件夹，运行安装包

	<div align="center" title = "运行Javasdk安装包">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/java_sdk.png"  alt="运行Javasdk安装包" align=center  />
	</div>

- 1.7 选择是，同意安装

	<div align="center" title = "同意安装">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_install.png"  alt="同意安装" align=center  />
	</div>

- 1.8 安装向导，直接选择下一步

	<div align="center" title = "安装向导">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_install2.png"  alt="安装向导" align=center  />
	</div>

- 1.9 安装，选择下一步，可以更改安装位置

	<div align="center" title = "安装">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_install3.png"  alt="安装" align=center  />
	</div>

- 1.10 正在安装Javasdk

	<div align="center" title = "正在安装">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_installing.png"  alt="正在安装" align=center  />
	</div>

- 1.11 安装完成

	<div align="center" title = "安装完成">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/javasdk_installed.png"  alt="安装完成" align=center  />
	</div>

<h2 id="2">2. 编程工具解压</h2>

#### 编程工具下载

- 首先从[Mixly官网](http://mixly.org/explore/software/mixly-arduino)下载Mixly编程工具，选择自己当前使用的平台（Mac或Windows或python-web，目前Windows平台使用较多）,在提供的下载链接中选择自己当前的平台，如windows平台则选择`Mixly_WIN`文件夹下的`Mixly0.997_WIN.zip`或`Mixly0.998_WIN(7.8).zip`或`Mixly0.998_WIN(7.9).zip`文件包下载到自己的电脑上。由于官方提供的是百度云网盘下载链接，而百度云对网页下载文件的大小有限制，故文件的具体下载方法请结合百度云的下载方式进行。

#### 编程工具解压运行

- 2.1 从官网提供的下载链接是未解压的压缩包文件，若直接双击压缩包打开，会展示压缩包内的文件内容（部分电脑出现的界面如图1所示），此时如果直接运行Mixly程序会出现第2张图的情况，请取消操作，从步骤2.2开始执行。
	<div align="center" title = "压缩包文件内容">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_Undecompressed.jpg"  alt="压缩包文件内容" align=center  />

		图1
	</div>
	<div align="center" title = "无法运行">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_javanotconfig.jpg"  alt="无法运行" align=center  />

		图2
	</div>

- 2.2 解压Mixly文件包

	<div align="center" title = "解压Mixly文件包">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_Decompression.png"  alt="解压Mixly文件包" align=center  />
	</div>

- 2.3 设置解压Mixly文件包的位置

	<div align="center" title = "设置解压路径">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_Decompression_path.jpg"  alt="设置解压路径" align=center  />
	</div>

- 2.4 解压成功后的Mixly文件夹

	<div align="center" title = "解压成功">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_Decompressed.jpg"  alt="解压成功" align=center  />
	</div>

- 2.5 运行Mixly程序出现的界面如下图所示（运行Mixly程序不是指运行Mixly.jar,若电脑配置了Java环境，则运行Mixly.jar也可以打开Mixly程序)

	<div align="center" title = "Mixly程序界面">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_Home_GUI.jpg"  alt="Mixly程序界面" align=center  />
	</div>

- 2.6 Mixly软件理论上来说不需要配置Java环境就可以运行，但是对于一部分电脑如果没有安装Java环境可能出现下图的情况，说明依旧需要配置Java环境，运行Mixly程序如果出现下图的情况，请从`1. Java环境安装`开始执行。

	<div align="center" title = "未配置Java环境">
		<img src="https://github.com/hustmzp/external_link_images/raw/master/smartcar_developed_by_graphical_programming/Mixly_javanotconfig2.jpg"  alt="未配置Java环境" align=center  />
	</div>

<h2 id="2">3. 串口驱动安装</h2>

- 参考Arduino中文论坛教程:[Arduino教程（入门篇）——各版本驱动安装方法](https://www.arduino.cn/forum.php?mod=viewthread&tid=1008&highlight=%E9%A9%B1%E5%8A%A8%E5%AE%89%E8%A3%85)


### 本文档完