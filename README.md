# record_something

done：

1、服务存活状态监控程序，部署在本机（mac）每日定时监控测试服务运行状态

2、网易接口测试平台集成的接口测试脚本，覆盖接口30+，每日定时执行

3、图片识别测试服务，部署在jenkins，解析指定路径下的MP4文件，按帧转为图片，转码为base64，批量请求定位服务，处理响应，统计结果

4、手机model数据爬虫，定期爬取github上的手机型号，并统计在xlsx文件中，部署jenkins，构建后发送至指定企业微信群

5、excel分析，遍历指定路径下的xlsx文件，并筛选出所需的数据另存为新文件新sheet，移动老文件到历史目录，定期清理

6、appium实现安卓端部分用例自动化，验证通过unittest及测试中截图与预期的图片相似度判断
ps：支持的验证方式
1）定位元素text与预期对比
2）提取toast文字与预期对比
3）截图与预期图对比（目前仅支持一模一样的，无法提取特征点）
4）截图提取图片文字与预期文字对比（通过百度开放api实现）
