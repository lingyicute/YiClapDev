# YiClap ✨
## Made for My Best Xyc～❤️
### 送给我最爱的、喜欢听歌的小蟹同学～❤️

![image](https://raw.githubusercontent.com/lingyicute/YiClap/main/app/src/main/res/drawable/material_design_default.webp)

简体中文 | [English](./README_EN.md) 

## 📱 截图
![Screenshot](https://raw.githubusercontent.com/lingyicute/YiClap/main/fastlane/metadata/android/en-US/images/phoneScreenshots/1.jpg)

## 🌟 YiClap 的亮点

### 🧭 简约清爽的设计
YiClap 的界面简洁明了，没有过多的视觉干扰，体验丝滑流畅～

### 🎨 多样的主题
YiClap 提供了数十种播放器主题供你随意挑选。不仅如此，你还可以在浅色模式和深色模式之间随意切换哦。

### 🌟 属于你的色彩
YiClap 支持 Material You 莫奈配色方案。你还可以从调色板中选择自己喜欢的主题色，打造独特的视觉体验～

### 🏠 好玩好用的推荐页
在 YiClap 推荐页，你可以查看自己最常听的歌曲和专辑，并一键播放刚刚添加的新歌。小提示：头像和名字都是可以编辑的喔！

### 🏷️ 完整的标签支持
你知道吗？每个音频文件的开头都有一段特殊的数据，名叫 ID3 标签。它不仅存储歌名、歌手和专辑名称，甚至还可以包含专辑图和歌词。YiClap 提供对 ID3 标签的全面支持。

### 🔐 安全总要有的
YiClap 完全不联网，它甚至根本没有申请联网权限。因此，它是独属于你的——没人会知道你听了什么，包括你的梨。不过，你可以去告诉她～

### 📦 更多特色功能
- 驾驶模式
- 有线耳机 / Bluetooth 设备支持
- 按时长过滤音频
- Android Auto 支持
- Android 8.1+ 的壁纸取色功能
- Android 12+ 的 Material You 支持
- Android 13+ 的 Monet 主题图标支持
- 文件夹支持 - 按文件夹播放歌曲
- 无间隙播放和淡入淡出效果
- 音量控制
- 专辑封面的旋转效果
- 主屏幕小部件
- 锁屏播放控制
- 歌词屏幕（与音乐同步）
- 睡眠定时器
- 轻松拖动以排序歌单和播放队列
- 标签编辑器
- 创建、编辑和导入歌单
- 可重新排序的播放队列
- 按歌曲、专辑、歌手和歌单浏览和播放音乐
- 智能分类 - 最近播放、最多播放和历史记录

> 注意：别忘了 YiClap 是一个离线音乐播放器哦。 因此，它不支持在线音乐平台的流转播放。

## 🕐 更新日志
### August 18, 2024 — v7.1.0
- YiClap 已采用 Target API 33 构建，支持新版媒体权限框架、照片拾取器、独立语言偏好、预测性返回手势等特性。

### October 11, 2024 — v7.2.0
- 修复了崩溃时无法正确显示错误信息的问题，同时修复在 Android 11 及更低版本系统上的若干兼容性问题。

### October 13, 2024 — v7.2.1
- 修复 Android 14 及更高版本系统中睡眠定时器无法设置的问题。
- 此版本已采用 Target API 34 构建，稳定性更佳～

## 🤗 常见问题

### Q：如何获取YiClap的测试版？
你可以查看 GitHub Actions 的测试版构建。

### Q：如何显示歌词？
在YiClap中，有以下添加离线同步歌词的方法。

#### 步骤1：
找到你歌曲的时间戳歌词。时间戳歌词的格式如下：“[00:04:02] 一些歌词文本”
#### 步骤2：
复制这些时间戳歌词。
#### 步骤3：
打开YiClap并进入标签编辑器。
#### 步骤4：
在编辑器中粘贴歌词，然后退出编辑器。
#### 步骤5：
播放歌曲，现在你应该能看到你的时间戳歌词啦。

**一些小提示：**
- 如果你想跳到特定的时间戳，只需滚动到你想开始的时间戳，特定时间戳左侧会出现一个“播放”图标。点击播放按钮即可从那里播放。
- 当你通过在编辑器中粘贴歌词来保存歌词时，记得重新播放以显示歌词。

### Q：如何更改主题？
设置 -> 界面与外观 -> 选择你的主题。

### Q：均衡器非常滞后和不稳定，或者我收到“未找到均衡器”的错误。为什么？
- YiClap没有内置音乐均衡器，它使用系统自带的均衡器。但很遗憾的是，并非所有系统都遵循这些规范。例如，国内的各类魔改UI提供的系统均衡器几乎都存在各种问题，更有甚者直接删除了系统均衡器。这真是一件令人讨厌的事情。

- 如果你在设备上看到“未找到均衡器”，这意味着你的设备没有内置的均衡器。这样的话，我也没办法呀。
 
### Q：如何启用锁屏控制？
设置 -> 个性化 -> 全屏控件 -> 启用（它仅在从YiClap播放歌曲时可见）。
 
### Q：为什么专辑封面显示成了各种乱七八糟的东西？
设置 -> 图片 -> 忽略专辑封面缓存 -> 启用

### Q：支持哪些文件类型？
YiClap使用你的手机自带的媒体解码功能，因此只要文件类型受到你手机的支持，YiClap也会支持。

### Q：为什么我使用YiClap时设备变慢？
YiClap对图像要求较高，它会将图像保存在缓存中以便快速加载。在老设备上，这可能确实会让设备变慢。

### Q：我的YiClap崩溃了，我该如何解决？
真的很抱歉！请尝试清除应用的数据。如果无效，重新安装它试试看。

### Q：为什么所有文本都变成白色/消失了？
将主题更改为黑色或深色，然后再改回你之前的设置。

### Q：为什么我的某些歌曲在我的库中没有显示？
- 请检查这些歌曲是否少于30秒，如果是，请前往设置 -> 其他 -> 过滤歌曲时长。将其设置为零，它们现在应该在库中显示了。

- 如果这仍然无效，重新扫描媒体应该会有所帮助。重启设备以刷新媒体存储。

- 最后，如果你的音频文件存储在SD卡中，请尝试将它们移动到内部存储，然后再移回SD卡。

### Q：为什么我的库中显示歌曲文件两次或根本没有歌曲？
如果你在库中看到歌曲重复或根本没有歌曲，那是因为媒体存储出现了问题。这大概是受到了其他应用的影响。

要解决此问题：

1. 前往设备设置

2. 打开“应用和通知”（此名称因系统而异）

3. 找到“媒体存储”应用并清除其存储（包括数据和缓存）。

4. 重启设备以刷新媒体存储。

**注意：** 当你重启前打开YiClap并看到库中显示“零”首歌曲时，不要惊慌。这是因为你清除了媒体存储，而媒体存储负责识别你设备上的文件。

### Q：为什么开启“星念你”字体没有效果？

YiClap的字体默认使用系统字体，“星念你”是动态替换的。可惜国内某些魔改UI的“主题商店”破坏了Android的字体框架。如果你认为系统字体看起来很丑，那么你可以从Android设置中更改系统字体（国内魔改UI的话，那只能靠主题商店了。）

### Q：如何导出歌单？
- ***从YiClap：***

前往歌单选项卡 > 点击你想导出的歌单上的三点菜单 > 另存为文件。

- ***从其他音乐播放器：***

在你内置的音乐播放器中，应该有一个选项可以将该歌单保存为文件。保存后，通过文件管理器导入到YiClap中。

> 请注意，此类歌单必须仅包含你的离线音乐，因为YiClap是一个离线音乐播放器，而不是在线音乐播放器。因此，如果你的歌单是在线音乐，那么很明显，它在任何离线播放器中都无法打开。

### Q：如何恢复/导入歌单？
当歌单文件存储在“内部存储/Playlist”中时，YiClap会自动检测它们。如果没有检测到，只需打开任何“文件管理器”，并用YiClap打开该歌单文件即可。

要成功恢复歌单，“歌单”文件里记录的歌曲位置和你的手机里歌曲文件的实际位置必须相同。例如，如果你的音乐在“内部存储/Music”中，而歌单文件记载的歌曲位置在“内部存储/Songs”中。那么它当然无法工作，因为这两个位置不同。

## 🗂️ License

YiClap is released under the GNU General Public License v3.0 (GPLv3).

Copyright (C) 2024 lingyicute.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see https://www.gnu.org/licenses.
