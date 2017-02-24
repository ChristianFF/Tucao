# Tucao
![](http://www.tucao.tv/skin2013/banner.jpg)

## Features
- 首页六大模块，推荐、新番、影剧、游戏、动画、频道
- 全站排行榜，支持每日/每周排序
- 放映时间表，可以查看周一到周日新番的更新情况
- 频道列表，支持按照发布时间/播放量/弹幕排序
- 视频搜索，支持分频道搜索
- 视频查看，使用IjkPlayer播放视频，DanmakuFlameMaster播放弹幕，自动拼接多段视频（使用concat协议）

## Screenshots
<a href="art/1.png"><img src="art/1.png" width="30%"/></a>
<a href="art/2.png"><img src="art/2.png" width="30%"/></a>
<a href="art/3.png"><img src="art/3.png" width="30%"/></a>

<a href="art/4.png"><img src="art/4.png" width="30%"/></a>
<a href="art/5.png"><img src="art/5.png" width="30%"/></a>
<a href="art/6.png"><img src="art/6.png" width="30%"/></a>

<a href="art/7.png"><img src="art/7.png" width="30%"/></a>
<a href="art/8.png"><img src="art/8.png" width="30%"/></a>
<a href="art/9.png"><img src="art/9.png" width="30%"/></a>

<a href="art/10.png"><img src="art/10.png" width="30%"/></a>
<a href="art/11.png"><img src="art/11.png" width="30%"/></a>
<a href="art/12.png"><img src="art/12.png" width="30%"/></a>

<a href="art/13.png"><img src="art/13.png" width="30%"/></a>
<a href="art/14.png"><img src="art/14.png" width="30%"/></a>
<a href="art/15.png"><img src="art/15.png" width="30%"/></a>

<a href="art/16.png"><img src="art/16.png" width="30%"/></a>
<a href="art/17.png"><img src="art/17.png" width="30%"/></a>
<a href="art/18.png"><img src="art/18.png" width="30%"/></a>

<a href="art/19.png"><img src="art/19.png" width="30%"/></a>
<a href="art/20.png"><img src="art/20.png" width="30%"/></a>

## TODO
- [x] 搜索历史
- [x] 播放历史
- [x] 离线缓存
- [x] 收藏
- [x] 缓存位置
- [x] 弹幕字号
- [x] 翻转
- [ ] 记录播放位置
- [ ] 更新

## UpdateLog

### V1.0.4
- 修复首页Api问题
- 修复查看更多崩溃
- 修复播放崩溃
- 支持修改缓存位置

### V1.0.3
- 当视频已离线缓存时，播放离线缓存视频
- 记录分P播放历史，方便追番

### V1.0.2
- 修复下载进度暴走的问题
- 修复全屏退出崩溃的问题

### V1.0.1
- 搜索历史
- 播放历史
- 离线缓存（测试）
- 收藏

### V1.0.0
- beta测试


## Instructions
- 设计编码均独立完成，如果你觉得太丑，欢迎砸设计稿
- 架构基于MVVM模式，使用`DataBinding` + `RxJava2` + `Dagger2` + `Retrofit`实现

## Statement
该项目仅供交流学习使用，如果该项目有侵犯Tucao版权问题，本人会及时删除此页面与整个项目。

## Thanks to the open source project
- [Kotlin](https://github.com/JetBrains/kotlin)
- [RxJava](https://github.com/ReactiveX/RxJava)
- [RxLifecycle](https://github.com/trello/RxLifecycle)
- [RxDownload](https://github.com/ssseasonnn/RxDownload)
- [Retrofit](https://github.com/square/retrofit)
- [Dagger2](https://github.com/google/dagger)
- [EventBus](https://github.com/greenrobot/EventBus)
- [GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)
- [ijkplayer](https://github.com/Bilibili/ijkplayer)
- [DanmakuFlameMaster](https://github.com/Bilibili/DanmakuFlameMaster)
- [Glide](https://github.com/bumptech/glide)
- [BaseRecyclerViewAdapterHelper](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)
- [CrashWoodpecker](https://github.com/drakeet/CrashWoodpecker)
- [Leakcanary](https://github.com/square/leakcanary)
- [Convenientbanner](https://github.com/saiwu-bigkoo/Android-ConvenientBanner)
