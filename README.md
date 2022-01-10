# record_something


2020-2022完成的脚本&工具：
--
1、服务存活状态监控程序，部署在本机（mac）每日定时监控测试服务运行状态<br> 

2、网易接口测试平台集成的接口测试脚本，覆盖接口30+，每日定时执行<br> 

3、图片识别测试服务，部署在jenkins，解析指定路径下的MP4文件，按帧转为图片，转码为base64，批量请求定位服务，处理响应，统计结果<br> 

4、手机model数据爬虫，定期爬取github上的手机型号，并统计在xlsx文件中，部署jenkins，构建后发送至指定企业微信群

5、excel分析，遍历指定路径下的xlsx、xls文件，将xls文件转换成xlsx，处理文件中的合并单元，并筛选出所需的数据另存为新文件新sheet，移动老文件到历史目录，定期清理

6、appium实现安卓端部分用例自动化，验证通过unittest及测试中截图与预期的图片相似度判断<br> 

>ps：支持的验证方式<br> 
>1）定位元素text与预期对比<br> 
2）提取toast文字与预期对比<br> 
3）截图与预期图对比（目前仅支持一模一样的，无法提取特征点）<br> 
4）截图提取图片文字与预期文字对比（通过百度开放api实现）<br> 

7、定期爬取官网数据监测更新，抓取更新内容，遍历访问每一个更新内容链接，并下载内容链接中的文件

8、日志分析，二重判断提取，通过正则提取出符合条件的数据，用命令行参数运行

9、设备标定数据处理，文件结构+数据异常校验和处理

好用的工具（已组内应用/体验）
--
1、抓包工具 https://github.com/mitmproxy/mitmproxy<br> 

2、终端 https://github.com/Eugeny/tabby/releases/tag/v1.0.164<br> 

3、性能监控 perfdog （可能收费，但监控非常全）

4、代码检查+安全分析 https://github.com/MobSF/Mobile-Security-Framework-MobSF.git

5、静态代码检查（facebook） https://infer.liaohuqiu.net/docs/getting-started.html

6、性能监控 https://github.com/alibaba/mobileperf （部分指标数据监控不到）

7、Vysor 好用的安卓同屏软件

8、Katalon Studio 好用的web移动端自动化工具，可以录制脚本，体验未用

一些可参考的测试经验
--
1、jmeter相关 https://github.com/aliesbelik/awesome-jmeter 

2、各大厂公开的测试经验 https://github.com/abhivaikar/howtheytest

