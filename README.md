# Google+(Baidu Bing 360 Sogou Weibo Twitter)
Show results from Baidu, Bing, 360, Sogou, Weibo and Twitter in Google web search. | 在Google网页搜索显示百度、必应、360、搜狗、微博和Twitter的搜索结果。 

使用之前 ↓

![使用之前](https://user-images.githubusercontent.com/7352378/37223435-5667cc38-2385-11e8-8844-9e9c5f11810e.gif)

使用之后 ↓

![使用之后](https://user-images.githubusercontent.com/7352378/37223433-564e4bb4-2385-11e8-94e6-0dd85e5898a9.gif)

原作者hzhbest的[Google+(baidu bing youdao)](https://greasyfork.org/scripts/4633-google-baidu-bing-youdao)已经三年没有更新了，[据原作者所说](https://greasyfork.org/forum/discussion/21801/x)因为墙的问题连调试脚本都无能为力。

我自己实在是非常喜欢这个脚本，用得很顺手！因为这几年Google的界面以及相关的东西变化也很大，所以我自己班门弄斧在此基础上进行我自己的维护，版本号还是沿用了之前原脚本的。

欢迎在[GitHub](https://github.com/guyigenius/Google-Baidu-Bing-360-Sogou-Weibo-Twitter/issues)上反馈Bug或者提出您宝贵的意见和建议！

## 计划任务
* 微调外部搜索结果页面；
* 修复微博搜索；
* 添加Twitter搜索；

## 更新日志
* 2018.03.02 v1.5.2：微调了页面布局，现在右侧的外部搜索结果不再会遮挡住左侧的搜索结果了，调整了Google OneBox在最左侧的缩放倍数。
* 2018.03.04 v1.5.3：启用并修正了360搜索，调整了外部搜索引擎的显示顺序，将HTTP改成了HTTPS访问。
* 2018.03.05 v1.5.4：删除了有道和中搜搜索。
* 2018.03.05 v1.5.5：@include匹配了Google的二级域名，启用并修正了GoogleCN搜索，更新了外部搜索引擎的URL参数，稍微优化了一下代码。
* 2018.03.06 v1.5.6：微调了页面布局，修正了GoogleCN的显示问题，修正了百度显示百度贴吧时图片过大的问题。
* 2018.03.08 v1.5.7：微调了页面布局，设置了Google OneBox的背景色为白色，调整了GoogleSpecial里面Images for的位置。
* 2018.03.09 v1.5.8：微调了与hover相关的延迟（之前的1s太久了……），README.md添加了使用前后对比示意图。
