## 介绍
百度搜索简约萌化主题。

![](https://raw.githubusercontent.com/JDYuuki/Baidu-lite-moe/main/lib/index_page.png)
![](https://raw.githubusercontent.com/JDYuuki/Baidu-lite-moe/main/lib/search_page.png)


## 注意事项
 1. 百度会为未登录百度账号的设备提供不同的 css 样式文件，在 v1.0.6a 版本中简单修复了这个 css 文件额外带来的部分问题。但仍有一些问题未处理，您可能需要登录百度账号以避免出现不必要的问题。
 2. 在使用百度主题后也有可能会出现不必要的问题，您可能需要在使用本样式前先关闭百度自带的样式功能才能保证本样式的正常工作



## 附加功能
 1. 持续维护的百度样式
 2. 提供搜索页、新闻页、视频页等多个页面的样式支持
 3. 卡片半透明化
 4. 高分屏适配
 5. 支持自定义图片背景



## Feature
- [x] 支持自定义图片
- [ ] 支持自定义单双栏
- [ ] 支持自定义卡片分辨率



## 安装
 1. 在使用本主题前，请先行安装 <a href="https://github.com/openstyles/stylus"  target="_blank"><b>Stylus</b></a> 插件。
 2. 安装样式：
    -  <a href="https://userstyles.org/styles/175260/baidu-lite"  target="_blank"><b>userstyles</b></a> **推荐** 实时更新，但可能较慢
    -  <a href="https://33kk.github.io/uso-archive/?style=175260"  target="_blank"><b>userstyles Archive</b></a> 滞后约一天

## Custom
![](https://raw.githubusercontent.com/JDYuuki/Baidu-lite-moe/main/lib/custom.png)

## 更新历史
**v1.14 - 2022-01-18**
> **Fix**
> 1. 修复底部相关搜索卡片样式失效的问题。
> 2. 尝试性修复上方搜索结果和搜索工具样式失效的问题。
> 
> 由于作者步入职场，此后改项目将转为维护模式，新功能优先级降低，同时由于纯 CSS 的局限性，之后会考虑转为制作 Tampermonkey 插件。

**v1.13 - 2021-05-11**
> **Fix**
> 1. 修复顶部搜索建议样式。
> 
> **New**
> 1. 适配百度新个人中心。
> 2. 现在可以自定义首页顶栏的颜色了。

**v1.12 - 2021-02-25**

> **Fix**
> 1. 进一步修复了部分情况下相关搜索越界问题。
> 2. 微调部分组件的样式。
> 3. 适配绝大多数搜索结果中的提示内容。
> 
> **New**
> 1. 实验性适配搜索结果中的视频广告。

**v1.11b - 2021-01-18**

> **Fix**
> 1. 修复了部分情况下相关搜索越界问题（仍有部分场景溢出，在下个版本修复）。
> 2. 修复了部分情况下将指针悬停在超链接上时，出现双下划线的问题。

**v1.11a - 2020-11-08**

> **Fix**
> 1. 修复了自定义背景无效的问题。
> 2. 适配了百度隐藏搜索结果的样式。

**v1.11 - 2020-11-05**

> **Fix**
> 1. 修复了指针悬停在超链接上时会出现复数下划线的问题。
> 1. 实验性修复了搜索结果中百度游戏的异常表现。
> 2. 修复部分页面的样式错误。
> 3. 回滚了新闻页在高分屏设备上的表现，以期适配下版本提供的多栏。
> 
> **New**
> 1. 现在在高分屏（横向分辨率大于1080p）设备上的搜索框会随着搜索结果居中

**v1.10 - 2020-10-13**

> **Fix**
> 1. 修复了已知的（如贴吧、图片）搜索结果溢出卡片的问题。
> 2. 修复了新闻页改版后不能正常显示的问题。
> 3. 修复了顶部 Tab 位置不正确的问题。
> 4. 修复了已知的（如视频）搜索结果占用过多空间的问题。
> 5. 修复了新闻页标题颜色不正确的问题。
> 6. 修复了搜索结果中部分结果未对齐的问题。
> 7. 修复了视频页样式异常的问题。
> 
> **New**
> 1. 现在可以自定义背景了。
> 2. 去掉百度首页单独的背景图片，现在和结果页使用同一背景。
> 3. 实验性的调整了卡片的宽度，以期解决各种兼容问题。
> 4. 调整了搜索框的长度以匹配卡片的宽度。

**v1.09 - 2020-06-29**

> **Fix**
> 1. 临时修复了新版百度搜索页的适配问题。
> 2. 修复了搜索结果页搜索框前方异常空白的问题。
> 
> **New**
> 1. 添加图片搜索页面的样式支持。
> 1. 添加视频搜索页面的样式支持。
> 
> **注意**
> 1. 近期百度官方样式修改频繁，在使用本样式时或会遇到异常，我会尽量在短时间内修复，也请您在遇到问题时第一时间联系我。
> 2. 由于本样式最早基于 pan_cao 大大的百度轻样式修改而成，代码迭代过程中出现了冗杂的问题。我会尽快推出完全重置的2.0版本，敬请期待。
> 3. 因百度自带的换肤功能会影响到本样式，因此自该版本开始将会隐藏所有换肤功能的入口。
> 4. 同时，当前版本的样式是基于开启“资讯”功能适配的（因为百度默认显示首页资讯，但实际上使用本样式时不会显示资讯）。换回默认皮肤并且打开“资讯”功能（在百度首页右上角中打开资讯）。
> 5. 因为百度在登录账号时会引入一个不同的css文件，强烈建议您在使用本样式时登录百度账号以确保有优质的体验。

**v1.08 - 2020-06-16**

> **Fix**
> 1. 修复了搜索结果中百度知道卡片样式异常的问题。
> 2. 修复了搜索结果中百度经验、百度题库占用空间异常的问题。
> 3. 修复了部分搜索结果中，鼠标悬停在带磁贴的条目上会导致样式错位的问题。
> 4. 修复了所有快递相关的搜索结果样式。
> 5. 进一步修复了搜索结果中百度招聘卡片样式的问题。
> 6. 修复了百度首页搜索框和搜索推荐的样式错位问题。
> 
> **New**
> 1. 添加对[百度不良信息举报][2]（通过搜索结果页底部的“举报”入口进入）的样式支持。
> 
> **注意**
> 1. 因百度自带的换肤功能会影响到本样式，因此自该版本开始将会隐藏所有换肤功能的入口。
> 2. 同时，当前版本的样式是基于开启“资讯”功能适配的（因为百度默认显示首页资讯，但实际上使用本样式时不会显示资讯）。换回默认皮肤并且打开“资讯”功能（在百度首页右上角中打开资讯）。
> 3. 因为百度在登录账号时会引入一个不同的css文件，强烈建议您在使用本样式时登录百度账号以确保有优质的体验。

**v1.07 - 2020-06-12**

> **Fix**
> 1. 修复了图片结果的错位问题。
> 2. 修复了部分结果的显示异常问题（如百度招聘）。
> 3. 修复了部分结果图标缺失的问题。
> 
> **New**
> 1. 广告结果现在将被醒目处理。
> 2. 现在支持搜索结果中的“温馨提示”。


**v1.06a - 2020-03-23**

> **Fix**
> 1. 临时修复了未登陆状态下使用本主题时造成的部分问题。
> 
> **注意**
> 1. 近期发现，在未登录百度账号时，百度会额外引用一个未登录的 css 文件，在最新版本 v1.0.6a 版本中简单修复了这个 css 文件额外带来的部分问题。但仍有一些问题未处理，建议您登录百度账号以避免出现不必要的问题。
> 2. 同样的，在使用百度主题后也有可能会出现不必要的问题，建议您在使用本主题时不要使用百度自带的皮肤功能。


**v1.06 - 2020-03-21**

~~咕了大半年终于又开始更新辣！~~

> **Fix**
> 1. 调整了首页的逻辑，横向分辨率较低的设备上也能够正常使用了。
> 2. 调整了搜索结果页的字体高度，以尝试修复图片结果的图片错位问题。
> 3. 因为本主题在逻辑上隐藏了卡片结果，因此本次更新将“显示卡片”的选项隐藏，避免误触导致错位的问题。
> 
> **New**
> 1. 添加了对 <a href = "https://kira.cool/go/t6dIJVDZ/"  target="_blank">百度产品大全</a> 页面的支持。
> 2. 现在搜索结果的文本对齐为“两端对齐”。


**v1.05 - 2019-10-11**

> 1. 隐藏了首页的滚动条，现在即便是在小尺寸屏幕下首页也不会出现滚动条了
> 2. 稍微上移了首页的搜索框，但首页的搜索框仍未合理，如果您有更好的想法烦请在下方评论区反馈给我。</b>
> 3. 调整了搜索页的滚动条，因为一页只有 10 个结果，可能会在下个版本考虑隐藏滚动条
> 4. 重做了搜索页的 Tab 样式，现在Tab不再有底部的指示条，同时也不再透明。底部的 Foot 背景色将与Tab相同，以减少色彩的使用（注：这是一个尝试性更新，也有可能会在下个版本恢复指示条）
> 5. 稍微增加了搜索结果卡片的不透明度，使之更易于阅读
> 6. 右上角的用户菜单现在不会再挡住用户名了


**v1.04 - 2019-10-01**

> 1. 修改了链接匹配方式，以适配“Infiniti 新标签页 Pro”，以及一些通过非标准链接打开的百度页面。 <b> 
> P.S. 但这可能会遇到预料之外的问题。如您遇到了显示问题烦请在下方评论区反馈给我。</b>


**v1.03 - 2019-09-25**

> 1. 修复了关键词为“携程”、“飞猪”、“去哪儿”时会出现的显示问题
> 2. 修复了关键词为“华为”时会出现的显示问题


**v1.02 - 2019-09-14**

> 1. 现在出现在顶部的“是不是要搜索”提示框也能正常显示了
> 2. 更换了背景图片的图床
> 3. 增加鸣谢名单
> 4. 合并和分离了部分代码


**v1.01 - 2019-09-13**

> 1. 修复了在高分屏下titile会移位的问题
> 2. 现在出现在顶部的“相关搜索”也能正常显示了
> 3. 合并和分离了部分代码
